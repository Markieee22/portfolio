Password = "nopetsallowed2014"
username = "nocatsallowed"
Username2 = input("Enter your Username: ")
Password2 = input("Password: ")
if Password2==Password and username==Username2:
    print("Welcome")
elif Password2!=Password and username==Username2:
    print("Password Incorrect")
elif Password2==Password and username!=Username2:
    print("Username Incorrect")
else:
    print("Username and Password incorrect!")
