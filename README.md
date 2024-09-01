# Function for Vaild or In-Valid

def addressVal(address):

    if address.find('@') != -1 and address.find('.') != -1:
        print("Valid")
    else:
        print("Invalid")

def main():

    while True:
        email = input("Input: ")
        
        addressVal(email)
        break

if __name__ == "__main__":
    main()
