Python_Classes
==============

Help with classes
#the next 4 lines sets static variables
cars = 100
space_in_a_car = 4.0
drivers = 30
passengers = 90
#the next 4 lines sets variables using the static variables as input
cars_not_driven = cars - drivers
cars_driven = drivers
carpool_capacity = cars_driven * space_in_a_car
average_passangers_per_car = passengers / cars_driven

#These lines print the variables in sentences
print "There are", cars, "cars available."
print "There are only", drivers, "drivers available."
print "There will be", cars_not_driven, "empty cars today."
print "We can transport", carpool_capacity, "people today."
print "We have", passengers, "to carpool today."
print "We need to put about", average_passangers_per_car, "in each car"
