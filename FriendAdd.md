URL: https://app.neurogenius.com/api/geniusx_brainskill/add_friend <br>
Method: POST <br>

### Header
| Field         | Type          | Description  |
| ------------- |---------------| -------------|
| Apikey        | String        | Your API Key |

### ตัวอย่าง Request header
```json
{
   "Apikey": "Your API Key",
}
```


### Body
| Field                 | Type          | Description             |
| -------------         |---------------| ------------------------|
| user_code             | String        | Code ผู้ขอ [Required] |
| user_code_friend      | String        | Code ผู้ถูกขอ [Required] |


### ตัวอย่าง Request
```json
{
    "user_code" : "ABCDEF",
    "user_code_friend" : "UVWXYZ"
}
```

### ตัวอย่าง Response
```json
{
    "status": "success",
    "message": "Add friend success"
}
```
