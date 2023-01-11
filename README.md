print("Enter Marks Obtained in : ");

markOne = int(input())

if markOne <= 100: 

    if markOne>=81 and markOne<=100:

        print("Your Grade is A+")

    elif markOne>=71 and markOne<81:

        print("Your Grade is A")

    elif markOne>=61 and markOne<71:

        print("Your Grade is A-")

    elif markOne>=51 and markOne<61:

        print("Your Grade is B")

    elif markOne>=41 and markOne<51:

        print("Your Grade is C")

    elif markOne>=33 and markOne<41:

        print("Your Grade is D")

    else:

        print("Your Grade is F")

else:

    print("Invalid Input!")
