URL: https://app.neurogenius.com/api/geniusx_brainskill/friend_list <br>
Method: POST <br>

สำหรับดูรายชื่อเพื่อน

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


### ตัวอย่าง Request
```json
{
    "user_code" : "ABCDEF"
}
```

### ตัวอย่าง Response
```json
{
    "status": "success",
    "message": "Friend list success",
    "result": [
        {
            "user_code_friend": "VUWXYZ",
            "approved": "0"
        }
    ]
}
```
