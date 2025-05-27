[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Y49tTL6w)

Include a video/screenshots in readme

*Who is the program for?*

The program is for children mainly, but people of all ages can use it to have fun. 

*What the program does, what does it automate?*

The program allows the user to play Mad Libs games by entering the words in and having the program generate a story based on the prompt they picked. This program automates the process of Mad Libs which is usually a game playing on paper. 


*Using A List*

```


```

*Using A Loop*

```

```

*Using a Function*

```

```

*Code Progress (Day 1)*

```
trys = 5

def endProgram(trys):
    options = ["A Day At The Beach", "The Worst Summer Camp Ever", "Summer Roadtrip Gone Wrong", "How To Survive A Heatwave", "My Crazy Summer Job"]

    dir(options)

    print("Welcome to the Mad Libs Games")
    print("All options are summer themed and you have 5 trys to play")
    print("Enter in the correct words to fit the prompts, just know that if you mess it up you are only messing up the fun for yourself")
    print("Here are the options you can choose from", options)
    def madLibs():
        while True:
            madLibType = input("Choose an Mad Lib topic to begin ")
            if madLibType in options:
                if madLibType == "A Day At The Beach":
                    print("1")
                    break
                
                elif madLibType == "The Worst Summer Camp Ever":
                    print("2")
                    break
                
                elif madLibType == "Summer Roadtrip Gone Wrong":
                    print("3")
                    break
                
                elif madLibType == "How To Survive A Heatwave":
                    print("4")
                    break
                
                elif madLibType == "My Crazy Summer Job":
                    print("5")
                    break

            else:
                print("That is not an option try again")             
    madLibs()

    program = input("Are you done playing Mad Libs, type yes to stop anything else will make you play again ")

    if program == "yes":
        print("Thank you for playing!")
        return
    else:
        while trys > 0:
            trys = trys - 1
            if trys == 0:
                print("Your trys are done thanks for playing!")
                return
            else:
                print("Okay time for more fun! You have", trys, "trys left")
                return endProgram(trys)

endProgram(trys)
```

*Final Code (Day 2)*

```

```
