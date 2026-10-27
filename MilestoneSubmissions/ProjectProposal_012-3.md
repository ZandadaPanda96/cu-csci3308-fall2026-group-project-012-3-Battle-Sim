<!---Yuan was a great help on 7,8,9,10,12 and 14, as well as fixing some spelling errors not in those issues, thank you Yuan!  --->
# 1. Team Number
012-3

# 2. Team name
Team Avatar

# 3. Team Members
|Name       | Email      | Github |
| --------- | :---------:|------:|
| Max Martin | Max.Martin-2@colorado.edu | maxwellmartin1005-blip |
| Jamie Grove | Jamie.Grove@colorado.edu | jamiegrove76-pixel |
| Aidan Johnson | Aidan.Johnson-2@colorado.edu | Aidan-dev50 |
| Andre Kalberer | Andre.Kalberer@colorado.edu | AndreKalberer |
| Zander Trafton-Hancock | Zander.Trafton-Hancock@colorado.edu |ZandadaPanda96 |
| Yuan Zuo | Yuan.Zuo@colorado.edu | yuanzuo09 |




# 4. Application Name
Battle Sim 

# 5. Application Description
A short (2-3 paragraphs) overview description of the application. Provide enough information to explain what functionality and value your product will provide to users of your application. This should help you to define the scope of your project:

Battle Sim is an online turn-based multiplayer creature battler where players fight against each other with avatars of themselves or others. While there are many similar games currently on the market, what sets (name here) apart is its customisability, and instead of creatures doing the battling, it is a direct representation of the player(or even someone else). By default, there is at least one(probably two for testing) premade fighter for example purposes. The character creation process is done by uploading an image of yourself and then selecting your move set(more info is needed on how this is to work, such as balancing, how many moves, and other mechanics, one form of balance may be to have some things tied to a random number generator, such as health, what types of moves you could choose for this character, etc. Speaking of moves, we could combine the previous idea with a class/type system, for example, if someone designs their avatar to be a fire class character, they will have acess to choose moves that class can learn, including some exclusive moves, but to avoid the issue of players just choosing the strongest moves, we could partially randomize what moves they could choose from. Another way we could solve the move balancing issue is by having a leveling system that unlocks more moves.) This section needs rewiritng now that we have more info



# 6. Audience
Our target audience is those looking for a fun game to play together while also looking for a customizable experience. 

# 7. Vision Statement
Our vision statement is: "To create an original and entertaining battle simulator that combines customizable character building with strategic turn-based combat."

# 8. Version Control info
[Github Repository Link](https://github.com/ZandadaPanda96/cu-csci3308-fall2026-group-project-012-3-Battle-Sim)

# 9. Development Methodology
We will use a hybrid Agile Methodology that draws ideas from Scrum and Kanban. 
Particularly, we will have one or multiple short weekly Scrum meetings to discuss about our progress and coordinate work to do for the next sprint.
At the same time, we will track our progress visually in Github issues by opening multiple epics and stories for people to work on and check off.

# 10. Communication Plan
We plan to use Discord as our primary way of communication, and we have already set up a discord server for the project. 
In discord, we will be using the threads feature to keep conversation topics specific and make the chat more organized for future reference.

# 11. Meeting Plan
Team Meeting: Identify the day(s) and time(s), mode, and location your team has agreed upon for regular meetings. “Modality” refers to how you are meeting (face-to-face), group video chat (like Zoom, Google Meet), etc.
Weekly meeting with TA: You will also mention the meeting day, time and location (in-person or online) for the weekly meeting with your TA here.
Please refer to these instructions for expectations in your weekly meeting with your TAs. Do read the entire section carefully.

All times bellow are in MDT unless othweise stated

Team meetings are currently planed to be held in person during recitation hours, which are 11:25 AM- 1:05 PM on Thursdays. If other meetings are required they will be scheduled as the need arises

Weekly meetings with our TA [name here] will take place on Tuesday 10:00 AM to 10:15 AM

## Please note
All times listed above are subject to change

# 12. Use Case Diagram

<!----This section is a slightly moddifed from of  Jamie Grove's use_case_diagram.md, thank you again Jamie! ----->
![Use Case Diagram](use_case_diagram.png)

## Actors
- **Player** - A registered user who creates characters and battles.
- **Opponent** - Another player on the other side of the battle.

## Use Cases
| # | Use Case | Description|
|---|----------|------------|
| 1 | Register | A new user creates an account |
| 2 | Log in | A returning user signs in to access their characters |
| 3 | Create Character | The player uploads an image of themselves or someone else to use as their fighter. |
| 4 | Use a premade fighter | The player can pick one of the games fighters instead of making their own. |
| 5 | Select a character for battle | The player chooses which fighter to bring to battle. |
| 6 | Battle another player | Two players battle each other in a turn-based battle. |
| 7 | Choose move each turn | On each turn, the player picks one of their fighters moves to use. |

## Note
Features are subject to change.

# 13. Wireframes
You will create wireframes for each page of the application.
Wireframes are low-fidelity visual representations of the user interface of your application. They are used to plan the layout of the application and to communicate the flow of the application to the team. You can use any tool of your choice to create the wireframes. Hand sketched wireframes are also acceptable. You can refer to this for more information on why and how

import wireframes here


<!----This section is a slightly moddifed from of  Jamie Grove's MilestoneSubmissions/risk_analysis.md, thank you once again Jamie! ----->

# Risk Analysis (Extra Credit)

| # | Risk | Severity | Mitigation | 
|---|------|----------|------------|
| 1 | A team member doesn't finish their part | High | Track tasks on GitHub, check in with the team, and reassign work if someone is stuck. |
| 2 | Merge conflicts when multiple people edit the same file | Medium | Everyone works on their own branch, keeps pull requests small, and pulls from main every time they start working. |
| 3 | Battles are unbalanced or battle logic has bugs | Medium | Keep the battle logic in its own file, test it separately, and adjust move values accordingly. |
| 4 | Changes to the database tables break other teammates' code | Medium | Keep the table setup in one shared SQL file and tell the team before changing it. | 
| 5 | The app runs differently on each teammate's computer | Medium | Everyone runs the app through one shared Docker Compose setup. |
