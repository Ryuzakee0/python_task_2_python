# python_task_2_python
# Calculator

while True:
    print()
    print("1. Start Calculator Application ..!")
    print("2. Close Application ..!")
    option = int(input("Enter Choice :"))
    match (option):
        case 1:
            print('-----------------------------')
            print("***** CALCULATOR ******")
            print('-----------------------------')
            num1 = float(input("Ente 1st Number :"))
            num2 = float(input("Ente 2nd Number :"))
            oprt = input("Enter Operator :")
            print('-----------------------------')

            if oprt == '+':
                sum = num1 + num2
                print("Addition of {} and {} is : {}".format(num1,num2,sum))
            elif oprt == '-':
                sub = num1 - num2
                print("Subtraction of {} and {} is : {}".format(num1,num2,sub))
            elif oprt == '*':
                mul = num1 * num2
                print("Multiplication of {} and {} is : {}".format(num1,num2,mul))
            elif oprt == '/':
                div = num1 / num2
                print("Division of {} and {} is : {}".format(num1,num2,div))
            else:
                print("Invalid choice ..!")
            print('-----------------------------')
        case 2:
            break
        case _:
            print("Invalid Choice ..!")
