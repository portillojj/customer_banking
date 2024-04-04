
# Module 3 Challenge - Customer Banking

## Background
You'll be creating a customer banking system that allows users to calculate and track interest earned on savings and CD accounts. By running this application, users will be able to enter their savings and CD account information, see the interest earned, and view the updated balances after a specified number of months.

## Before you begin
- Before starting the assignment, be sure to complete the following steps:
   - [x] Create a new repository for this project called customer_banking. Do not add this homework assignment to an existing repository.
   - [x] Clone the new repository to your computer.
   - [x] Inside your local Git repository, add the starter files from your file downloads
   - [x] Push these changes to GitHub or GitLab.

## Instructions
The starter files consist of the following files: Accounts.py, savings_account.py, cd_account.py, and customer_banking.py. The Accounts.py file contains the Account class with methods to set the balance and interest.

In the cd_account.py file, you will import the Account class and create a create_cd_account function that will create a CD account instance, calculate the interest earned based on user input, update the account balance with the earned interest, and return the updated balance and interest earned.

In the customer_banking.py file, you will import the create_savings_account and create_cd_account functions, then create a main function that prompts the user to enter the savings and CD account details, call the corresponding functions to calculate the interest earned and update the balances, and display the results.

## Create the Savings Account Function
Open the savings_account.py file, and do the following:

1. Imports the Account class from the Accounts.py file.

2. In the create_savings_account function do the following:

    - Create an instance of the Account class and pass in the balance and interest parameters.

    - Calculate interest earned.

> [!TIP] 
> **_Interest on the balance is calculated as follows: interest = balance * (apr/100 * months/12)._**

    - Update the savings account balance by adding the interest earned.

    - Pass the updated balance to the set balance method using the instance of the Account class.

    - Pass the interest earned to the set interest method using the instance of the Account class.

    - Return the updated balance and interest earned.

## Create the CD Account Function
Open the cd_account.py file, and do the following:

1. Import the Account class from the Accounts.py file.

2. In the create_cd_account function, do the following:

    - Create an instance of the Account class and pass in the parameters.

    - Calculate interest earned.

    - Update the savings account balance by adding the interest earned.

    - Pass the updated balance to the set balance method using the instance of the Account class.

    - Pass the interest earned to the set interest method using the instance of the Account class.

    - Return the updated balance and interest earned.

## Create the Main Function
Open the customer_banking.py file, and do the following:

1. Import the create_cd_account and create_savings_account functions from the appropriate files.

2. In the main function, do the following:

    - Prompt the user to set the savings balance, interest rate, and months for the savings account.
    
    - Call the create_savings_account function and pass in the variables from the user.

    - Print out the interest earned and updated savings account balance with interest earned for the given months.

    - Prompt the user to set the CD balance, interest rate, and months for the CD account.
   
   - Call the create_cd_account function and pass the variables to the function used to prompt the user from the user.

    - Print out the interest earned and updated CD account balance with interest earned for the given months.

    - Call the main function.

> [!TIP]
> **Make sure that the values are the _appropriate_ data types.**

## Badges

## Visuals

## Installation

## Usage
This assigment highlights the usage of Python class and methods for generating customer banking information and calculating interest.

## Support
Some of the code on this assigment was done with the help of a bootcamp tutor.

## Roadmap

## Contributing

## Authors and acknowledgment
1. Code generated with the assistance of Saad (@Bootcamp Tutor)
2. This site was built using [GitHub Pages](https://pages.github.com/).

## License


## Project status
- Submitted for grading (04.04.2024)

## Footnotes

