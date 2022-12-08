URL: https://app.neurogenius.com/api/geniusx_brainskill/friend_fav_del <br>
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
| user_code             | String        | Code ผู้ที่ทำรายการ [Required] |
| user_code_friend      | String        | Code ผู้ใช้ที่ต้องการลบรายการโปรด [Required] |


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
    "message": "Delete favorite friend success"
}
```
