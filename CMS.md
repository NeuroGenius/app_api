
URL: https://app.neurogenius.com/api/geniusx_brainskill/cms/{{CMS_NAME}} <br>
Method: GET <br> 
### ตัวอย่างการเรียก URL {{CMS_NAME}} 
terms = ข้อตกลงและเงื่อนไขการใช้บริการ [ https://app.neurogenius.com/api/geniusx_brainskill/cms/terms ] <br>
privacy = นโยบายความเป็นส่วนตัว [ https://app.neurogenius.com/api/geniusx_brainskill/cms/privacy ] <br>
help = ช่วยเหลือ [ https://app.neurogenius.com/api/geniusx_brainskill/cms/help ] <br>
tip = แนะนำการใช้แอป [ https://app.neurogenius.com/api/geniusx_brainskill/cms/tip ]

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
            "title": "ข้อตกลงและเงื่อนไขการใช้บริการ",
            "link": "https://app.neurogenius.com/terms",
            "content": "<p>เว็บไซต์ neurogenius.com (ซึ่งต่อไปนี้จะเรียกว่า &ldquo;เว็บไซต์&rdquo;)..."
        }
    ]
}
```
