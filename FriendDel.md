URL: https://app.neurogenius.com/api/geniusx_brainskill/friend_del <br>
Method: POST <br>

สำหรับบันทึกการยอมรับเป็นเพื่อน

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
| user_code             | String        | Code ผู้ใช้ [Required] |
| user_code_friend      | String        | Code ผู้ใช้ เพื่อน [Required] |


### ตัวอย่าง Request
```json
{
    "user_code" : "UVWXYZ",
    "user_code_request" : "ABCDEF"
}
```

### ตัวอย่าง Response
```json
{
    "status": "success",
    "message": "Friend delete success"
}
```
