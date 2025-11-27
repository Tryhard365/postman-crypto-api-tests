[![API Testing](https://github.com/Tryhard365/postman-crypto-api-tests/actions/workflows/api-tests.yml/badge.svg)](https://github.com/Tryhard365/postman-crypto-api-tests/actions/workflows/api-tests.yml)
# Crypto API Automated Testing Suite

This repo demonstrates automated API tests for live Bitcoin
and Ethereum price endpoints using Postman, Newman CLI, and continuous integration with GitHub Actions.

​Features

    API tests for valid and invalid crypto endpoints using the CoinGecko public API

    Separate requests for Bitcoin and Ethereum price checks in USD, plus a multi-crypto endpoint

    Negative test for invalid coin IDs to verify safe handling of bad input

    Automated regression suite executed via Newman CLI

    CI/CD pipeline with GitHub Actions running tests on every push and exposing status via badge

    ​

Usage

    Download Postman and import crypto-api-tests.json.

    Run tests manually in Postman, or execute them with Newman from the terminal:

bash
newman run crypto-api-tests.json

To see CI results:

    Fork or clone this repo

    Push any change to the main branch

    Open the Actions tab to view the latest workflow run and logs.

        ​

Project Structure

    crypto-api-tests.json — Postman API test collection (requests, assertions, and scenarios)

    .github/workflows/api-tests.yml — GitHub Actions workflow that installs Newman and runs the collection on each push.

    ​

Author

Michael A - QA Automation Engineer
