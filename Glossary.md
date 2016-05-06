# Musement Glossary

* **Customer**: the customer is the one that makes the purchase. He can be one of the passengers or not. In any cart there must be one and only one customer.

* **Open ticket**: Musement events can have a specific date, e.g. a football match, or can be valid for a limited time span, e.g. an entrance ticket valid for the next 365 days. In the first case the property open_ticket would be "no", in the second case would be "yes". The dates API for open tickets will always return the last day of availability no matter the range of days you passed. This property is printed at the end of each "Single date" API request

* **Passenger**: the passenger is the one who will benefit the ticket. In any cart there can be many passengers or any. Not every product requires info about passengers


* **Seat price**: this is the single product that can be added to the cart. The seat price identifies a specific time slot, with a specific ticket holder for a specific event.