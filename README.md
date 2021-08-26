# Quiz App
This was my group project for Semester 2 during my Higher Diploma course. 

Over ten weeks, myself and four others worked remotely using SCRUM to make an online React app that had persistent data in the form of a database of users and their created quizzes. Other users could then be invited to play these quizzes using passwords, and results would be displayed as a leaderboard at the end of the quiz.
We used firebase to deal with the user data, and tailwind and bootstrap for styling. We used an API to get our quiz questions.
Each of us took responsibilty for different aspects of the project, and my contribution was the quiz creation and the quiz display.

The quiz creation allows for selecting the size of the quiz, the amount of time for each question and the number of rounds. The rounds can be picked randomly from all categories, or just one specific one. The random questions can be multiple choice, true or false, or both. There is also an image round, that accepts point clicked on a map as an answer. Custom rounds can also be created, with the user supplying the question, and the correct and incorrect answers. A password can be chosen for the quiz to allow other people to play it.

The quiz display is what is shown during play time. One question at a time appears, and when the timer reaches zero the quiz opens the next question. All the player has to do is click on the answer they think is right, and that answer is saved and checked when the timer reaches zero. When the quiz reaches the end of a round, the player starts the timer again by clicking to proceed to the next round. The decision to let the game playout like this was to minimise the chance of cheating, should this app be used like a pub quiz. When all rounds are over, the player can review their score and it is added to that quiz's leaderboard.

I worked mainly on the front end, working with the API to get the correct data request and displayed properly, while working with the user interface to make sure everything was clear, simple and easy to use.
