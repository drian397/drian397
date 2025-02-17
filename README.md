class Car:
    def __init__(self, brand, model, year):
        self.brand = brand
        self.model = model
        self.year = year

    def display_info(self):
        print(f"Brand: {self.brand}, Model: {self.model}, Year: {self.year}")

# Create two car objects
car1 = Car("BMW", "BMW X1", 2014)
car2 = Car("MITSUBISHI", "Lancer Evolution", 2024)

# Display their details
car1.display_info()
car2.display_info()
