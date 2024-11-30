# Team-Project

def main():
    while True:
        # Display menu
        print("\nPlease choose from the list below:")
        print("1. Learn Python")
        print("2. Learn Java")
        print("3. Go Swimming")
        print("4. Have Dinner")
        print("5. Go to Bed")
        print("0. Exit")
        
        # Get user input
        try:
            choice = int(input("Enter your choice (0-5): "))
        except ValueError:
            print("Invalid input. Please enter a number between 0 and 5.")
            continue
        
        # Process the input
        if choice == 1:
            print("You chose to Learn Python. Great choice!")
        elif choice == 2:
            print("You chose to Learn Java. Happy coding!")
        elif choice == 3:
            print("You chose to Go Swimming. Enjoy the pool!")
        elif choice == 4:
            print("You chose to Have Dinner. Bon appétit!")
        elif choice == 5:
            print("You chose to Go to Bed. Sweet dreams!")
        elif choice == 0:
            print("Exiting the program. Goodbye!")
            break
        else:
            print("Invalid choice. Please enter a number between 0 and 5.")
