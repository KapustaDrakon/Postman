POST https://blog.kata.academy/api/users
{
  "user": {
    "username": "vlad",
    "email": "vlados-abricos@gmail.com",
    "password": "password123"
  }
}

response

{
    "user": {
        "username": "vlad",
        "email": "vlados-abricos@gmail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzODhjZjcwMjA3NTk0MWIwMGU0NmUwMiIsInVzZXJuYW1lIjoidmxhZCIsImV4cCI6MTY3NTA5NDM4NCwiaWF0IjoxNjY5OTEwMzg0fQ.oYnISuL_UM09qvZiu9vjCTe4FLtlffh1cCnpxNucdeM"
    }
}


GET https://blog.kata.academy/api/user

{
  "user": {
    "email": "vlados-abricos@gmail.com",
    "password": "password123"
  }
}

{
    "user": {
        "username": "vlad",
        "email": "vlados-abricos@gmail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzODhjZjcwMjA3NTk0MWIwMGU0NmUwMiIsInVzZXJuYW1lIjoidmxhZCIsImV4cCI6MTY3NTA5ODc1NCwiaWF0IjoxNjY5OTE0NzU0fQ.fqp8i6bgVcm2uSa_lHSwFGDhv6AXfiDi_7fnmYFtc9I"
    }
}


POST https://blog.kata.academy/api/users/login

{
  "user": {
    "email": "vlados-abricos@gmail.com",
    "password": "password123"
  }
}

response

{
    "user": {
        "username": "vlad",
        "email": "vlados-abricos@gmail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzODhjZjcwMjA3NTk0MWIwMGU0NmUwMiIsInVzZXJuYW1lIjoidmxhZCIsImV4cCI6MTY3NTA5OTEzNiwiaWF0IjoxNjY5OTE1MTM2fQ.f-du2_QTsyO4Tq5BxW61XcTZ1oOQ83SCBvNU1SG0upU"
    }
}
