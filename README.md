### Greetings

I'm Alan, a Software Developer located in Southern California

### About Me

Formerly a musician playing the French Horn (and still Drumset), I've been programming since 2011, starting with designing and hosting customized videogame servers, expereince working in Aviation Software at Northrop Grumman, and now working at ASML via nology. Many of my hobbies intersect with programming such as video editing and arduino code (partially for model train automation), along with motorcycles and cars, movies, and still some music playing.

- Langauges: Java, Node/JS, C++, Lua, PHP, Python, Batch, Bash... English, a bit of Japanese...
- Concepts: OOD, Networking, Threading, API Creation/Usage
- Software: Jenkins, GIT
- Systems: Windows  (7, 10, Server 2008), Linux (Ubuntu, Debian, Redhat)
- Databases: Mysql, MariaDB, Postgres, Json, Excel

### Recent Personal Projects

- [3d Printed + Arduino Timezone Map](https://github.com/AlanGreaney/TimezoneMap)

Using 3d Printing and Arduino Code, I created a Topographical map that has multiple 4-digit 7-segment displays. I created my own code to sync the output on the segment displays across 4 timezones, with buttons on the breadboard to change the minute/hour and brightness/daylight-savings. More technical details in it's main repository.

<img src="https://raw.githubusercontent.com/AlanGreaney/TimezoneMap/main/img/mapMounted.jpg" width="75%">

<img src="https://raw.githubusercontent.com/AlanGreaney/profile/main/images/mapWip2.jpg" width="75%">

- [Streamdeck Video Player](https://github.com/AlanGreaney/Streamdeck-Video-Player)

Using FFMPEG and ImageMagick video/image editing libraries through NodeJS, this program converts a video into a format able to be played via the Streamdeck's API, something it was not at all designed to do even with it's LCD buttons, which made for a great challenge. A higher quality version of this GIF is available on the specific repo

<img src="https://thumbs.gfycat.com/CautiousFantasticBergerpicard-size_restricted.gif" width="75%">

### ASML x Nology Training Course

    - Week 1 - HTML/CSS/SaSS

- [CSS Flexbox Usage](https://github.com/AlanGreaney/nology-coursework/tree/main/CSS_HTML_Week1/flexbox-challenge)

Webpage Displaying usage of Flexbox for advanced webpage layouts in CSS, dynamically sized to the screen.

<img src="" width="75%">

- [SASS/SCSS](https://github.com/AlanGreaney/nology-coursework/tree/main/CSS_HTML_Week1/sass-two)

Example "Budget" Travel Site Created using SASS to handle creation of CSS, including nesting and responsiveness.

<img src="https://raw.githubusercontent.com/AlanGreaney/profile/main/images/sass.PNG" width="75%">

- [CSS Grid Area](https://github.com/AlanGreaney/nology-coursework/tree/main/CSS_HTML_Week1/css-grid-area)

Imaginary Photography site similar to the Flexbox project above, but using another method for website layout and responsiveness: CSS Grids. 

<img src="https://raw.githubusercontent.com/AlanGreaney/profile/main/images/responsive.PNG" width="75%">

    - Week 2 - Python
    
- [Main Work](https://github.com/AlanGreaney/nology-coursework/tree/main/Python_Week2/env)

Multiple small projects demonstrating understanding of the Python Language, such as Loops, Datastructures, Control Flow, Entry Points, Logging to Files/CSV, and Object Oriented Programming by means of Classes and Imports.

- [Text Adventure Projects](https://github.com/AlanGreaney/nology-coursework/tree/main/Python_Week2/env/textAdventureProject)

Utilizing all concepts listed above, we were to create a text adventure game to run within a command line window. Pushing this concept farther than the example we were to copy, I created a generalized framework for any game, which allowed for the creation and linking of scenes, theoretically allowing basically any text game to be loaded, the idea being I wanted to approach it with a way where any classmates' games could be loaded into my framework, instead of all being hardcoded.

The Main File simply loads whatever specified game is wish to be played, and follows the scene order based off the Option-Classes. A game-print function was included, that automatically converts all story text string into the boxes surrounded by characters, so that manual sizing of the text-promopts did not have to be done manually. A method to display ASCII images within a scene was also included.

<img src="https://raw.githubusercontent.com/AlanGreaney/profile/main/images/textAdvEx1.PNG" width="75%">
<img src="https://raw.githubusercontent.com/AlanGreaney/profile/main/images/textAdvEx2.PNG" width="75%">

    - Week 3 - Python + Flask

- [Initial Flask Projects](https://github.com/AlanGreaney/nology-coursework/tree/main/Python_Flask_Week_3/Day_2_API)

Projects surrounding Flask, using Python to interact with Databases, GETS/PUTS, and HTTP Status Codes. General project was to make an API for a theoretical room tempature monitor. This would allow for remote entry of Tempatures along with the Room ID and a Timestamp, then also retrieving that data in forms such as average tempature, number of days recorded, etc.

The following code snippet was a bonus I added to the project - a function to add random data into the database to simulate a previous months' worth of tempature recording to verify the other methods listed above were working well, without having to enter tons of data manually.

<img src="https://raw.githubusercontent.com/AlanGreaney/profile/main/images/flaskEx1.PNG" width="75%">

    - Week 4 - Python Unit Testing (PyTest)
    
- [Text Adventure ReWork](https://github.com/AlanGreaney/nology-coursework/tree/main/Testing_Week_4/Refactor_Text_Adventure)

In Week 4, we were given an introduction to the PyTest module to begin implementing into future projects. This covered concepts such as testing classes, asserts, parameerized testing, and fixtures. The first project was to add testing into the previous Text Adventure Project. Since my original code was written with Object-Oriented Programming Design, only one line of code ended up needing refactored to work PyTest into the project to test all ascpects of its workings, such as loading data, displaying the fancy squared output, and doing a turn in the gamestate.

- [Zoo Manager API](https://github.com/AlanGreaney/nology-coursework/tree/main/Testing_Week_4/Zoo_Project)

The prompt for this project was to start on a fresh project with OOP design and create an API for a Zoo's Management to use to track enclosures, and what animals were in them, using methods such as adding enclosures, adding animals, and viewing their various statuses. On top of the prompt, I added ways to edit the animals, and automatically return data whether enclosures were recalled by name or id.

This project makes heavy use of fixtures to setup a single test database connection and a fixture of the Flask App instance used for testing, run in module mode to prevent recreation during every test. The final output includes 8 tests covering all user-features with a high rate possible of use cases, along with basic functions such as connectivity and logging. The output is put into an HTML report page for easy viewing of what is/isn't passing, with dropdown boxes that explain further what the test is doing to meet it's pass criteria.

<img src="https://raw.githubusercontent.com/AlanGreaney/AlanGreaney/main/images/ZooManagerEx1.PNG" width="75%">

<img src="https://raw.githubusercontent.com/AlanGreaney/AlanGreaney/main/images/ZooManagerEx2.PNG" width="75%">

    - Week 5 - CI/CD + ISTQB
    
Week 5 consistented half of training in CI/CD via Jenkins and AWS, and half of ISTQB princple study. There are no direct work products to show, however, there were multiple sample tests taken for ISTQB training with high scores achieved in each. The ISTQB princples and Jenkin's pipeline information is also being worked into the Week 7 project, and will be visible upon completion of that task.
    
    - Week 6 - CRUD Project + MongoDB
    
Week 6 was a CRUD application - Create/Read/Update/Delete - based in Python using MongoDB. The project breif was to create an application that tracks Parts in a wharehouse, and create a high-level of testing coverage.

<img src="https://raw.githubusercontent.com/AlanGreaney/AlanGreaney/main/images/crud1.PNG" width="75%">

Unfortunately, I do appear to have uncovered a bug in PyTest Coverage resulting in an unknown line being shown as "missing" coverage, but none highlighted in the app! However, full decision statement coverage has been achieved.

<img src="https://raw.githubusercontent.com/AlanGreaney/AlanGreaney/main/images/crud2.PNG" width="75%">

7 Main tests were used to cover all the functionality - in addition to CRUD, I also added extra ability to check stock that had expired on it's shelf life, and check stock that was below it's "desrived reserve" level, and return JSON data containing the relevant info a parts administrator might need. The 7 tests end up being 17 in the report, as many of them run multiple timns thanks to parametization in PyTest, allowing for the re-use of a single function multiple times with varied of data, which greatly sped up the time it took to write the tests, and the time it would take to add/change them in the future.

```
@pytest.fixture()
    def app(self, mongodb):
        app = create_app(mongodb)

        yield app
```

The creation of the test-database was done via pytest-mongodb, which allows for the very clean setup within the testing environemt as seen above, and allowed for hosting the test data locally, allowing for quick repeatability of test-cases.

    - Week 7 - NologyNav Testing-Focused Project

Week 7 was a colloaborative project with other group members to take a project through a full agile delivery sprint. Starting with recieving a project prompt and attending a requirements gathering meeting, the project was then built using Test Driven Development, with a workload spread out through Trello project tracking.

The main requirements were to use the Google Navigation API to take in a Origin/Destination and turn it into a human-readable summary including things like distance, time to travel, and modes of travel. The team made lots of deicsions about the project - hosting the code on Git and using reviewed-pull requests for every code change, the method to build up the data for the user, and how to best integrate the tests to Jenkins for automated CI/CD.

This project mainly took the previous 6 weeks of training and combined it all, whilst also allowing for an experience of working in a team performing all these development techniques instead of working alone. The start of the project involved writing a detailed test plan which was the basis of all the tests and therefore development of the project to meet the outlined user stories.

<img src="https://raw.githubusercontent.com/AlanGreaney/AlanGreaney/main/images/week7_1.png" width="75%">

30 Tests were written to achieve 100% statement coverage using whitebox and blackbox testing techniques at the unit and system level, respectively. A notable overcome challenge durign test design was dealing with the final integration tests using live data from the Google API. Since directions often change due to traffic, road closures, ferry schedules, etc, we had to modify tests to use PyTest's Approx() module to allow a tolerance for distance/times in the route, while still testing for exact matches on items like start/end position.

The Jenkins testing pipeline was setup so that a build was run and then tested after every pull request on Github, as all development was done on a team member's dev branch before being merged into the main project.

<img src="https://raw.githubusercontent.com/AlanGreaney/AlanGreaney/main/images/week7_2.png" width="75%">
