URL: https://app.neurogenius.com/api/geniusx_brainskill/update_profile <br>
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
| token                  | String        | Token ผู้ใช้ [Required] |
| firstname_th           | String        | ชื่อ (ภาษาไทย) [Required] |
| lastname_th            | String        | นามสกุล (ภาษาไทย) [Required] |
| firstname_en           | String        | ชื่อ (English) [Required] |
| lastname_en            | String        | นามสกุล (English) [Required] |
| birthday               | String        | วันเกิด รูปแบบ yyyy-mm-dd |
| idcard                 | String        | เลขประจำตัวประชาชน |




### ตัวอย่าง Request
```json
{
    "token" : "acbdefghijk",
    "firstname_th" : "เอกวิทย์",
    "lastname_th" : "จิตตะเสโน",
    "firstname_en" : "Eakkawit",
    "lastname_en" : "Jittaseno",
    "birthday" : "1990-07-20",
    "idcard" : "1909800000000"
}
```

### ตัวอย่าง Response
```json
{
    "status": "success",
    "message": "Update profile success"
}
```
