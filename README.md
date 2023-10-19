Certainly! Here's a README.md for your Vending Machines CLI project:

---

# Vending Machines CLI

## Objective

The primary objective of the Vending Machines CLI is to provide a command-line interface for users to interact with virtual vending machines. Users can purchase items, view inventory, and receive change. The program connects to a PostgreSQL database to store and retrieve vending machine data, ensuring persistence across sessions. Additionally, all significant user actions and transactions are logged into a local log file for audit and traceability purposes.

## Features

- **User-Friendly CLI:** Interactive prompts guide the user through the various functionalities.
- **Persistent Storage:** Connection to a PostgreSQL database ensures that the data remains intact across different user sessions.
- **Audit Logging:** Any transaction (purchase, add funds, etc.) is logged for future reference.

## Requirements

### Functional Requirements:

1. **Display Inventory**: List available items, their prices, and quantities.
2. **Purchase Item**: Allow users to select an item for purchase.
3. **Add Funds**: Users should be able to deposit money into the machine.
4. **Give Change**: Upon completing a purchase, the machine should return the appropriate change.
5. **Write to Log File**: Every transaction (including errors) should be written to a log file with a timestamp.
6. **Database Operations**:
    - **Connect**: Securely connect to a PostgreSQL database.
    - **Fetch Data**: Retrieve the latest vending machine inventory from the database.
    - **Update Data**: Reflect any changes (e.g., after a purchase) in the database.

### Non-functional Requirements:

1. **Performance**: The application should respond to user inputs promptly without noticeable delays.
2. **Security**: Database credentials should be secured, and SQL injections should be prevented.
3. **Usability**: The CLI should be intuitive, with clear prompts and error messages.
4. **Reliability**: The application should handle errors gracefully without crashing.


