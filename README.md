# springboot-database-security
Inserting Record
----------------
```bash
URL : http://localhost:4004/employee/save
HTTP Method : POST
```
Json Request :
```json
{
    "username":"sankar",
    "password":"1234",
    "roles":"ROLE_USER"
}
```
Json Response :
```json
{
    "id": 46,
    "username": "sankar",
    "password": "$2a$10$jhMUm1T5ZHIfKcBwZfSSpOrk5Mx9LtkKq.oWtylfQUM6A9rIsn2tG",
    "roles": "ROLE_USER"
}
```
