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
Apartment Maintenance | Apartment List <br> Method: GET <br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Apartment_Maintenance><br><br>Single Apartment<br>Method:GET<br><http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Apartment_Maintenance/1><br><br> Create Apartment <br>Method:POST<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Apartment_Maintenance><br><br> Update Apartment <br>Method:PUT<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Apartment_Maintenance/1><br><br> Delete Apartment<br>Method: DELETE<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Apartment_Maintenance/1>
Payment | Payment List <br> Method: GET <br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/Payment><br><br>Single Payment<br>Method:GET<br><http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/Payment/1><br><br> Create Payment <br>Method:POST<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/Payment><br><br> Update Payment <br>Method:PUT<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/Payment/1><br><br> Delete Payment<br>Method: DELETE<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Payment/1>
Building Maintenance | Building Maintenance List <br> Method: GET <br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/Building_Maintenance><br><br>Single Building Maintenance<br>Method:GET<br><http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/Building_Maintenance/1><br><br> Create Building Maintenance <br>Method:POST<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/Building_Maintenance><br><br> Update Building Maintenance <br>Method:PUT<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/Building_Maintenance/1><br><br> Delete Building Maintenance<br>Method: DELETE<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Building_Maintenance/1>
Building Maintenance | Building Maintenance List <br> Method: GET <br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/Building_Maintenance><br><br>Single Building Maintenance<br>Method:GET<br><http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/Building_Maintenance/1><br><br> Create Building Maintenance <br>Method:POST<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/Building_Maintenance><br><br> Update Building Maintenance <br>Method:PUT<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/Building_Maintenance/1><br><br> Delete Building Maintenance<br>Method: DELETE<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Building_Maintenance/1>