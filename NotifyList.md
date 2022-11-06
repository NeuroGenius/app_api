URL: https://app.neurogenius.com/api/geniusx_brainskill/notify <br>
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
| to                    | String        | Code ผู้ใช้ที่ต้องการดึง [Required] |
| type                  | Number        | ประเภทการแจ้งเตือน 1=ทั้งหมด 2=ส่วนตัว (default = 1) |


### ตัวอย่าง Request
```json
{
    "to" : "ABCDEF",
    "type" : "1"
}
```

### ตัวอย่าง Response
```json
{
    "status": "success",
    "result": [
        {
            "id": "1",
            "type": "1",
            "to": "ABCDEF",
            "from": "UVWXYZ",
            "title": "ทดสอบ",
            "message": "ทดสอบการแจ้งเตือน",
            "posted": "2022-10-08 15:20:37",
            "read": 0,
            "read_on": null
        }
    ]
}
```

type : 1=public, 2=private
