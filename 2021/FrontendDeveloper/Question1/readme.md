# Technical Question

[https://randomuser.me/api/?results=10](https://randomuser.me/api/?results=10)

This is a public api which gives random data of n users in json. Display specific information from the data on a web page.

Information to display:

Full name

Email

Address i.e. Street, city, state, country and postcode separated by comma.

Sample data:

```json
{
    "results": [
        {
            "gender": "female",
            "name": {
                "title": "Ms",
                "first": "Annabelle",
                "last": "Bélanger"
            },
            "location": {
                "street": {
                    "number": 1425,
                    "name": "Elgin St"
                },
                "city": "Red Rock",
                "state": "Manitoba",
                "country": "Canada",
                "postcode": "N0N 3O1",
                "coordinates": {
                    "latitude": "-67.8310",
                    "longitude": "136.0344"
                },
                "timezone": {
                    "offset": "-10:00",
                    "description": "Hawaii"
                }
            },
            "email": "annabelle.belanger@example.com",
            "login": {
                "uuid": "12f127a2-b765-494a-8e42-4eedf5f2cba2",
                "username": "blackelephant939",
                "password": "doggy",
                "salt": "CAwKrOI4",
                "md5": "e14d60dc8f31d972387d7761e821bf18",
                "sha1": "7aea1334dbc4666b8d749369e1043683455d3961",
                "sha256": "ef404e05c3e4b191b7cbf5787dd980a1df071b66de7be56db8b811af2a688d72"
            },
            "dob": {
                "date": "1993-10-17T15:46:34.140Z",
                "age": 28
            },
            "registered": {
                "date": "2016-11-30T00:47:50.713Z",
                "age": 5
            },
            "phone": "391-776-1774",
            "cell": "992-464-8545",
            "id": {
                "name": "",
                "value": null
            },
            "picture": {
                "large": "https://randomuser.me/api/portraits/women/91.jpg",
                "medium": "https://randomuser.me/api/portraits/med/women/91.jpg",
                "thumbnail": "https://randomuser.me/api/portraits/thumb/women/91.jpg"
            },
            "nat": "CA"
        }
    ],
    "info": {
        "seed": "2823895ee9926b5f",
        "results": 1,
        "page": 1,
        "version": "1.3"
    }
}
```


Sample Output:

![image](https://user-images.githubusercontent.com/17079876/124132057-0a741600-da9e-11eb-8df7-7126d846c81d.png)
