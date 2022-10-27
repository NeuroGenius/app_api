
URL: https://app.neurogenius.com/api/geniusx_brainskill/cms/{{CMS_NAME}} <br>
Method: GET <br> 
### ตัวอย่างการเรียก URL {{CMS_NAME}} 
term = ข้อตกลงและเงื่อนไขการใช้บริการ [ https://app.neurogenius.com/api/geniusx_brainskill/cms/term ] <br>
privacy = นโยบายความเป็นส่วนตัว [ https://app.neurogenius.com/api/geniusx_brainskill/cms/privacy ] <br>
help = ช่วยเหลือ [ https://app.neurogenius.com/api/geniusx_brainskill/cms/help ]

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


### ตัวอย่าง Response
```json
{
    "status": "success",
    "result": [
        {
            "id": "1",
            "name": "รับสมัครรุ่น 4",
            "img": "hero_gnx4.png",
            "img_fulllink": "https://app.neurogenius.com/assets/images/hero/hero_gnx4.png",
            "link": "https://www.neurogenius.com/geniusx/x4",
            "link_text": "คลิกเพื่อสมัคร"
        }
    ]
}
```
