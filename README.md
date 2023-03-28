# Airline-Database-using-sql
This SQL code creates a basic airline database, which consists of four tables: airports, flights, passengers, and bookings.

The airports table stores information about each airport, such as its name, location, and code. The flights table stores information about each flight, such as its number, departure and arrival airports, and prices for different classes of service. The passengers table stores information about each passenger, such as their name and contact details. The bookings table links the information from the other tables and stores information about each booking, such as the flight number, passenger details, and the price paid.

The code also sets up relationships between the tables, ensuring that the data is consistent and valid. For example, the flights table references the airports table, so that only valid airport codes can be used for each flight. Similarly, the bookings table references the flights and passengers tables to ensure that only valid flight numbers and passenger IDs are used for each booking.

Overall, this database allows an airline to keep track of its flights, airports, passengers, and bookings in an organized and efficient way.
