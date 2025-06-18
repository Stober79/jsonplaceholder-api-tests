# JSONPlaceholder API Test Suite

Postman collection for testing the public API at https://jsonplaceholder.typicode.com

## Features

- 20+ test cases covering positive and negative scenarios
- Includes: posts, comments, users, todos, albums, photos
- Proper use of pm.test(), status checks, body validations

## Structure

### Positive tests
- `GET /posts`, `GET /posts/1`, `GET /posts?userId=1`
- `GET /comments`, `GET /comments/1`
- `GET /users`, `GET /users/1`
- `GET /todos`, `GET /albums`, `GET /photos`

### Negative tests
- Invalid post ID, invalid endpoint
- POST without body
- DELETE and PATCH on resources

##  How to Use

1. Open Postman
2. Import collection: `Postman_Collections/JSONPlaceholder_Collection.json`
3. Import environment: `Postman_Environment/jsonplaceholder-environment.json`
4. Select `JSONPlaceholder Environment`
5. Use Runner or Newman to execute tests

## Technologies

- Postman
- REST API
- pm.expect / JavaScript assertions

## Use cases

Great for showcasing API testing skills on GitHub or LinkedIn.
