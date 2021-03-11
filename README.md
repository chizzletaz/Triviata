# La Triviata
This is a trivia game. The user can choose between challenge mode and practice mode. In challenge mode the user plays three rounds with increasing difficulty, with questions from every category. In practice mode, the user can choose the category and difficulty level.

# UX
## **Strategic level**
The website is for people who want to play a fun or a challenging game and at the same time test their knowledge.
Another goal is to show the coding skills I learned solar (HTML, CSS and Javascript).

Game idea/explanation?

### **user stories**
**first time users:**  
- As a first time user, I want to navigate easily across the website.  
- As a first time user, I want to know what the game is about, so I can play the game with ease. 
- As a user, I want to play the game on different screen sizes.
- As a user I want to have some control over the game, so I can play the game in my own pace.
- As a user I want to get feedback on how I am doing, in particular if my answer is correct and how many points I have.
- As a user I want to save my score and see the high scores, so I challenge myself to play better.
- As a user I want to choose different game modes, so the game is more versatile.

NOTE: is it better to be as precise as possible on the user stories, or can you groups some stories into general user stories? For instance ‘user story e’ is more general and leaves room for more implementations/features. Should I split this up in different stories?

**developer stories:**
- As a developer I want to give feedback and control to the users before, during and after the game, so that the user keeps on playing.
- As a developer I want to challenge the user, so they will come back and play some more.
- As a developer I want my users to be able to play on all devices.

## **Scope level**
Considering that I don’t have enough experience and therefore insight into how much time it costs and how difficult implementing some features are, I’ve decided to plan for a *Minimal Viable Project* first and then add the extra features, depending on how much time was left.  
Minimal Viable Project, what requirements are needed?
1. Provide an explanation of the game.
2. Provide good navigation indications with use of buttons and icons.
3. Have a responsive design.
4. Provide a game 
5. An option to choose the next question
6. An option to change settings.
7. Provide information on score, correct/incorrect answer and which question the user is on.
8. An option to save the score.
9. Provide high scores.

**Extra requirements:**  
1. An option to show the right answer.
2. Provide different player modes: practice/fun mode: the user can choose the category and difficulty level.
3. Sound effect and background music and the option to turn them on/off.
4. Option to switch between dark and light mode.


## **Structure Level**  
The structure (and later on the wireframes) will already include the extra features. Whether or not they are implemented, will depend on the available time and the difficulty of implementation. 
During the design and development, I worked out the following ideas.

The overall look is kept the same for consistency:   
- The colours are kept the same on each page.
- The buttons are styled in a similar way.

The navigation is kept simple:   
- There are buttons to navigate the game, such as a button go to a next question, buttons navigate to other pages like the landing/home page or the high scores page. 

The user is given feedback, in order to enhance a pleasant user experience:  
- This translates to visual and audio feedback during certain actions (like focusing on, clicking on or hovering over buttons or links). Examples are: the displacement of the answer box, when hovering over it. Or change of colour when clicking a button or link.
- The answer box changes colour in case of a right or wrong answer. 
- A sound is played after giving a correct or wrong answer.

All the information should be easily visible:
- Visual aids are used, like icons and complementary colours.


The website will have 5 pages:  
A landing page, a practice selection page, a game page for practice mode, a game page for challenge mode and a high scores page.

Each page will have the same header, with options to change sound, music and light/dark mode.
Except for the landing page, all pages have a button to go back home to the landing page.

**The landing page** will have an option to see the explanation of the game. 
There will be a start button, which opens a link to choose a play mode. There is a link to go to the high scores page. The settings are displayed at the top of the page.

**The practice selection page** has the option for the user to choose the category and difficulty level of the game.

**The game page for challenge mode** will have a question and answer area. There will be an indicator of the score and which question the user is at. After round 1 and round 2 a modal will pop up to indicate that the user is going to another level. When all the three rounds are finished, a modal pops up. In the modal there will be an endscore, the option to save the user’s score, the option to play again and a link to the high scores page. 

**The game page for practice mode** will be the same as the challenge mode page, except that there is only 1 round.

**The high scores page** will have an overview of the top 5 players with names and scores.

## **Skeleton Level**
As mentioned above, the extra features will also be included in the wireframes. A comparison of the wireframes with the endproduct will show the implemented extra features. Also the implemented extra features will be updated in the ‘Features’ section below.

Link to [wireframes](https://github.com/chizzletaz/MSP2-TriviaQuiz/blob/master/assets/documents/Wireframes%20MSP2.pdf)

## **Service Level**
Design choices. Note why you use certain fonts, color and design choices.
**Colors**  


**Fonts**  




# **Features**
In this section, you should go over the different parts of your project, and describe each in a sentence or so.

**Existing Features**
Feature 1 - allows users X to achieve Y, by having them fill out Z
...
For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.
In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

**Features Left to Implement**
- A timer: the questions have to be answered in a certain time, e.g 10 seconds.
- The score is linked to how fast a user answers the question.

## **Technologies used**

**languages used**  
- [HTML5](https://en.wikipedia.org/wiki/HTML) for markup  
- [CSS](https://en.wikipedia.org/wiki/CSS) for styling
- [Javascript](https://en.wikipedia.org/wiki/JavaScript) for  interactivity

**Frameworks, libraries and programmes used**   
- [Bootstrap 4.5.3](https://getbootstrap.com/) was used for precoded code-snippets, like navigation bar, modals, carousel and to help with the responsiveness of the website.  
- [Balsamiq](https://balsamiq.com/) for making the wireframes.  	
- [Git](https://git-scm.com/) was used version control.  
- [GitHub](https://github.com/) for storing and deploying the website.  
- [GitPod](https://www.gitpod.io/) for coding (IDE) the website.  
- [Atom](https://atom.io/) for trying out code (IDE), due to limited usage time on gitpod.
- [Google fonts](https://fonts.google.com/) for the fonts used in the website.  
- [Font Awesome](https://fontawesome.com/) for the icons used on the website.  
- [Hover.css](https://ianlunn.github.io/Hover/) was used for the hover effect on the navigation-links.  
- [Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools)
was used to debug and checking/testing the website.

# **Testing**
In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.
Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.
For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:
Contact form:
Go to the "Contact Us" page
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.
You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.
If this section grows too long, you may want to split it off into a separate file and link to it from here.
4. Testing
	The testing writeup should go through your  site with a fine tooth comb and document clearly everything you have done  to ensure that your site works. Testing is far more than just confirming  that the navigation links work. You also need to consider your sites  responsiveness and browser compatibility. You should go back over the user stories you defined  in the UX section and go through each one, document in detail how your site meets  these pre-identified needs and wants.

Use the HTML an CSS online validators.
Use Chrome Dev Tools: right click -> inspect -> search/select Lighthouse from the top screen.

## **Deployment**

To deploy this website to GitHub, I followed the these steps:

1. Go to GitHub.com and on the left side click on the repository:chizzletaz/MilestoneProject1.
2. In the repository click on the ‘Settings’-tab at the top.
3. Scroll down to ‘GitHub Pages’.
4. Under ‘Source’ you see the word ‘None’ with a dropdown menu: select ‘master branch’.
5. Click ‘Save’, this will give you a URL of the website (see above ‘Source’).

Local Clone:
1. Go to GitHub.com and on the left side click on the repository.
2. Click on the ‘Code’ button.
3. To clone using HTTPS, copy the link that is displayed.
4. Open a terminal in your preferred IDE (e.g. Atom)
5. Use  the ‘git clone’ command and add the link that you copied in step 3.  For Atom: Toggle command palette (cmd-shift-p (macOS) or shift-p (Linux/Windows) and search ‘git clone’: Add the link and 
6. A clone will be created locally.

For more info on how to clone a repository check [here](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository)

# **Credits**
### code
- Changing the colour of the hamburger icon.  
[Amirreza Mohammadi](https://stackoverflow.com/questions/42586729/bootstrap-4-change-hamburger-toggler-color)
- [Loader](https://www.w3schools.com/howto/howto_css_loader.asp)  
- How to play audio for correct/incorrect answer:
[Uri](https://stackoverflow.com/questions/9419263/how-to-play-audio)

### Content
The text for section Y was copied from the Wikipedia article Z

### Media
Images  
- [Background image](https://pixabay.com/illustrations/game-background-sky-game-landscape-4956017/
) of index.html page.  
- [Trophy image](https://gallery.yopriceville.com/Free-Clipart-Pictures/Trophy-and-Medals-PNG/Trophy_Cup_PNG_Clipart)  
- Icon music on: Icon by <a href="https://freeicons.io/profile/6156">Reda</a> on <a href="https://freeicons.io">freeicons.io</a>  
- Icon music off: Icon by <a href="https://freeicons.io/profile/6156">Reda</a> on <a href="https://freeicons.io">freeicons.io</a>
                                  
Music  
- [background music](https://www.chosic.com/download-audio/?t=27247)
Monkeys Spinning Monkeys Kevin MacLeod (incompetech.com)  
Licensed under Creative Commons: By Attribution 3.0 License
http://creativecommons.org/licenses/by/3.0/  
Music promoted by https://www.chosic.com/  

sounds:  
- Correct answer: [Correct answer 9](https://www.dreamstime.com/stock-music-sound-effect/correct-answer.html)  
- Wrong answer: [Gameshow wrong answer fail buzzer bleep](https://www.dreamstime.com/stock-music-sound-effect/wrong-answer.html)

# Acknowledgements
I received inspiration for this project from X


