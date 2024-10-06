
# Kanggo QA Test API

Automation testing for the Reqres API using Postman.

## Running the Test

To run the tests using Postman, follow these steps:

1. **Clone this repository** to your local machine:
    ```bash
    git clone https://github.com/jejefjefri/kanggo-qa-test-API.git
    ```
    Replace `[USERNAME]` with your GitHub username.

2. **Import Collection**:
    - Open Postman.
    - Select `Import`.
    - Select the `kanggo-qa-test API Test.postman_collection.json` file from this repository's folder.

3. **Run Tests Using Postman Runner**:
    - Open Postman Runner.
    - Select the imported collection.
    - Click `Run` to execute the API tests.

## Tested Endpoints

The following endpoints are tested:
- `GET /api/users`
- `GET /api/users/2`
- `POST /api/users`
- `PUT /api/users/2`
- `DELETE /api/users/2`

## Project Structure

- `reqres-collection.json`: Postman collection file for testing the Reqres API.
