URL: https://app.neurogenius.com/api/geniusx_brainskill/delete_picture_profile <br>
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
| token                 | String        | Token ผู้ใช้ [Required] |




### ตัวอย่าง Request
```json
{
    "token" : "acbdefghijk"
}
```

### ตัวอย่าง Response
```json
{
    "status": "success",
    "message": "Delete picture success"
}
```
