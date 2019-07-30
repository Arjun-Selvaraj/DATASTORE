<----EXPLANATION---->

1.The location of the data source is selected:
   i)Default location -The same location as java files location.
  ii)USER defined location-Location obtained from user and file is created with a default name.

2.JSON files are created and used for manipulations.

3.There are three operations.
  
   1)CREATE:
          Checks whether the key specified by the user is already present, if present print as already present. 
          If  not then insert the key and value pair into the JSON file in JSON array.
   2)READ:
          Gets the user input whether to retrieve all data or read based on user given key value.
          For read-all operation, all the key along with thier value are displayed in consecutive lines.If no record is print it will display as empty JSON array.
          For read operation based on key,the specific key is searched in the JSON file and if found the value is displayed along with the key.
          If key is not found after searching entire JSON file then display as key not found.
   3)DElETE:
          Get the key from the user.
          Check whether the particular key is present using similar read function but with a return type.
          If the key is present then delete the key and it's value pair.
          If key is not present then print as ELEMENT not found.                  
