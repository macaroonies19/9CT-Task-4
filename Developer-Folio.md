# Developer Folio
## Identifying and Defining
### Identifying a need
I want to create a Top Down RPG on unity. 
Brainstorm:
- Complete puzzles to progress
- Defeat enemies
- Invetory
- Collectable items
- Storyline
- Memory (you will need to remember things earlier in the game to solve puzzles and progress)

Need:
My project will address the need for entertainment while encouraging players to think strategically and explore through an engaging and interactive game that also promotes problem solving and memory recall.

Problem Statement:
Lots of people, especially young people like teens need entertainment and often play video games for this. This top down rpg will meet that need by giving players a fun way to explore, solve puzzles, and make choices that impact the outcome of the story. Filled with puzzles and memory recall in order to progress, this game will challenge their brain and cognitive function while providing entertaining gameplay.

Skill development:
- To develop the skills in Unity required to create the game, I would utilise tutorials on youtube and alike, and also get some help from ai.
- Follow Unity 2D top-down RPG tutorials to learn about tilemaps, character movement, collisions, and dialogue systems.
- Practice basic C# scripting for player input, enemy AI, and inventory management.
- Learn how to use Unity’s UI system to display health bars, dialogue, and menus.
- Experiment with pixel art and sound effects for a complete user experience.

### Requirements Outline
Inputs:
- Directional keyboard keys for character movement (WASD).
- Mouse clicks or “E” key to interact with objects/NPCs
- "Esc" key to pause or open the menu
- "I" key for inventory

Processing:
- The program will check for collisions, and calculate the new position of the player when a movement key is detected.
- Open an interactable GUI when the inventory key is detected.
- Run an object specific script to load any puzzles.
- Run dialogue or event scripts when interacting with objects or characters.
- Constantly update stats like player health, experience, and inventory.

Outputs:
- The game will constantly update visuals (display the character's position, animations, environment)
- Sound effects for actions (footsteps, item pickups, attacks).
- On screen messages for dialogue, objectives, or health changes.
- Game over screen when you die.

Transmission:
- No online or network features planned (single-player only).

Storage:
- Save player progress (level, position, items, and stats) locally.
- Sprites/characters.

### Functional Requirements
User Interaction:
- Players move the character using the keyboard.
- Pressing “E” interacts with NPCs, doors, or objects.
- The menu button opens inventory and game settings.
- Health bars and quest text update in real time.

Core Gameplay or Simulation Mechanics:
- Explore the map to find quests, puzzles, and items.
- Engage in simple combat or puzzles to progress.
- Complete objectives to unlock new areas.
- Dialogue choices can affect story outcomes.

Scoring and Feedback (if applicable):
- Players earn experience points or currency and items for completing quests.
- Sound and visual cues reward progress or alert players to danger.
- Dialogue to guide a player in the general directly.
- The game will be more open world so you have to explore it for yourself.

Level Progression or Simulation Stages (if applicable):
- The player starts in a small area and unlocks new zones by completing tasks.
- Some areas require specific items or skills to enter.
- Completing all main quests leads to the game ending or credits.

Saving and Loading Data:
- Saved data is stored locally so players can continue later.
- The game saves automatically after completing key objectives.

### Non-Functional Requirements
Performance Requirements:
- The game should load in under 5 seconds.
- Frame rate should remain smooth (30–60 FPS).
- Controls should respond instantly to player input.
- Shouldn't seem laggy at all.

Usability Requirements:
- The game should have a simple, clear interface.
- Beginner friendly tutorial to explain how to move and interact.
- Text should be clearly readable.

Compatibility Requirements:
- The game should run on Windows and Mac.
- Controls will use keyboard and mouse input.

Scalability Requirements:
- The system should allow for more quests or new maps without changing the base code.
- If dlcs are added the game could possibly remove old tutorials or areas that are no longer needed or remove areas that have limited access.

Security Requirements:
- Save data will be stored locally in a non-sensitive format (no personal data).

Reliability and Availability:
- The game should autosave after major progress to prevent data loss.

### Consideration of Social and Ethical Issues
Define the following terms:
- Equity: Everyone having a fair opportunity regardless of circumstances.
- Accessibility: Available to anyone despite any circumstances or disabilities.

Accessibility:
- The game will include simple controls, colours will be chosen wisely to be readable for colour blind people, on screen subtitles for dialogue for deaf people, and instructions will be clear and easy to follow.

Privacy and Data Protection:
- The game will not collect any personal information. Saved data will be stored locally on the user’s device only.

Fairness and Representation:
- Characters will be designed to be diverse and inclusive, without stereotypes. Players will be able to play as a neutral character with choices that represent different values or personalities.

Mental and Emotional Well-Being:
- The game will avoid violent or distressing content and focus on exploration, strategy, and positive problem solving. The story will promote curiosity and exploration rather than conflict.

Cultural Sensitivities:
- All themes, dialogue, and symbols will be appropriate for all audiences. The game will avoid religious, political, or culturally specific imagery that could be misinterpreted.

## Researching and Planning: Exploration of Existing Ideas
3 different games I will draw inspiration from and compare my idea to. Considering positive and negative impacts, and how it impacts my project moving forward:

| Existing Idea | Plus | Minus | Implication |
| :--- | :--- | :--- | :--- |
|Hollow Knight![Hollow](https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/367520/header.jpg?t=1695270428) | Hollow Knight has done an excellent job creating a deep and atmospheric world with a cool, unique style of hand drawn art and smooth combat mechanics. Its exploration system encourages curiosity, rewarding players who take the time to discover hidden paths and secrets. | One downside of Hollow Knight is that its difficulty level can be frustrating for new players, and it doesn’t always give clear direction on where to go next, which can make players feel lost. | For my project, I will take inspiration from Hollow Knight’s sense of exploration and atmosphere but make my game easier to navigate with clearer objectives. I will also keep the difficulty more balanced to make it accessible for all players. |
|The Legend of Zelda: A Link to the Past![Zelda](https://assets-prd.ignimgs.com/2021/12/15/legendofzelda-linktothepast-1639586882982.jpg) |This game excels in world design and player engagement. Its top down perspective works well for exploration and puzzle solving, and the gameplay loop of exploring dungeons and gaining new abilities feels rewarding. |The dialogue and quest system can feel repetitive and linear, which limits replayability once the player knows what to do. |I will use Zelda’s exploration and puzzle design as a reference for my own top down rpg but will add more player choice and branching dialogue to make the story feel more personal and replayable. |
|Stardew Valley![star](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQp9QhAqExpEt5DMUmmh31szAeOq3OulK8yrOghKQISbhlTRrH78eHSaoI89uGSkJmAWomLBw&s=10) |Stardew Valley succeeds in giving players a sense of progression and ownership. The mix of exploration, customisation, and character interaction makes the world feel alive and connected. |The pace of the game can sometimes be slow, and new players might not understand how to progress efficiently without external guides, like youtube or searching on the wiki. |I will aim to include a sense of progression and discovery similar to Stardew Valley but simplify the systems and provide clear in game guidance so that players always know what to do next. |

## Researching and Planning: Flowchart and Pseudocode Example
A flowchart and pseudocode for all functional requirements of my game:

![movement]()
![interaction]()
![menu/UI]()
![healthbars/quests]()
![dialogue/choices]()
![combat]()
![area_unlocking]()
