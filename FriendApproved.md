URL: https://app.neurogenius.com/api/geniusx_brainskill/friend_approved <br>
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
| user_code             | String        | Code ผู้ใช้ ที่เข้ามาอนุมัติ [Required] |
| user_code_request     | String        | Code ผู้ใช้ที่ส่งคำขอเป็นเพื่อน [Required] |


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
    "message": "Friend approved success"
}
```
