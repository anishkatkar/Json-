# Json-
My Project report 
curl -i -X POST \
   -H "Content-Type:application/json" \
   -d \
'{
    "token": "90932597|-31949277728968257|90948996",
    "cmd": "PUT",
    "dbName": "Employee",
    "rel": "Emp-Rel",
    "jsonStr": {
        "id": "1",
        "name": "Harry",
        "email": "Harry@login2xplore.com",
        "mobileno": "9967825111"
      "employee id": 111
    }
}' \
 'http://api.login2explore.com:5577/api/iml'
