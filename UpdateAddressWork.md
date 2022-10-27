URL: https://app.neurogenius.com/api/geniusx_brainskill/update_addrwork <br>
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
| addr_no               | String        | เลขที่ [Required] |
| addr_room             | String        | ห้องเลขที่ |
| addr_floor            | String        | ชั้น |
| addr_moo              | String        | หมู่ |
| addr_soi              | String        | ซอย |
| addr_building         | String        | อาคาร/หมู่บ้าน |
| addr_road             | String        | ถนน |
| addr_zipcode          | String        | รหัสไปรษณีย์ [Required] |
| addr_province         | String        | จังหวัด |
| addr_district         | String        | เขต/อำเภอ |
| addr_sub_district     | String        | แขวง/ตำบล |




### ตัวอย่าง Request
```json
{
    "token" : "acbdefghijk",
    "addr_no" : "944",
    "addr_room" : "S24056",
    "addr_floor" : "24",
    "addr_moo" : "",
    "addr_soi" : "",
    "addr_building" : "มิตรทาวน์ ออฟฟิศ ทาวเวอร์",
    "addr_road" : "พระราม 4",
    "addr_zipcode" : "10330",
    "addr_province" : "กรุงเทพมหานคร",
    "addr_district" : "ปทุมวัน",
    "addr_sub_district" : "วังใหม่"
}
```

### ตัวอย่าง Response
```json
{
    "status": "success",
    "message": "Update address success"
}
```
