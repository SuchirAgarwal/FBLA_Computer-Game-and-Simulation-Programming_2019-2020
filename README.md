# Road to BAA Mastery
FBLA 2019-2020 Computer Game and Simulation Programming

Parkland High School

Suchir Agarwal, Udit Garg, and Raviteja Kanthamneni

PA FBLA

### Overview
Road to BAA Mastery transforms the Business Achievements Awards Program into a fun and interactive role-playing journey the player undertakes to reach a final goal: the BAA Awards. The player starts on a map where two FBLA elders guide his/her path through the four major levels and minigames: Progress, Service, Education, and Mastery. Completing each level provides the player with an accomplishment token they must have in order to progress through the game. Throughout these levels we integrated lives, tokens, penalties, interactive battles, quizzes, and game progression. By creating a role-playing game we wanted the player to understand the best actions to take and apply the BAA program skills in the real world. Once the player finishes the game they are presented with a pin at the end-game Awards Ceremony just like real FBLA.
The user interface and instructions are identified when the gameplay starts in order to minimize player confusion.

### Minigames
#### FBLA Member Recruitment: Progress Level
* Players must choose the right words and phrasing to successfully recruit new members to join FBLA and its program.
#### Park Clean-Up: Service Level
* Players pick up the trash and litter polluting a local park alongside of an FBLA student chapter. Additionally, there is a time limit for this level to increase difficulty.
#### Quiz: Education Level
* Players must correctly answer questions regarding FBLA and the BAA Program.
#### Final Exam: Master Level
* This level provides a final review of the three essential requirements for the BAA Program. It is inspired to be the boss level of the game where the user can battle monsters and earn large rewards to get to the end of the game.

### CONTROLS
* [Up Arrow Key] Move Foward
* [Down Arrow Key] Move Backward
* [Left Arrow Key] Move Left
* [Right Arrow Key] Move Right

* [Right-Mouse Button] In-Game Menu/Back/Quit/Exit
* [Middle-Mouse Button] Dash
* [Left-Middle Button] Confirm/Move

* [Enter/Space] Confirm/Interact
* [Q/Page-Up] Show Controls
* [W/Page-Down] Hide Controls
* [ESC/X] In-Game Menu/Back/Quit/Exit

### Development Environment and Requirements

| Environment Specifics | Tool Used |
| --- | --- |
| IDE  | RPG Maker MV  |
| Language  | Javascript  |
| Operating System  | Windows |

### Running Game on Windows
1. Open the application file in the windows package.

### Running Game from index.html
Most browsers will not let the index.html file load local files due to security reasons. If this is a case, then the two options would be to either enable loading local files or to create a local server. We will take you through the process of creating a local server via Browsersync.
1. Download and install Node.js from https://nodejs.org/en/download/
1. Enter `npm install -g browser-sync` in the terminal or command prompt and press enter
1. If the previous step fails due to permission errors, then use `sudo npm install -g browser-sync`. This will then prompt you to enter your password.
1. Clone or download this repository.
1. Use the terminal or command prompt to `cd` into the repository and use the command `browser-sync start --server`. This will automatically load the index.html file in a default browser. In order to specify the desired browser, use `broswer-sync start --server --broswer <CHOICE OF BROWSER>`.

### Other platforms
Since our game was created with RPG Maker MV, it is distributable on additional platofrms such as macOS, iOS, and Android. We have not included those distributions in this repo due to the difficulty of managing a repo that is this large. If desired, the additional distributions can be built from source using RPG Maker MV.

### Possible Awards & Tokens
1. Tokens are given when the user completes a level by meetings its requirments. 
1. Mastery Awards are given when the user receives a perfect score in a specific level. Ex: the user receives a 100% on the Education Level Quiz.
1. The BAA Gold Award is earned upon completion of the game. 
1. The BAA Mastery Award is earned if the user has received all of the Mastery Awards for each level.
1. The Full Life Award is earned if the user hasn't lost any lives.

|     | Token | Mastery Award |           
| --- | --- | --- |
| Progress  | Yes | Yes |       
| Service  | Yes | Yes |
| Education | Yes | Yes |


| Award | Requirements |           
| --- | --- |
| BAA Gold Award  | Completion of Game |       
| BAA Mastery Award  | Received all Mastery Awards |
| Full Life Award | No lives lost |

### Team Members
* @SuchirAgarwal
* @uditgarg32
* @TK164
