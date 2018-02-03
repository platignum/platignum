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

## Pagination

**Parameter:** per_page
**Default Value:** 0

**Parameter:** page

Resource Name | Endpoints
----------|----------
Apartment Maintenance | Apartment List <br> Method: GET <br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Apartment_Maintenance><br><br>Single Apartment<br>Method:GET<br><http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Apartment_Maintenance/1><br><br> Create Apartment <br>Method:POST<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Apartment_Maintenance><br><br> Update Apartment <br>Method:PUT<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Apartment_Maintenance/1><br><br> Delete Apartment<br>Method: DELETE<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Apartment_Maintenance/1>
Payment | Payment List <br> Method: GET <br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Payment><br><br>Single Payment<br>Method:GET<br><http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Payment/1><br><br> Create Payment <br>Method:POST<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Payment><br><br> Update Payment <br>Method:PUT<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Payment/1><br><br> Delete Payment<br>Method: DELETE<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Payment/1>
Building Maintenance | Building Maintenance List <br> Method: GET <br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Building_Maintenance><br><br>Single Building Maintenance<br>Method:GET<br><http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Building_Maintenance/1><br><br> Create Building Maintenance <br>Method:POST<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Building_Maintenance><br><br> Update Building Maintenance <br>Method:PUT<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Building_Maintenance/1><br><br> Delete Building Maintenance<br>Method: DELETE<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Building_Maintenance/1>
Tenant | Tenant List <br> Method: GET <br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Tenant><br><br>Single Tenant<br>Method:GET<br><http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Tenant/1><br><br> Create Tenant <br>Method:POST<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Tenant><br><br> Update Tenant <br>Method:PUT<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Tenant/1><br><br> Delete Tenant<br>Method: DELETE<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Tenant/1>
Lease | Lease List <br> Method: GET <br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Lease><br><br>Single Lease<br>Method:GET<br><http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Lease/1><br><br> Create Lease <br>Method:POST<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Lease><br><br> Update Lease <br>Method:PUT<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Lease/1><br><br> Delete Lease<br>Method: DELETE<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Lease/1>
Landlord | Landlord List <br> Method: GET <br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Landlord><br><br>Single Landlord<br>Method:GET<br><http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Landlord/1><br><br> Create Landlord <br>Method:POST<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Landlord><br><br> Update Landlord <br>Method:PUT<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Landlord/1><br><br> Delete Landlord<br>Method: DELETE<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Landlord/1>
Rent | Rent List <br> Method: GET <br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Rent><br><br>Single Rent<br>Method:GET<br><http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Rent/1><br><br> Create Rent <br>Method:POST<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Rent><br><br> Update Rent <br>Method:PUT<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Rent/1><br><br> Delete Rent<br>Method: DELETE<br> <http://reqres-apartmentrental.1d35.starter-us-east-1.openshiftapps.com/api/Rent/1>