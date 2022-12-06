URL: https://app.neurogenius.com/api/geniusx_brainskill/notify_read <br>
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
| id                    | String        | ID Notification [Required] |
| code                  | String        | code ผู้ใช้ที่อ่าน [Required] |


### ตัวอย่าง Request
```json
{
    "id" : 1,
    "code" : "ABCDEF"
}
```

### ตัวอย่าง Response
```json
{
    "status": "success",
    "message": "Notification is read"
}
```


