# Team-Project

def display_menu():
    print("Please choose an option from the list below:")
    print("1. Learn Python")
    print("2. Learn Java")
    print("3. Go swimming")
    print("4. Have dinner")
    print("5. Go to bed")
    print("0. Exit")

def main():
    while True:
        display_menu()
        try:
            choice = int(input("Enter your choice: "))
            if choice == 1:
                print("You chose to learn Python!")
            elif choice == 2:
                print("You chose to learn Java!")
            elif choice == 3:
                print("You chose to go swimming!")
            elif choice == 4:
                print("You chose to have dinner!")
            elif choice == 5:
                print("You chose to go to bed!")
            elif choice == 0:
                print("Exiting the program.")
                break
            else:
                print("Invalid choice. Please choose a number between 0 and 5.")
        except ValueError:
            print("Invalid input. Please enter a number.")

if __name__ == "__main__":
    main()
