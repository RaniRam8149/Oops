Q1. Explain Class and Object with respect to Object-Oriented Programming. Give a suitable example.

In object-oriented programming (OOP), a class is a blueprint or template for creating objects. It defines the properties (attributes) and behaviors (methods) that objects of that class will have. An object, on the other hand, is an instance of a class. It's a concrete realization of the class, possessing its own set of attribute values and able to perform actions through its methods.
class Car:
    def __init__(self, make, model, year):
        self.make = make
        self.model = model
        self.year = year
        self.speed = 0

    def accelerate(self, increment):
        self.speed += increment

    def brake(self, decrement):
        if self.speed - decrement >= 0:
            self.speed -= decrement
        else:
            self.speed = 0

    def get_speed(self):
        return self.speed

car1 = Car("Toyota", "Corolla", 2022)
car2 = Car("Tesla", "Model S", 2023)

car1.accelerate(20)
car2.accelerate(15)

print(f"{car1.make} {car1.model}'s speed: {car1.get_speed()} mph")
print(f"{car2.make} {car2.model}'s speed: {car2.get_speed()} mph")

car1.brake(10)
car2.brake(5)

print(f"{car1.make} {car1.model}'s speed after braking: {car1.get_speed()} mph")
print(f"{car2.make} {car2.model}'s speed after braking: {car2.get_speed()} mph")
