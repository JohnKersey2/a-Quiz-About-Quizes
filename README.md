# Create a Quiz

For this assignment, I was to create a quiz with a few sporadic features added in. 

## Link to Deployed Application 

<https://johnkersey2.github.io/a-Quiz-About-Quizes/>

## Application Screenshot 

![Screenshot of the Application](./assets/applicationscreenshot.png)

## Criteria

According to the user story, I was to create a quiz with the following acceptance criteria. 

The quiz starts when user clicks a start button

A timer starts and the user is presented with a question

When one question is answered, another appears

When a question is answered incorrectly, the timer is decremented 15 seconds

The quiz had to stop asking questions when the clock reached 0 or the user completed all questions

After the quiz was over, the user could save their initials and score. 

## Known Issues 
Input for initials will only be entered if user hits save button, not if they hit the enter key. Only solution found is deprecated.  

##  Current Development Notes

Too much is hard-coded. Current plan is to rewrite to a single function pulling from an array, but mvp is completed for now. 

Change initial input to only take alphabet characters

## Future Development Notes
Potential features to add:

Change functionality of scoreboard to only show highest score, or if possible, 3 highest scores

Add final question that asks how many times you clicked the A answer?

Add time taken to complete to scoreboard

Add buttons for different quizzes.

Add endless mode. 