URL: https://app.neurogenius.com/api/geniusx_brainskill/delete_account <br>
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
| code                  | String        | รหัสผู้ใช้ [Required] |
| comment               | String        | ความคิดเห็น |




### ตัวอย่าง Request
```json
{
    "code": "ABCDEF",
    "comment": ""
}
```

### ตัวอย่าง Response
```json
{
    "status": "success",
    "message": "Delete account success"
}
```
