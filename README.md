# Building_License_Cleaning
Cleaning project of building license from Taipei 建築使用執照資料清理
- Raw data is from Taipei Open data platform, the format is .xml
- the notebook will create 4 output files as a result:
    - usage_normal: an overview grouped by license #, includes zoning, total level, bulding price(in 10 thousand), buiding height, total household etc.
    - usage_address: address grouped by license #
    - usage_floor: level, usage and area(in squared meter) of the floor, grouped by license #
    - usage_lanCode: land code (地段地號) grouped by license #
    
    
|Overview|Address|
| :-------------: |:-------------:|
| ![](https://github.com/ShihWen/Building_License_Cleaning/blob/master/image/bdn_overview.png)|![](https://github.com/ShihWen/Building_License_Cleaning/blob/master/image/bdn_address.png)|

|Floor|Landcode|
| :-------------: |:-------------:|
| ![](https://github.com/ShihWen/Building_License_Cleaning/blob/master/image/bdn_floor.png)|![](https://github.com/ShihWen/Building_License_Cleaning/blob/master/image/bdn_landCode.png)|
