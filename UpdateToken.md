URL: https://app.neurogenius.com/api/geniusx_brainskill/update_token <br>
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
| token                  | String        | Token ผู้ใช้ [Required] |
| onesignal_token        | String        | onesignal Push Token |
| onesignal_playerid     | String        | onesignal Player ID |




### ตัวอย่าง Request
```json
{
    "token" : "acbdefghijk",
    "onesignal_token" : "j6FnydB9N2UK3gdDEg7eSJEA7Pe7SdMb",
    "onesignal_playerid" : "f9f0ab29-fa73-46d7-96c3-8ed372969eb6"
}
```

### ตัวอย่าง Response
```json
{
    "status": "success",
    "message": "Update token success"
}
```
