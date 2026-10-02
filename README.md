## Movie Theater Ticket Kiosk

This repository contains the guided tools practice for the Movie Theater Self-Service Ticket Kiosk system. 
The toy system allows customers to view available movies and showtimes, select their preferred seats, and securely purchase tickets. 
It is designed to process payments, provide a final confirmation, and ensure that the same seat cannot be sold twice.

## Expanded Use Case: Purchase Ticket

* **Primary Actor:** Customer
* **Precondition:** The customer has selected an available movie, showtime, and seat.
* **Main Steps:**
  1. The customer selects the checkout option on the kiosk interface.
  2. The system prompts the customer for payment information.
  3. The customer inserts or taps their payment card.
  4. The Payment Service processes and authorizes the transaction.
  5. The Ticket Service permanently marks the seat as sold.
  6. The system generates a unique ticket confirmation number.
  7. The kiosk displays the confirmation message and dispenses the physical ticket.
* **Postcondition:** The ticket is paid for, printed, and the seat is permanently reserved in the system.
