# raknroll-api
Raknroll api for searching services.
1. Run project
docker run  \
      -p 3000:3000  -v `pwd`:/data  \
      williamyeh/json-server        \
      --watch db.json
2. Example usage:
a) find users by username
Request:

  http://0.0.0.0:3000/users?email=jedynakpoczta@gmail.com
  
Response:
[
    {
        "id": 1,
        "name": "Krzysztof",
        "surname": "Damian",
        "createdDate": "2018-12-11",
        "email": "jedynakpoczta@gmail.com"
    }
]
  
