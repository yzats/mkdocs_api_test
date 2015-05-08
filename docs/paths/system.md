#System
----------------
##GET system - Get active system configuration

####Description
Lorem ipsum dolor sit amet, consectetuer adipiscing elit

####Resource Path
`/manager/v1/system`

####Request 
*none*

####Response
| Parameter  | Type  | Enum  | Description  |
|------------|-------|-------|--------------|
| name  | integer  |   | Lorem ipsum dolor sit amet, consectetuer adipiscing elit   |
| location  | string  |   | Donec sodales sagittis magna  |
| cliTimeout  | string  |   | In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo  |

####Example Request
```
GET /manager/v1/system HTTP/1.1
```

####Example Response
```
HTTP/1.1 200 OK
...
{ 
	"name": "Foo", 
	"location": "Houston", 
	"cliTimeout": 10, 
}
```

-----------------------------

## POST system/reset - Reset the entire network 

####Description
Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet nec, vulputate eget, arcu.

####Resource Path
`/manager/v1/system`

####Request 
*none*

####Response
*none*

####Example Request
```
POST /manager/v1/system/reset HTTP/1.1
```
####Example Response
```
HTTP/1.1 200 OK
...
```