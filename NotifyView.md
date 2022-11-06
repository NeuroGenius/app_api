URL: https://app.neurogenius.com/api/geniusx_brainskill/notify_view <br>
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
| id                    | String        | ID Notification ที่ต้องการดู [Required] |


### ตัวอย่าง Request
```json
{
    "id" : 1
}
```

### ตัวอย่าง Response
```json
{
    "status": "success",
    "result":{
            "id": "1",
            "type": "1",
            "to": "ABCDEF",
            "from": "UVWXYZ",
            "title": "ทดสอบ",
            "preview": "ทดสอบการแจ้งเตือน",
            "message": "<p style=\"text-align:center\">นี่คือข้อความทดสอบการแจ้งเตือนทดสอบการแจ้งเตือน</p>",
            "posted": "2022-10-08 15:20:37"
        }
}
```

type : 1=public, 2=private
