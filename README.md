# ParkingLot

Parking Lot Project
ParkedVehicle class takes 5 parameters :

vehicleSeq : takes an integer value, an unique identification number for each vehicle.
fourWheeler : takes a boolean value to determine if the parked car is a four wheeler or not.
parkedFor : takes an integer value, denotes number of hours the car is parked for.
valetParking : takes a boolean value, denotes whether the owner used Valet Parking or not.
parkedStatus : takes a boolean value, denotes if the car is parked or not.

ParkingLot class initialises a Python dictionary to store the list of ParkedVehicle objects. It has 5 methods as shown below:

add_to_parking_lot adds a new car to the parking lot by storing the ParkedVehicle object in the parked_vehicles dictionary.

parking_charge calculates the total cost of the parking for the entire duration a vehicle object has been parked. It followes the follwing rule while calculating the cost:
if a car is a Four Wheeler, then the rate is 50 INR
if a car is a Two Wheerler, then the rate is 30 INR.
if the owner used a valet to park his car, it adds 10 INR to the base price, otherwise the base price is the final price.

get_parking_catalog returns the dictionary which contains all the lot numbers of the parked cars.

change_parked_status changes the status of the vehicle object from True to False and vice versa. It takes the vehicle object as a parameter.

get_parked_status returns a boolean value denoting whether the vehicle is parked or not. It takes the vehicle object as a parameter.


Improvements in functionality is always welcome. 
