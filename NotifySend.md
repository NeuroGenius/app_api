URL: https://app.neurogenius.com/api/geniusx_brainskill/notify_send <br>
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
| type                  | Int           | ประเภทการแจ้งเตือน 1=ทั้งหมด 2=ส่วนตัว [Required]|
| from                  | String        | Code ผู้ใช้ที่ส่งข้อความ หากเป็นระบบ ให้ระบบ SYSTEM [Required] |
| to                    | String        | Code ผู้ใช้ที่ต้องการส่งแจ้งเตือน เว้นว่างหากส่งทั้งหมด |
| title                 | String        | หัวเรื่อง (ส่วนนี้จะแสดงบนแจ้งเตือน) [Required] |
| message               | String        | ข้อความแบบย่อ |
| detail                | String        | ข้อความเต็ม|


### ตัวอย่าง Request
```json
{
    "type" : 2,
    "from" : "SYSTEM",
    "to": "HUTQWC",
    "title": "ทดสอบส่งข้อความหาส่วนตัว",
    "message": "นี่คือการทดสอบส่งข้อความหาส่วนตัว",
    "detail": "<b>นี่คือการทดสอบส่งข้อความหาส่วนตัว</b>"
}
```

### ตัวอย่าง Response
```json
{
    "status": "success",
    "message": "send to HUTQWC"
}
```

type : 1=public, 2=private
