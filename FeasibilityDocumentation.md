# Courier Crusader Feasibility Documentation

- [Courier Crusader Feasibility Documentation](#courier-crusader-feasibility-documentation)
- [1. Project Overview](#1-project-overview)
  - [1.1 List of Team Members](#11-list-of-team-members)
  - [1.2 Project Description](#12-project-description)
  - [1.3 Conceptualizations and Motivations](#13-conceptualizations-and-motivations)
  - [1.4 Player Experience](#14-player-experience)
- [2 Findings](#2-findings)
  - [2.1 Project Scope](#21-project-scope)
    - [2.1.1 Project Constrains](#211-project-constrains)
    - [2.1.2 Technology Involved](#212-technology-involved)
    - [2.1.3 Technology Alternatives](#213-technology-alternatives)
  - [2.2 Feasibility Analysis](#22-feasibility-analysis)
    - [2.2.1 Technical Feasibility](#221-technical-feasibility)
    - [2.2.2 Economic Feasibility](#222-economic-feasibility)

# 1. Project Overview 

Courier Crusader is a top down rogue like game built in Unity where the player has to balance delivering packages or stealing them in order to pay their rent at the end of the day. The player also has to balance other factors such as endurance, theft level, in order for the game to continue. They also have a talent tree which they can spec out their character during each run to customize the player experience.

## 1.1 List of Team Members 

- Nicholas James Xavier Orcsik
  - [Github](https://github.com/norcsik)
  - [LinkedIn](https://www.linkedin.com/in/norcsik/)
  - [Portfolio](https://norcsik.github.io/nicholas-orcsik-portfolio/)
  
- Alex Coutinho
  - [Github](https://github.com/norcsik)
  - [LinkedIn](https://www.linkedin.com/in/norcsik/)
  - [Portfolio](https://norcsik.github.io/nicholas-orcsik-portfolio/)
  
-  Ivan Zrvnar
     - [Github](https://github.com/norcsik)
     - [LinkedIn](https://www.linkedin.com/in/norcsik/)
     - [Portfolio](https://norcsik.github.io/nicholas-orcsik-portfolio/)

## 1.2 Project Description 




## 1.3 Conceptualizations and Motivations

Many top down rogue lites have a similar concept of a player trying to survive in a procedurally generated world. Courier Crusader is no different, but it has a few unique features that make it stand out from the rest. The first is the ability to steal packages from people within the world. This adds a new layer of strategy to the game as the player has to balance the risk of stealing packages with the reward of getting more money. The second is the talent tree. The talent tree allows the player to customize their character to their play style. This allows the player to have a unique experience every time they play the game. The third is the ability to upgrade your character. The player can upgrade their character by buying new items which will increase their stats. This allows the player to have a sense of progression as they play the game.


## 1.4 Player Experience 
- Main Gameplay Loop:
  - Player must balance delivering packages with stealing packages (delivering packages is less risky, stealing packages makes you more money) 
  - Rogue-like runs (ends if you cannot pay rent/expenses or get caught stealing) 

- Day Night Cycle
  - Player starts each day with a full endurance bar. They start in their apartment, where they may swap items. 
  - During the day, deliver any amount of packages (recommend a minimum “quota” of packages needed to be delivered each day). Delivering packages drains Endurance/Energy. 
  - After day shift, return to apartment to swap items. Can also visit shop to purchase upgrades on skill tree. 
  - The player will leave items they wish to sell in a mailbox and once the cycle restarts they will given money for the items in the mailbox.
  - Certain foods can restore endurance depending on the day. Example coffee gives a boost in the morning, but a soda will give a boost in the afternoon.
  - Endurance is returned to full at end of the day, and all expenses are paid. Game is over if all bills cannot be paid in full. 
  - The cycle restarts in two ways A) Player choice: Player can go to bed to restart the cycle. B) Player runs out of endurance. If endurance runs out, the player will be forced to go to bed.

- Delivery and Theft Cycle
  - This is the main gameplay mechanic which everything is based around. 
  - The Packages have a weight and dimensions, which hint at its contents. However, the items is unknown until the player returns to their apartment at the end of the night shift. Each successful theft causes the player’s threat level to increase, and their threat level naturally decreases each day. 
  - The items in the package range from valuable items, consumables (food, drinks, etc), and trash.
  
- Skill Tree
  - Skill tree is a way for the player to customize their character to their play style. 
  - They can choose to focus on one aspect of the game, or spread their points out to be more well rounded. Either styled more towards delivery or theft.
  - Middle of the tree is balanced and more simple picks 
  - [Skill tree Example](Skill%20Tree.png)
  - Lower down the tree the stronger the abilities are almost in a way that they are overpowered.


- Inventory Management  
  -  Another major influence on the game is inventory management. The player will have limited space in their inventory, and will have to decide what items to keep and what items to sell.
  -  The player has "special" slots that if endurance runs out they keep but lose the rest of the items in their inventory.
  -  Weight and dimensions of the items will also play a factor in the inventory management.

- Items 
  - Items are a major part of the game. They can be used to restore endurance, increase stats, or be sold for money.
  - Different levels of rarity affects the cost
  - Some items will be consumable and some will give the player boosts. 
  - Items are found inside packages but can also be earned from being a good delivery person.
  - 
- How to lose the Game 
  -  If the player runs out of endurance, they will be forced to go to bed. 
  -  If the player cannot pay their bills at the end of the day, the game is over. 
  -  If the player’s threat level is too high, the player will get caught stealing and the game is over.


 




# 2 Findings 
## 2.1 Project Scope
### 2.1.1 Project Constrains 
### 2.1.2 Technology Involved 

- Game Engine Choice: Unity 

  - The Unity game engine provides all the tools for a top down 2D game along with providing us the ability to deploy on multiple platforms.
  - It also provides built features such as player movement, camera movement, and collision detection, which are all essential for a top down 2D game.
  - Unity Asset Store provides a large library of assets that we can use to create our game. This includes sprites, animations, and sound effects and are easily imported into the game.

- Version Control: Plastic SCM
   - Plastic SCM is a version control system built into Unity. It allows us to easily track changes to our code and revert back to previous versions if needed.
   - A GUI application similar to Github Desktop is provided to allow us to easily view the changes made to our code.
   - Plastic SCM is used by many large companies such as Ubisoft, EA, and many other indie developers to manage their code and have provided examples of their workflows and best practices.
  
- Documentation Tool: Visual Studio Code
   - When choosing a documentation tool, we wanted to choose something that was simple to write markdown in and was easy to use.
   - The use of version control was also important as we wanted to be able to easily track changes to our documentation.

- Communication: Microsoft Teams
   - Microsoft Teams is a communication tool that allows us to easily communicate with each other and share files.
   - It also allows us to easily create meetings and share our screen to show each other our progress.
   - It is also easy to use and has a simple interface that allows us to easily navigate through the application.

- Project Management: TBA
  - Microsoft Projects
  - Trello
  - JIRA



### 2.1.3 Technology Alternatives
- Game Engine Alternatives: Unreal Engine ,GameMaker Studio 2, Custom Engine
  - Unreal Engine
    - Although Unreal Engine is a great engine, it is not as beginner friendly as Unity. It also has a much higher learning curve and is more difficult to use. It also utilizes C++ instead of C#, which none of the team members have experience with.

  - GameMaker Studio 2
    - Another popular option for 2D games but for this project we wanted to use a more popular engine that would allow us to easily deploy on multiple platforms.
    - The asset store for GameMaker Studio 2 is not as large as Unity’s and does not provide as many assets as Unity does.
    - Scripts are written in GML, which is a custom scripting language that is not as popular as C# and unfamiliar to the team members.
    - For testing Unity allows developers modify the game in real time, which is not possible in GameMaker Studio 2.

- Version Control Alternative: Git
  - Git is the most popular version control system However, it is not built into Unity and requires additional setup to use.
  - The major drawback of using Git is the way Unity handles its assets and how it tracks them into a project. For larger assets it's is recommended to use Git LFS so when uploaded to Github you won't run into file size limits.
  - 




## 2.2 Feasibility Analysis
### 2.2.1 Technical Feasibility
### 2.2.2 Economic Feasibility

