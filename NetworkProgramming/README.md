# Bank account management using REST

A simple RESTful web service for managing bank accounts using java & SQL.
Developed with Netbeans and xampp, tested on local network.
Bank accounts info are stored in a single SQL table. No authentication needed to access it.

The program user is able to do the following:
- Get all acounts information in JSON or XML format.
- Get information for a specific account using its ID (in JSON or XML format).
- Create a new account.
- Activate or deactivate an existing account (upon creation, every account is being activated).
- Make transactions (deposit, withdrawal, transfer to another account). Only activated accounts can make transactions.
- Delete an existing account.