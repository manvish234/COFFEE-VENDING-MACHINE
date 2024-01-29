METHODOLOGY: 

•	Initially, vending machine is in the initial state, waiting for user interaction. When a user approaches the vending machine, it transitions to the welcome state
•	In the welcome state, the vending machine presents the available beverage options to the user, such as coffee, tea, milk, or hot chocolate.
•	The user can select one of the available beverage options.
•	After the user selects a beverage, the vending machine transitions to the payment state.
•	In the payment state, the vending machine provides payment options to the user, such as cash or UPI.
•	If the user selects the cash option, the vending machine transitions to the cash payment state, awaiting the user to insert the required amount of cash (5$).
•	If the user selects the card option, the vending machine transitions to the card payment state, prompting the user to give a 4-bit pin for the machine.
•	Once the payment is successfully processed, the vending machine transitions to the dispensing state.
•	In the dispensing state, the vending machine prepares and dispenses the selected beverage to the user.
•	After dispensing the beverage, the vending machine transitions to the transaction complete state and displays a transaction completion message.
•	If the selected beverage is out of stock, the vending machine transitions to the unavailable state and prompts the user to the select state again.
•	If the payment fails or is insufficient, the vending machine transitions to the payment failure state and prompts the user to idle.
•	Once the transition reaches complete state the process is successfully completed.
