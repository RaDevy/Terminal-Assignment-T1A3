### Github

https://github.com/RaDevy/Terminal-Assignment-T1A3

### Trello

https://trello.com/b/xxFlbYij/terminal-application

### Purpose

Our overall health is dependant on various factors, one of the main factors is sleep.This factor is normally overlooked as our screen time increases with each day.Addiction or Habit.This application will help the user get some answers and hopefully HELP.
This APPlication will therefore assist people to get a better perspective on the various factors that affect their sleep.It will ask the users questions regarding their sleep and caffeine habits. From each of users inputs (actual habits) the APPlication will calculate and rate the users sleep hygiene.Once a score is calculated it will output the score on screen.The score reflects whether
the user has either good or bad sleep hygiene. This is a simple indicator, however if  the score is bad (negative value) it will output "Please see a Health  Professional" and if the score is good (positive value) it will output "you have good sleep hygiene". This is a simple,useful and effective APPlication.



- Identify the problem it will solve and explain why you are developing it
The Application will highlight the users sleep habits , and make them take some action.Having adequate sleep is critical in our lives ,having some feedback about our sleep habits is important, this Application will assist the user to reslove that.

- Identify the target audience
Mainly directed towards gamers,video and media artists, ages 14-35yrs.Office workers now working from home could also be a potential target audience.It will also have a larger audience once it is circulated. (anyone with poor sleeping patterns).

- explain how a member of the target audience will use it
The user will will complete an application questionaire that will aid them in assessing their sleeping patterns. The questionnaire has a series of relevant questions that relate to sleep heath.Once the inputs are made it returns a score that predicts their sleep hygiene.


### Features

Keywords
Methods
Variables

#### describe each feature:

Keywords is used in this application to represent the defined actions.This makes it easier for the application to be built.

The method feature will be used - consisting of the  keyword, a method name, which will return value and the end keyword. 

A variable is a name that Ruby associates with a particular object. For example: caffeine drinks: Ruby associates the string "coffee" with the name (variable) caffine drinks.


### Menu
The menu has a WELCOME message , This will open the terminal application.The application has four features that are inter-related, they are recorded analysed by the program and contribute to the users sleep hygiene score.

### Caffeine Intake
The caffeine intake is on a slide bar , the user can choose the number of caffeine drinks they have in a day.
There is also a range of other drinks that users could choose.These are displayed as options on an unordered list.
The time that the drinks are taken can also have an impact on the user sleep,eg.caffeine at night is much worse at night than during the day.

### BMI
The BMI calculator has a formula that calculates your body mass index.This is your weight divided by the users height in meters squared.
The BMI calc. is useful as a high BMI could negatively affect your sleep habits.


### Screentime
The user has a range choice displayed prompt slider of the number of hours they  spend on screen per 24hour day.
There is also an option for the user - displayed in an unordered list to choose from - the types of activities they engage in while on screen,e.g gaming,working etc.
There is a further option of the different times of the day these activities are carried out.
All the above information is collated and a score is given based on good habits vs bad habits.
An output is given to the user once all inputs are received.
The number of hours a person spends on a screen (laptops,phones,tablets,t.v) has a fundamental outcome on a person sleep patterns and their health.Screens give an artificial enviroment that the user can engage in at all hours of the day and night, this constant stimulation can keep the user away from sleeping and resting and / or take more caffinated drinks to stay awake.


### StressRelated questions
Stress levels also have an impact on sleep patterns.
The user can input the level of stress they feel. This is a choice on a prompt.slider.

### Develop an outline of the user interaction and experience for the application.

Your outline must include:
 #### how the user will find out how to interact with / use each feature
    - TTY prompt lets the user know what they need to do to interact with the input.
    - My application 
 #### how the user will interact with / use each feature
    - This is a linear questinaire that takes the step by step
    - Each question prompts the user with instructions
 #### how errors will be handled by the application and displayed to the user	
    - If the user inputs the incorrect datatype the terminal prompts to not do that and enter the correcr data type
    - This will be done with the BEGIN - RESCUE - error handling method

### Control flow

![Control Flow Diagram](docs/ControlFLowDiagram.png)

- show the workflow/logic and/or integration of the features in your application for each feature.
- utilise a recognised format or set of conventions for a control flow diagram, such as UML.	

#### Main app - 8days
    - Menu
    - Caffeine Questionaire
    - BMI 
    - Psychology
    - Screen Time
    - Final Advice
    - Polish/Bug fixing

#### Caffeine Questionaire (3hrs)
    - Initialize Questionaire class
    - Plan out the questions that I need to ask the user
    - Figure what what TTY-Prompt is most suitable for that type of question
    - Write up the question flow 
    - Impliment it into the menu


R10	Design help documentation which includes a set of instructions which accurately describe how to use and install the application.

You must include:
- steps to install the application
- any dependencies required by the application to operate
- any system/hardware requirements

#### A walk-through of your Terminal application, its features and how it used
(I used the slider because it is convenient for the user to move to the correct level, by simply sliding on the correct value)


#### A walk-through of the logic of your Terminal application and code
The terminal application has a "Welcome" Heading , this is to make them want to go forward with the app.I also added sound - again to connect with the user.

There are four sections are broken up into various sections to make the user engage and give more information reagrding their habits.

The questions are simple which allows easier participation in the questionnaire.

#### A review of your development/build process including challenges, ethical issues, favourite parts, etc

It was a very rewarding process to build the terminal application.
I enjoyed coming up with the different ideas.

The difficult part was implementing the ideas , and making it work.
I therefore kept my coding simple , as ruby is still new to me. 
I underestimated the time it took me to complete the project.

Creating an application that has health parameters is challening as I did not want the app to give health advice but rather point the user in the correct direction regarding their sleep habits.

My favorite part was adding the sound , and feeling the interaction with the terminal app.I hope it will help the user.


