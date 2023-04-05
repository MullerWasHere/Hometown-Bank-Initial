# Hometown Bank Kata

### Part 1

#### Background
Imagine you are working as a software developer for a small local bank called "Hometown Bank." The bank wants to create a simple banking system to manage their customers' accounts and provide essential features like deposit, withdrawal, and balance checking.

Your team leader has asked you to start developing a basic bank account system following Test-Driven Development (TDD) principles. The bank wants the system to be reliable and ensure that it handles customers' money accurately.

#### Requirements
1. Create a new bank account with an initial balance.
2. Deposit money into the bank account.
3. Withdraw money from the bank account.
4. Check the balance of the bank account.
5. Transfer money between two bank accounts.

### Part 2

#### Background
After successfully implementing the basic bank account system, "Hometown Bank" has seen a significant increase in the number of customers. To provide better services and attract more customers, the bank has decided to introduce different account types with various features like overdraft protection and monthly maintenance fees.

Overdraft protection is a service offered by banks that allows account holders to withdraw more money than they have in their account, up to a certain limit, without incurring hefty fees or penalties. This feature is often available for certain account types and offers a safety net for customers during financial emergencies.

As a software developer, your team leader has assigned you to extend the existing bank account system to support these new features. The bank wants you to ensure that the new functionalities work seamlessly with the existing system, and any changes are thoroughly tested using TDD.

#### Requirements
1. Update the bank account creation process to include an account type (Basic, Premium, Business).
2. Modify the withdrawal process to consider account type and overdraft protection.
   - Basic accounts: No overdraft protection.
   - Premium accounts: Overdraft protection up to $500.
   - Business accounts: Overdraft protection up to $2,000.
3. Implement a monthly maintenance fee for certain account types.
   - Basic accounts: $10 monthly maintenance fee.
   - Premium accounts: $5 monthly maintenance fee.
   - Business accounts: No monthly maintenance fee.
