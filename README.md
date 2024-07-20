Key Operations:
Generate a new keypair and create an account on the ledger:

Generates a new keypair (public and secret keys).
Uses the Friendbot service to fund the new account.
Setup Trustline:

Prompts user to enter asset code and issuer public key.
Creates a trustline for the specified asset.
Issue Asset:

Prompts user to enter asset code, issuer public key, and the amount to issue.
Issues the specified asset to the account.
Make Payment:

Prompts user to enter the amount to pay.
Makes a payment of the specified amount.
Manage Buy Offer:

Prompts user to enter details about the buy offer (selling asset, buying asset, amount, price, and offer ID).
Manages the buy offer on the blockchain.
Manage Sell Offer:

Prompts user to enter details about the sell offer (selling asset, buying asset, amount, price, and offer ID).
Manages the sell offer on the blockchain.
Stream Payments:

Streams incoming payments to the account in real-time.
Handle Preconditions:

Prompts user to enter preconditions for a transaction (minTime, maxTime, and amount).
Submits a transaction with the specified preconditions.
Pathfinding:

Prompts user to enter the amount to find a path for.
Finds a payment path for the specified amount.
Payment Channel:

Prompts user to enter details for creating a payment channel (receiver public key, starting balances, and amount to send).
Manages the payment channel transactions.
Usage:
When the script is executed, it generates a new keypair and funds the account using Friendbot.
The user is then prompted to choose from a list of operations to perform.
Depending on the user's choice, appropriate functions are called to execute the blockchain operations.
Error Handling:
The script includes try-catch blocks to handle any errors that may occur during the execution of blockchain operations and displays the error message.
Note:
Ensure that you have the diamante-sdk-js and node-fetch packages installed.
The script assumes the existence of a Diamante testnet and Friendbot service for account funding.
