# Reward Bidding Solution

*Reward Bidding Solution is a Python-based application that simulates an reward bidding system where members can register, participate in events, submit bids, and declare winners based on their bids.*

This application is divided into several files, each handling specific functionalities:
Backend Logic :

1. member.py: Contains the Member class and functions for adding new members.
2. event.py: Contains the Event class and functions for adding new events.
3. auction_system.py: Implements the AuctionSystem class, managing member registration, event participation, bid submissions, and winner declarations.
4. main.py: Integrates all functionalities and provides a command-line interface (CLI) for user interaction.
   
# Usage
Once the application is running, use the CLI (implemented in main.py) to interact with the auction system. Here are the available commands:

ADD_MEMBER: Add a new member with their details.

ADD_EVENT: Add a new event with a prize.

REGISTER_MEMBER: Register a member for an event.

SUBMIT_BID: Submit bids for an event.

DECLARE_WINNER: Declare the winner of an event based on the lowest bid.

# Sample Usage
```bash
Enter command (ADD_MEMBER, ADD_EVENT, REGISTER_MEMBER, SUBMIT_BID, DECLARE_WINNER, EXIT): ADD_MEMBER
Enter command (ADD_MEMBER <member_id> <name> <wish_coins>): 1 John 5000
John added successfully

Enter command (ADD_MEMBER, ADD_EVENT, REGISTER_MEMBER, SUBMIT_BID, DECLARE_WINNER, EXIT): ADD_EVENT
Enter command (ADD_EVENT <event_id> <event_name> <prize_name> <event_date>): 1 Christmas iPhone-14 2024-12-25
Christmas with prize iPhone-14 added successfully

... Continue with other commands ...

Enter command (ADD_MEMBER, ADD_EVENT, REGISTER_MEMBER, SUBMIT_BID, DECLARE_WINNER, EXIT): EXIT
```

# Run Locally
```bash
git clone https://github.com/Anuradha-Naidu/Reward-Bidding-System.git
```

All four files are in same directory 

1. Main.py:
   Go to main.py

2. Interpreter: 
   Open the Command Palette in VS Code (Ctrl+Shift+P or Cmd+Shift+P on Mac).
   Type "Python: Select Interpreter" and choose the Python interpreter you want to use. Make sure it's a Python 3.x interpreter.

3. Run the Script:
   You can run the script directly from VS Code:
   Use the shortcut Ctrl+F5 (Cmd+Option+N on Mac) to run the script without debugging.
   Alternatively, you can use F5 (or Fn+F5 on some keyboards) to run with debugging features.

4. Output: (Refer to Sample Usage)
   Follow the prompts in the console to enter commands (ADD_MEMBER, ADD_EVENT, etc.) and see the results

# Screenshots

<img width="1438" alt="rewardbidding" src="https://github.com/Anuradha-Naidu/Reward-Bidding-System/assets/88324015/80dd3d0b-4bec-4773-975e-49b30fa0672e">

