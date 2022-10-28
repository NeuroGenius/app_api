URL: https://app.neurogenius.com/api/geniusx_brainskill/update_work <br>
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
| work                  | String        | อาชีพ [Required] |
| company               | String         | ชื่อสถานที่ทำงาน/ธุรกิจส่วนตัว [Required] |




### ตัวอย่าง Request
```json
{
    "token" : "acbdefghijk",
    "work" : "พนักงานเอกชน",
    "company" : "NeuroGenius Co.,Ltd."
}
```

### ตัวอย่าง Response
```json
{
    "status": "success",
    "message": "Update work success"
}
```
