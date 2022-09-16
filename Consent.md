URL: https://app.neurogenius.com/api/geniusx_brainskill/consent <br>
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
| U_ID              | String        | ไอดีผู้ใช้                  |
| CONSENT_APPROVED  | String        | 1:ยอมรับ 0 ไม่ยอมรับ       |




### ตัวอย่าง Request
```json
{
    "U_ID": 1,
    "CONSENT_APPROVED" : 1
}
```

### ตัวอย่าง Response
```json
{
    "status": "success",
    "message": "Data has been updated"
}
```
