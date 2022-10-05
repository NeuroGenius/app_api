URL: https://app.neurogenius.com/api/geniusx_brainskill/user <br>
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
| code                  | String        | รหัสผู้ใช้ [Required] |




### ตัวอย่าง Request
```json
{
    "code": "ABCDEF"
}
```

### ตัวอย่าง Response
```json
{
   "status": "success",
   "result": {
      "code": "ABCDEF",
      "name_th": "ธงชัย ใจดี",
      "name_en": "Thongchai Jaidee",
      "firstname_th": "ธงชัย",
      "lastname_th": "ใจดี",
      "nickname_th": "ธง",
      "first_en": "Thongchai",
      "lastname_en": "Jaidee",
      "nickname_en": "Thong",
      "birthday": "1990-12-31",
      "email": "thongchai@neurogenius.com",
      "email_active": "1",
      "address": {
            "addr_no": "",
            "addr_room": "",
            "addr_floor": "",
            "addr_moo": "",
            "addr_soi": "",
            "addr_building": "",
            "addr_road": "",
            "addr_zipcode": "",
            "addr_province": "",
            "addr_district": "",
            "addr_sub_district": ""
        },
      "company": "NeuroGenius Co.,Ltd.",
        "company_address": {
            "addr_2_no": "944",
            "addr_2_room": "S24056",
            "addr_2_floor": "24",
            "addr_2_moo": "",
            "addr_2_soi": "",
            "addr_2_building": "มิตรทาวน์ ออฟฟิศ ทาวเวอร์",
            "addr_2_road": "พระราม 4",
            "addr_2_zipcode": "10330",
            "addr_2_province": "กรุงเทพมหานคร",
            "addr_2_district": "ปทุมวัน",
            "addr_2_sub_district": "วังใหม่"
        },
        "occupatione": "",
        "position": "Web Developer",
        "img": "nophoto.jpg",
        "img_fulllink": "https://app.neurogenius.com/assets/images/users/nophoto.jpg",
        "active": "1"
   }
}
```
