# HousingEstateMaintenance
Feed Apartment tables data real time in data lake and create real time online analytics engine to report issues and warn users and residents. Issues like Problem with Electrics, Dripping Tap, Plumbing issues



## Register

### Request
**Method:** POST

**EndPoint:** <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/register>

**Data:**
```
{
    "email": "sydney@fife",
    "password": "pistol"
}
```
### Response
```
{
    "token": "QpwL5tke4Pnpja7X"
}
```

## Login

### Request
**Method:** POST

**EndPoint:** <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/login>

**Data:**
```
{
    "email": "peter@klaven",
    "password": "cityslicka"
}
```
### Response
```
{
    "token": "QpwL5tke4Pnpja7X"
}
```

Resource Name | Endpoints
----------|----------
Apartment Maintenance | Apartment List <br> Method: GET <br> http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/Apartment_Maintenance
