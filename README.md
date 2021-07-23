# e-wallet
A wallet microservice running on the JVM that manages credit/debit transactions. 

A Rest API to access monetary accounts with the current balance of a user. The balance can be modified by registering transactions on the account, either debit transactions (removing funds) or credit transactions (adding funds).

A debit transaction will only succeed if there are sufficient funds on the account (balance - debit amount >= 0).
Unique global transaction id must be provided when registering a transaction on an account.

It is also possible to fetch the users accounts and get current balance.

