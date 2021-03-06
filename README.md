# Bank Account Kata
This is an implementation of the bank account kata in Scala.

## Problem Description

Think of your personal bank account experience When in doubt, go for the simplest solution

### Requirements

* Deposit and Withdrawal
* Account statement (date, amount, balance)
* Statement printing

### User Stories

#### US 1
**In order to** save money  
**As a** bank client  
**I want to** make a deposit in my account

#### US 2
**In order to** retrieve some or all of my savings  
**As a** bank client  
**I want to** make a withdrawal from my account

#### US 3
**In order to** check my operations  
**As a** bank client  
**I want to** see the history (operation, date, amount, balance) of my operations

## Solution
The provided solution focused on the account key features and no user interface was implemented. 
The solution is only runnable through unit tests. 
The next step would be the implementation of a CLI to register user operations on his account.

## Usage
```shell script
sbt test
```