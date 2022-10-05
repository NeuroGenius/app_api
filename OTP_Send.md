URL: https://app.neurogenius.com/api/geniusx_brainskill/otp_send <br>
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
| phone              | String        | หมายเลขโทรศัพท์ปลายทาง (08xxxxxxxx) [Required]                  |
| ref_code  | String        | Ref code คือการอ้างอิงของรหัสพร้อมรหัส OTP ใน SMS [Optional]       |




### ตัวอย่าง Request
```json
{
    "phone": "0871234567"
}
```

### ตัวอย่าง Response
```json
{
    "status": "success",
    "message": "SMS has been sent",
     "result": {
        "token": "tik8t84xkhuy2dtpscwl",
        "ref_code": "ABCDEF"
    }
}
```
