# Car-Rental-System
A simple "Car Rental System" in Java, which allows customers to rent and return cars.
**Rent a Car: Experience the ease of renting cars through an interactive console. **Return a Car: Effortlessly return previously rented cars and update availability. **Customer Management: Add new customers and maintain customer records. **Car Management: Manage cars, brands, models, and pricing details. **Rental History: Keep track of rentals, customers, and rental durations.
About Project:
class includes Car, Customer, Rentals, CarRentalSystem which includes different methods for specific work.
class Car includes methods - carId, brand, model, basePricePerDay.
class Customer includes methods - getCarId(), getBrand(), getModel(), calculatePrice(), isAvailable(), rent(), returnCar(), isAvailable().
class Rentals includes methods - getCustomerId(), getName(), getCar(), getCustomer(), getDays().
class CarRentalSystem includes methods - addCar(), addCustomer(), rentCar(), returnCar(), menu().
Rent a Car:
Enter the customer's name, choose an available car by its ID, and specify the number of rental days.
The system then displays rental details (including the total price) and asks for confirmation.
If confirmed, the car is rented out and marked as unavailable.
Return a Car:
The user enters the car ID to return the car.
The system checks if the car is currently rented and then processes the return.
Exit the System:
Exits the menu loop and ends the program.
A basic implementation of a car rental management system where cars can be rented and returned by customers. The system maintains a list of available cars, ongoing rentals, and customer information. The functionality is provided through a simple text-based menu, which allows the user to interact with the system and perform rental-related operations.
