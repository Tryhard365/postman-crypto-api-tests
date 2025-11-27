[![API Testing](https://github.com/Tryhard365/postman-crypto-api-tests/actions/workflows/api-tests.yml/badge.svg)](https://github.com/Tryhard365/postman-crypto-api-tests/actions/workflows/api-tests.yml)
# Crypto API Automated Testing Suite

This repo demonstrates automated API tests for Bitcoin [finance:Bitcoin] price endpoints using Postman, Newman CLI, and continuous integration with GitHub Actions.

## Features

- API tests for valid and invalid crypto endpoints (CoinGecko [finance:CoinGecko])
- Response validation for status, keys, and negative cases
- Automated regression suite with Newman CLI
- CI/CD pipeline via GitHub Actions running tests on every push

## Usage

1. Download [Postman](https://www.postman.com/downloads/) and import `crypto-api-tests.json`.
2. Run tests manually in Postman, or use Newman from the terminal:
    ```
    newman run crypto-api-tests.json
    ```
3. To see CI results:
    - Clone this repo
    - Push any change to `main`
    - Check "Actions" tab for results!

## Project Structure

- `crypto-api-tests.json` — Postman API test collection
- `.github/workflows/api-tests.yml` — GitHub Actions for CI

## Author

Michael A • QA Automation Engineer
