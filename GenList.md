URL: https://app.neurogenius.com/api/geniusx_brainskill/gen_list <br>
Method: GET <br>

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
            "name": "รุ่นที่ 1",
            "year": "2019",
            "img": "gen1.jpg",
            "img_fulllink": "https://app.neurogenius.com/assets/images/gen/gen1.jpg",
            "status": "1"
        },
        {
            "id": "2",
            "name": "รุ่นที่ 2",
            "year": "2020",
            "img": "gen2.jpg",
            "img_fulllink": "https://app.neurogenius.com/assets/images/gen/gen2.jpg",
            "status": "1"
        },
        {
            "id": "3",
            "name": "รุ่นที่ 3",
            "year": "2021",
            "img": "gen3.jpg",
            "img_fulllink": "https://app.neurogenius.com/assets/images/gen/gen3.jpg",
            "status": "1"
        },
        {
            "id": "4",
            "name": "รุ่นที่ 4",
            "year": "2022",
            "img": "gen4.jpg",
            "img_fulllink": "https://app.neurogenius.com/assets/images/gen/gen4.jpg",
            "status": "1"
        }
    ]
}
```
