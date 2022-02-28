# AgeCalculator
AgeCalculator is a Python program that asks for the user's name and date of birth in the following format: mm/dd/yyyy and outputs how old they were at the moment of the program's execution.

### Running
To run the program, open name.ipynb in JupyterLab and run the code block. Input your name and date of birth (in the mm/dd/yyyy format) when prompted and press enter. 

Example use:

```
Please enter your name: John Doe
Enter your birthday in the following format 'mm/dd/yyyy': 10/31/1961
John Doe you are 60 years, 4 months, 12 days, 11 hours, 40 minutes, 53 seconds old.
```

To use the method 'calculateAge(year, month, day)' directly, input the year, month, and day as integers and it will return the total seconds elapsed
since 12:00am on that date.
Sample use: 
```python
year = 1961
month = 10
day = 31
elapsed_seconds = calculateAge(year, month, day)
```

To use the method `printInfo(seconds, name)` directly, input an integer number of seconds and the name of the person and it will print out the person's name and the seconds converted to years, months, and days in a formatted output. 
Sample use: 
```python
name = "John Doe"
elapsed_seconds = calculateAge(year, month, day)
printInfo(elapsed_seconds, name)
```

## How to Contribute
Before contributing please review our Code of Conduct.
1. Fork the main repository
2. Make changes
3. Create a pull request to main with a detailed description of the changes as well as the reasoning behind them.
4. Wait for the pull request to be accepted or for feedback from someone on our team.

Thank you for considering to contribute to AgeCaluculator, we appreciate all of our contributers!





## Code of Conduct
Please read CODE_OF_CONDUCT.md for more information about community guidelines.

## Our Team
### Katelyn Kunzmann
### Michael Mascilli
### Taha Ahmad


## Reasoning Behind Our Code of Conduct and Choice of License 
This code of conduct was developed on the basic principles of respect and courtesy and to create an enviroment where eveyone, regardless of race, age, orientation, gender, etc. feels welcomed and feel comfortable contributing. We also wanted to discourage any person who wants to create an unwelcoming and bigoted atmosphere which makes it difficult for people to collaborate and contribute to this project. 

We chose the MIT license because it seemed simpler compared to the others which suits a small project like this and because it gives pretty much full leeway for anyone to use our source code for their own projects. 