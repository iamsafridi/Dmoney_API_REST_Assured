## Dmoney API Test Automation REST Assured

This repository contains automated test scripts for the Dmoney API using Rest Assured. The test scripts automate various activities outlined in the task description.

### Setup Instructions
Follow these steps to set up and execute the automated tests:

## Usage
1. Navigate to the project directory.
2. Run the following command to install dependencies:
3. Execute the test scripts by running: gradle clean install

4. ## Update the config.properties File

1. **Set the `baseUrl`**:
   - Set the `baseUrl` to the URL of the Dmoney API.

2. **Update the partnerKey and token**:
   - Update the `partnerKey` and `token` for authentication.

## Prepare Necessary Data

1. **Create a JSON File**:
   - Create a JSON file containing the required information for creating customers and agents as outlined in the task description.
   
2. **Save the JSON File**:
   - Save the JSON file in the project directory.

## Execute the Tests

1. **Execute the Tests**:
   - Run the automated test suite to execute the tests against the Dmoney API.
   - Ensure that the tests are executed successfully without any failures.
   
   ```sh
   gradle clean test

## Test Scenarios

The automated tests cover the following scenarios:

- Login by admin.
- Creation of 2 new customers and an agent.
- Transfer of 2000 tk from the System account to the newly created agent.
- Deposit of 1500 tk to a customer from the agent account.
- Withdrawal of 500 tk by the customer to the agent.
- Money transfer of 500 tk to another customer.
- Payment of 100 tk to a merchant (01686606905) by the recipient customer.
- Verification of the balance of the recipient customer.


## Generating Allure Report

After running the tests, execute the following command to generate the Allure report:
1. allure generate allure-results --clean -output
2. allure serve allure-results


### Screenshots
![screencapture-192-168-11-10-59733-index-html-2024-03-20-13_03_11](https://github.com/iamsafridi/Dmoney_API_REST_Assured/assets/82276738/ce348659-4a70-4f00-af77-7a5b83adbaf7)

![screencapture-192-168-11-10-59733-index-html-2024-03-20-13_04_06](https://github.com/iamsafridi/Dmoney_API_REST_Assured/assets/82276738/15fe0b36-7378-4299-8afe-7253373b0b7a)

## Contributing

Contributions are welcome! Please feel free to submit bug reports, feature requests, or pull requests.

## Author
[Shahid Afridi]
