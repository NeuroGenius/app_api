URL: https://app.neurogenius.com/api/geniusx_brainskill/otp_validate <br>
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
| Field             | Type          | Description             |
| -------------     |---------------| ------------------------|
| token             | String        | โทเค็นสำหรับตอบกลับกิจกรรมนี้ [Required] |
| otp_code          | String        | รหัส OTP ใน SMS [Required] |
| ref_code          | String        | Ref code คือการอ้างอิงของรหัสพร้อมรหัส OTP ใน SMS [Optional] |




### ตัวอย่าง Request
```json
{
    "token": "tik8t84xkhuy2dtpscwl",
    "otp_code": "123456"
}
```

### ตัวอย่าง Response
```json
{
    "status": "success",
    "message": "OTP code is valid"
}
```
