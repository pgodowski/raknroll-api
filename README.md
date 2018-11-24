# raknroll-api
Raknroll api for searching services.
1. Push app on Heroku
git push heroku master
2. Visit app via heroku:
heroku open
3. Logs:
heroku logs --tail
4. Example usage:
a) find users by username
Request:

  https://XXXXXXXX/users?email=jedynakpoczta@gmail.com
  
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
  
