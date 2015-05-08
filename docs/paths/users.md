#Users
----------------
##GET users - Get active user list

####Description
Lorem ipsum dolor sit amet, consectetuer adipiscing elit

####Resource Path
`/manager/v1/users`

####Request 
*none*

####Response
| Parameter  | Type  | Enum  | Description  |
|------------|-------|-------|--------------|
| userid  | string  |   | Lorem ipsum dolor sit amet, consectetuer adipiscing elit   |

####Example Request
```
GET /manager/v1/users HTTP/1.1
...
```

####Example Response
```
HTTP/1.1 200 OK
...
{ 
HTTP/1.1 200 OK
...
{
  "users": [
    {
      "userid": "fred"
    },
    {
      "userid": "paul"
    },
    {
      "userid": "john"
    }
  ]
}
}
```

