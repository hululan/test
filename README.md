## Examples
setup the path for the output file 
```bash
  out_path = 'final_permits1.csv'
```

all the query path and parameters are set, only run the file. 

and you will get a result in csv format


| OBJECTID | PermitNum | Longitude | Latitude | permitID | Max_class_code| functionalClassCode |
| :--- | :--- | :--- | :--- | :--- | :---: | :---: |
| 964512 | PA1117249 | -77.0898 | 38.92887 | 964512 | 19 | 19 |
| 966118 | PA1117364 | -77.0478 | 38.98817 | 966118 | 19 | 19 |
| 968294 | PA1117551 | -77.025 | 38.90087 | 968294 | 17 | 17 |

where Longitude and Latitude are the coordinate information under epsg:4326 cooordinate system, permitID is the ID of permit,
Max_class_code is the largest class code of each permit, and functionalClassCode is the record of the function class of roadway associated with each permit.

