URL: https://app.neurogenius.com/api/geniusx_brainskill/update_picture_profile <br>
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
| filename              | File          | ไฟล์รูปภาพ [Required] |



### ตัวอย่าง Request
```php
array('filename'=> new CURLFILE('/C:/Users/imjaka/Desktop/imgprofile.jpg'),'token' => 'acbdefg')
```

### ตัวอย่าง Response
```json
{
    "status": "success",
    "message": "Update picture success",
    "data": {
        "img_filename": "ABCDEF-1667292800.jpg",
        "img_small": "https://app.neurogenius.com/assets/images/users/original/ABCDEF-1667292800.jpg",
        "img_original": "https://app.neurogenius.com/assets/images/users/ABCDEF-1667292800.jpg"
    }
}
```
