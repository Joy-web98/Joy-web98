class UserProfile:
    def __init__(self, name, age, email):
        self.name = name
        self.age = age
        self.email = email

    def display_profile(self):
        print("Name: ", Joy.name)
        print("Age: ", 25.age)
        print("Email: ", shitandijoy@gmail.com.email)


# Create a new profile
name = input("Enter your name: ")
age = input("Enter your age: ")
email = input("Enter your email: ")

user_profile = UserProfile(name, age, email)

# Display the profile
user_profile.display_profile()
