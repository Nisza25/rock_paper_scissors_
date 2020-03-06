# Rock_Paper_Scissors coding with simple logic of if-elif-else loop with customized player names

x = str(input('Enter your name: '))
y = str(input('Enter your friends name: '))
print("Hi there", x, "and", y,"!! Are you ready to play Rochambeau??")
c = ['rock', 'paper', 'scissors']

def rock_paper_scissor():

    user_input = input('[yes/no]: ').lower()
    if user_input == 'yes':
        a = input('So ' + x + "'s call is: ").lower()
        b = input("And " + y + "'s call is: ").lower()
        if (a == c[0] and b == c[2]) or (a == c[1] and b == c[0]) or (a == c[2] and b == c[1]):
            print('Well done', x, '! You beat', y,'this time.')
            print('Would you like to play again?')
            return rock_paper_scissor()
        elif (b == c[0] and a == c[2]) or (b == c[1] and a == c[0]) or (b == c[2] and a == c[1]):
            print('Well done', y, '! You beat', x,'this time.')
            print('Would you like to play again?')
            return rock_paper_scissor()
        elif a == b:
            print("Looks like", x, "and", y, "couldn't beat each other. It's a draw!")
            print('Would you like to play again?')
            return rock_paper_scissor()
        else:
            print("Oops! Careful with your spelling. How about we play again? ")

    if user_input == 'no':
        print("Awe! No Problem. I understand. But before you go, here's a fun fact: ")
        print("Did you know that Rock_Paper_Scissors has another name called Roshambo?")

    else:
        print("Please type 'yes' or 'no' carefully.")
        return rock_paper_scissor()


rock_paper_scissor()


