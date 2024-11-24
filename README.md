![image](https://github.com/user-attachments/assets/60ae159b-fc7b-4601-b8bd-cc990e538b0f)

## **DISCLAIMER**

This project is intended for educational and learning purposes only. Users who wish to play the game must build it themselves if I decided to release the source code, as no executable files will be provided.

I strictly discourage any illegal use of tools, assets, or files associated with this project. Please respect all applicable copyright and intellectual property laws.

-----------

## **Current Status** 

### Prologue

- [x] Custom intro
- [ ] Title / press any button
- [x] Previously / recap
  - [ ] Add QTE function
- [ ] Star launch cutscene
- [ ] Traveling multiverse
  - [ ] Multiple star gates - distance view
  - [x] Third person view
    - [ ] Controllable
    - [ ] Glimpses of different worlds
      
### Chapter 1
- [ ] Design mushroom kingdom
  - [ ] Import all assets
  - [ ] place npcs
  - [ ] add effects, water, etc
- [ ] intro to mushroom kingdom
  - [ ] cutscene - overall map
  - [ ] cutscene - astro bot landing
- [ ] implement mission objective
- [ ] speak with toad to start mission
- [ ] new ability - mario hat
- [ ] stage 1 clear goombas
  - [ ] optional - hidden coins
- [ ] optional - in game trophy
  - [ ] store inside a trophy room
- [ ] access to peach castle
- [ ] dialogue to next stage

<!---Idea: implement minigames for trophy reward1. Mariokart2. Luigi mansion3. Slaparazzi-->

### Chapter 2
- [ ] *TBA*

<!---
Ch2
 - [ ] ideas to next map   - [ ] luigi mansion   - [ ] zelda   - [ ] kirby   - [ ] splatoon - [ ] or kart our way thru rainbow bridge
-->

----------

## **Development Log**

Development process, techniques and other knowledge sharing will be documented here<br>[Dev Logs](DevLog/)

----------

## **Game Story Flow**

```mermaid
flowchart LR
X("**PROLOGUE**"):::startFinish
A("**INTRO**<br>Custom Logo"):::green
B("**TITLE SCREEN**<br>Press any button"):::green
C{"**QTE EVENT**<br>Previously on..."}:::blue
D{"**PLAYER**<br>Star Appears"}:::orange
E("**CUTSCENE**<BR>Travelling Multi-verse"):::pink
F("**CHAPTER 1**"):::startFinish
A --> B 
C --> D --> E --> F
classDef green fill:#B2DFDB,stroke:#00897B,stroke-width:2px,color:#000
classDef orange fill:#FFE0B2,stroke:#FB8C00,stroke-width:2px,color:#000
classDef blue fill:#BBDEFB,stroke:#1976D2,stroke-width:2px,color:#000
classDef yellow fill:#FFF9C4,stroke:#FBC02D,stroke-width:2px,color:#000
classDef pink fill:#F8BBD0,stroke:#C2185B,stroke-width:2px,color:#000
classDef startFinish fill:#000000,stroke:#8E24AA,stroke-width:3px,color:#fff
```
----------
```mermaid
flowchart LR
X("**CHAPTER 1**"):::startFinish
A("**CUTSCENE**<br>Kingdom View"):::pink
B("**CUTSCENE**<br>Player Entrance"):::pink
C{"**PLAYER**<br>Follow Objective(s)"}:::orange
D{"**PLAYER**<br>Optional objective<br>available"}:::blue
E("**CUTSCENE**<BR>Castle Unlocked"):::pink
F{"**PLAYER**<BR>Talk to Princess Peach"}:::green
G("**CHAPTER 2**"):::startFinish
A --> B --> C --> D
C --> E --> F --> G

classDef green fill:#B2DFDB,stroke:#00897B,stroke-width:2px,color:#000
classDef orange fill:#FFE0B2,stroke:#FB8C00,stroke-width:2px,color:#000
classDef blue fill:#BBDEFB,stroke:#1976D2,stroke-width:2px,color:#000
classDef yellow fill:#FFF9C4,stroke:#FBC02D,stroke-width:2px,color:#000
classDef pink fill:#F8BBD0,stroke:#C2185B,stroke-width:2px,color:#000
classDef startFinish fill:#000000,stroke:#FF0000,stroke-width:3px,color:#fff
```
----------
```mermaid
flowchart LR
X("**CHAPTER 2**"):::startFinish
A("*WIP*"):::green
F("**CHAPTER 3**"):::startFinish
A  --> F
classDef green fill:#B2DFDB,stroke:#00897B,stroke-width:2px,color:#000
classDef orange fill:#FFE0B2,stroke:#FB8C00,stroke-width:2px,color:#000
classDef blue fill:#BBDEFB,stroke:#1976D2,stroke-width:2px,color:#000
classDef yellow fill:#FFF9C4,stroke:#FBC02D,stroke-width:2px,color:#000
classDef pink fill:#F8BBD0,stroke:#C2185B,stroke-width:2px,color:#000
classDef startFinish fill:#000000,stroke:#39FF14,stroke-width:3px,color:#fff
```

-----------

## **CREDITS**

[X: @_SnakePlissken1](https://twitter.com/_SnakePlissken1) - For helping me get started and the ongoing support
