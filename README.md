repository data is 

```dart 
[
  {
    "user_id": "583c3ac3f38e84297c002546",
    "email": "test@test.com",
    "name": "test@test.com",
    "given_name": "Hello",
    "family_name": "Test",
    "nickname": "test",
    "last_ip": "94.121.163.63",
    "logins_count": 15,
    "created_at": "2016-11-28T14:10:11.338Z",
    "updated_at": "2016-12-02T01:17:29.310Z",
    "last_login": "2016-12-02T01:17:29.310Z",
    "email_verified": true
  },
  {
    "user_id": "583c5484cb79a5fe593425a9",
    "email": "test1@test.com",
    "name": "test1@test.com",
    "given_name": "Hello1",
    "family_name": "Test1",
    "nickname": "test1",
    "last_ip": "94.121.168.53",
    "logins_count": 1,
    "created_at": "2016-11-28T16:00:04.209Z",
    "updated_at": "2016-11-28T16:00:47.203Z",
    "last_login": "2016-11-28T16:00:47.203Z",
    "email_verified": true
  },
  {
    "user_id": "583c57672c7686377d2f66c9",
    "email": "aaa@aaa.com",
    "name": "aaa@aaa.com",
    "given_name": "John",
    "family_name": "Dough",
    "nickname": "aaa",
    "last_ip": "94.121.168.53",
    "logins_count": 2,
    "created_at": "2016-11-28T16:12:23.777Z",
    "updated_at": "2016-11-28T16:12:52.353Z",
    "last_login": "2016-11-28T16:12:52.353Z",
    "email_verified": true
  },
  {
    "user_id": "5840b954da0529cd293d76fe",
    "email": "a@a.com",
    "name": "a@a.com",
    "given_name": "Jane",
    "family_name": "Dough",
    "nickname": "a",
    "last_ip": "94.121.163.63",
    "logins_count": 3,
    "created_at": "2016-12-01T23:59:16.473Z",
    "updated_at": "2016-12-01T23:59:53.474Z",
    "last_login": "2016-12-01T23:59:53.474Z",
    "email_verified": true
  },
  {
    "user_id": "584a9d13e808bcf75f05f580",
    "email": "test9999@test.com",
    "given_name": "Dummy",
    "family_name": "User",
    "created_at": "2016-12-09T12:01:23.787Z",
    "updated_at": "2016-12-09T12:01:23.787Z",
    "email_verified": false
  }
]
```

## Assignment: Backend Development using Dart and Shelf Package

In this assignment, you will create a backend server using Dart programming language and the Shelf package to handle HTTP requests and responses. The server will have endpoints to display all users, display one user by id, display one user by email, and remove one user by id. You should use the shelf_hotreload and dart_code_metrics packages to ensure good coding practices and ease of development.

## Requirements:
1. Create a Dart project and install the Shelf and shelf_hotreload packages.
2. Create a "model" file to represent the user object with the required properties.
3. Create a "repository" file to store the users in memory and handle CRUD operations on the user objects.
4. Create a "routes" folder to contain the router handlers for each endpoint.
5. Create a "response" folder to contain the handler methods for each endpoint.
6. Implement an endpoint to display all users. This endpoint should return a JSON response containing all user objects.
7. Implement an endpoint to display one user by id. This endpoint should accept an id parameter in the request URL and return a JSON response containing the user object with the matching id.
8. Implement an endpoint to display one user by email. This endpoint should accept an email parameter in the request URL and return a JSON response containing the user object with the matching email.
9. Implement an endpoint to remove one user by id. This endpoint should accept an id parameter in the request URL and remove the user object with the matching id from the repository.

## Grading Criteria:
1. Correct implementation of all four endpoints.
2. Use of the Shelf package to handle HTTP requests and responses.
3. Use of the shelf_hotreload and dart_code_metrics packages to ensure good coding practices and ease of development.
4. Use of a "model" file to represent the user object with the required properties.
5. Use of a "repository" file to store the users in memory and handle CRUD operations on the user objects.
6. Use of a "routes" folder to contain the router handlers for each endpoint.
7. Use of a "response" folder to contain the handler methods for each endpoint.
8. Code readability and documentation.
9. Proper error handling.

## Note:
You can use the provided JSON data to create test users and test the endpoints.
