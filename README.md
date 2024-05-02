Simple Banking Application using Spring Boot, Spring Data JPA(Hibernate) and MySQl database

1. **Create a Bank Account:**
   - When a user wants to create a bank account, they provide details like account number and initial balance.
   - The application stores this information in the MySQL database.

2. **Get the Bank Account details by Account number:**
   - When a user wants to view their account details, they provide their account number.
   - The application retrieves the account details associated with that account number from the database.

3. **Get All the Bank Account details:**
   - When a user or admin wants to view all bank account details, the application fetches all accounts stored in the database.

4. **Withdraw the money from Account:**
   - When a user wants to withdraw money from their account, they provide the account number and the amount to withdraw.
   - The application checks if the account has sufficient balance and updates the balance accordingly in the database.

5. **Deposit the money in account:**
   - When a user wants to deposit money into their account, they provide the account number and the amount to deposit.
   - The application updates the account balance by adding the deposited amount to the existing balance in the database.

6. **Delete or Close the Account:**
   - When a user wants to close their account, they provide the account number.
   - The application deletes the account details from the database.
