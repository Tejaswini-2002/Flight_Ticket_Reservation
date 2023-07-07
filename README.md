# Flight Booking System

This Python script implements a flight booking system that allows users to search for available flights, view flight details, and book tickets for different airlines. The script is written to handle flight data stored in separate CSV files for each airline.

# Data Files
The script reads flight information from the following CSV files:

- Indigo.csv: This file contains flight details for IndiGo airlines.
- Air India.csv: This file contains flight details for Air India airlines.
- SpiceJet.csv: This file contains flight details for SpiceJet airlines.

# Functionality
The script provides the following functionalities:

- Flight Search: Users can search for available flights by specifying the origin and destination cities. The script retrieves the matching flights from the corresponding CSV file based on the search criteria.

- Flight Details: Users can view the details of a specific flight by entering the airline and flight number. The script retrieves the flight details from the corresponding CSV file.

- Ticket Booking: Users can book tickets for a selected flight by providing passenger details such as name, passport number, contact number, age, and seat preference (business, economy, or first class). The script verifies seat availability based on the selected flight and seat type, allowing the user to choose an available seat.

- Seat Availability: The script checks the availability of seats based on the selected flight and seat type. It ensures that the requested number of seats can be accommodated by checking the remaining available seats for each flight and seat class.

- Ticket Price: The script calculates the ticket price based on the selected flight and seat type. It defines the costs for different seat classes (business, economy, or first class) for each airline and calculates the total price based on the number of seats booked.

- Seat Selection: After verifying seat availability, the script presents the user with a seat layout based on the selected seat class. The user can choose their preferred seat by entering the corresponding seat number.

- Ticket Generation: Once the ticket is successfully booked, the script generates a ticket with passenger details, flight information, gate number, and seat number. The ticket information is displayed on the console.

- Data Persistence: The script stores the booking details in separate CSV files (airindia.csv, indigo.csv, spice.csv) for each airline. These files save the passenger details, flight information, seat number, and ticket number for future reference.

