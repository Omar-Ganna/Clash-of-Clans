Tower Defense Game README
Welcome to our tower defense game project implemented in C++ with Qt! Below you'll find a comprehensive overview of the project's structure, classes, functionalities, and more.

Project Overview
Our tower defense game presents players with a challenging task: defend the castle against waves of incoming enemies. Players can strategically place defenses such as fences and cannons, as well as deploy troops to fend off the enemy onslaught. With multiple levels, unique themes, and customizable upgrades, players are in for an engaging gaming experience.

Features
Login and Sign-Up: Implemented using hash tables, players can either log in with existing credentials or sign up for a new account.
Market: At the beginning of the game, players can access the market to purchase fences and defense items to fortify their castle.
Object-Oriented Design: Classes such as Castle, Cannon, Fences, Troops, and Bullets are implemented with inheritance and aggregation to manage game elements efficiently.
Level Management: The Levels class serves as the main game controller, handling spawning of troops, updating game time, and determining win conditions.
Sound Effects and Themes: Immersive gameplay experience with thematic music and sound effects corresponding to each level.
Dynamic Gameplay: Troops utilize A* algorithm for pathfinding, and collisions with defenses or the castle result in dynamic interactions affecting health and damage.
Progression System: Five levels of increasing difficulty provide players with a challenging progression curve. Additionally, players can upgrade defenses between levels using tokens earned in-game.
Endings: Happy or sad endings based on player performance, with statistics displayed at the end using merge sort for easy analysis.
Implementation Details
Object Classes: Castle, Cannon, Fences, Troops, and Bullets classes are designed with health attributes and unique functionalities.
Market and Clan Interaction: Players can access the market at the start and between levels, with the ability to continue to the next level or customize their defenses.
Forward Declaration: Utilized to resolve circular dependencies between classes for efficient access and management.
How to Use
To run the game, simply compile the project files and execute the main program. Follow on-screen instructions for login, market interactions, and gameplay. Enjoy defending your castle against relentless waves of enemies!
