URL: https://app.neurogenius.com/api/geniusx_brainskill/friend_fav_list <br>
Method: POST <br>

สำหรับดูรายชื่อเพื่อน

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
| user_code             | String        | Code ผู้ใช้ [Required] |


### ตัวอย่าง Request
```json
{
    "user_code" : "ABCDEF"
}
```

### ตัวอย่าง Response
```json
{
    "status": "success",
    "message": "Friend favorite list success",
    "result": [
        {
            "code": "ACFDER",
            "fname": "เอกวิทย์",
            "lname": "จิตตะเสโน",
            "img": "nophoto.jpg",
            "img_fulllink": "https://app.neurogenius.com/assets/images/users/nophoto.jpg",
            "img_original": "https://app.neurogenius.com/assets/images/users/original/nophoto.jpg"
        }
    ]
}
```
