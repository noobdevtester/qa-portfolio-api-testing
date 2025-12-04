# QA Portfolio – API Testing with JSONPlaceholder

## Project Overview
This project demonstrates manual API testing of the JSONPlaceholder public REST API.
The goal is to validate common API endpoints by verifying responses, status codes, and error handling.

## Application Under Test
JSONPlaceholder – a free, hosted REST API for testing and prototyping.

## Scope of Testing
⦁	Retrieve lists and single items for posts, comments, albums, photos, todos, and users
⦁	Test creation of new posts using POST /posts
⦁	Update existing posts with PUT and PATCH /posts/{id}
⦁	Delete posts using DELETE /posts/{id}
⦁	Validate filtering of comments by post ID (e.g., /comments?postId=1)
⦁	Check response status codes and error handling for invalid requests

## Testing Types Performed
- Functional API testing
- Positive and negative testing
- Response validation
- Status code verification

## Tools Used
- Postman for sending API requests and managing test collections
- GitHub for documentation and version control

## How to Use This Repository
- Review `api-test-cases.md` for detailed API test cases.
- Review `api-test-report.md` for test execution summaries and findings.
- Import `JSON API Testing.postman_collection` into Postman to run the tests interactively.
