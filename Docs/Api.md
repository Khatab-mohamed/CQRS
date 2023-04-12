# Bubber Dinner API
-[Bubbber Dinner Api](#bubber-dinner-api)
    -[Auth](#auth)
        -[Register](#register)
            -[Register Request](#register-request)
            -[Register Response](#register-response)
        -[Login](#login)
            -[Login Request](#login-request)
            -[Login Response](#login-response)
        
## Auth

### Register

```json
POST {{host}}/auth/register
```
#### Register Request
```json
{
    "firstName":"John",
    "lastName":"Doe",
    "email":"john@domain.com",
}
```
#### Register Response

```js
200 OK
```
### Login

```json
POST {{host}}/auth/login
```
#### Login Request
```json
{
    "email":"john@domain.com",
    "password":"P@w0rd"
}
```
#### Login Response

```js
200 OK token:"agvsdgavgsagsdadgsadgas"
```
