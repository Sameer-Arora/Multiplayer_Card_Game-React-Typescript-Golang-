# Multiplayer_Card_Game-React-Typescript-Golang-

## Motivation
This Repository is meant to create a multi-player card game in a tutorial style building the game from very basics and keep on adding complexixty as it progresses.  The tech stack used by the game :- 
- **React** for creating dynamic content client-side.
- **Typescript** to add reliablility to our react app.
- **Golang** based backend for managing the game state in multi-player environment.

The project will proceed in stages as described in the open issues and is meant to be a great way of learning experience for developers to explore multiple challenges of the distributed multi-player environment.

## Intital Plan 

### Entities Involved

#### Game Model
- Players
- Cards( Cutomizable and Static )
- Decks(Collections of Cards)
- Hand(A single interaction within players which reaches the goal i.e. all possible moves of each player have been played.)
- Rounds(A timeseries execution of a hand)
- Scoreboard(Aggregate of the scores gained in each hand)
- Rules (collection of settings to modify the game execution).
  
#### Game Architectures
  #### Networking Topology
  - Local Hosted Single Machine
  - LAN hosted on single network.
  - Peer-2-Peer hosted on single client as server with other as clients(Pitfall: Server Domination)
  - Dedicated Server Hosted

  #### Functional Requirements
  - Authentication & Authorization.
  - Customizable Cards and Rules
  - Timed Moves for players to avoid blocking others.
  - Fault Tolerance & Resilient ( shouldn't break anything if some players leave or are inactive ).
  - Shareable decks to let build great decks collection.

## Incremental Goals :-

- Create a local card game that works with two players.
  - Create front-end for the visible entities
    - Players Logos/Profiles
    - Cards
    - Decks
    - Game Runtime (Scoreboard,Hand,Round)
  - Create game working logic along with the components.
  - Create scenario based tests to get relaible behaviour.
  - Collect game metrics to measure the performance. 
## References
-  https://github.com/Lattyware/massivedecks