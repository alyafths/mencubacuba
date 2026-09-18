# Effection

## Team Introduction

Hello everyone! We’re the Effection Team!

Our team is responsible for developing the Visual Effects System for the game. 
We'll be working on several improvements and new features aimed at enhancing the overall visual experience, gameplay feedback, and immersion.

## Members

| Name           | Role                       | GitHub                                          |
|----------------|----------------------------|-------------------------------------------------|
| Khairul Suffie | Team Leader & Collaborator | [KaiSuf](https://github.com/KaiSuf)             |
| Ariq Iqbal     | Assistant Developer        | [ariqiqbal](https://github.com/ariqiqbal)       |
| Alya Fatihah   | UI/UX Designer             | [alyafths](http://github.com/alyafths)          |
| Dian Melissa   | UI/UX Designer             | [dianpines](https://github.com/dianpines)       |
| Najihah        | Project Analyst            | [najihahs](https://github.com/najihahs)         |
| Maisarah       | Documentation              | [maisarah-mg](https://github.com/maisarah-mg)   |
| NurSofia       | Performance & QA Developer | [sofiajourke](https://github.com/sofiajourke)   |
| Elisya Natasha | Project Manager            | [deluluclover](https://github.com/deluluclover) |

## Responsibilities

- Theme & Performance Integrity: The system shall render retro Space Invaders-themed visual effects while maintaining optimized particle processing to minimize impact on game performance.
- Combat & Interaction FX: The system shall provide distinct visual feedback for combat interactions, including weapon firing trails, hit impacts, explosions, and player death/Game Over sequences.
- Progression & Environment FX: The system shall render particle effects such as sparks, smoke, and debris, along with transition animations for level completion and stage progression.
- Synchronization & Inter-Team Integration: The system shall provide synchronized, event-driven, reusable effect components that can be triggered by other systems through game logic.
- Player & Enemy Effects: The system shall provide visual effects for player and enemy interactions, including damage, destruction, and hit feedback.
- Effect Lifecycle: The system shall automatically manage the creation, animation, and removal of visual effects after their completion.

## Dependencies on Other Teams

1. Player & Enemy Ship Variety Team

Our Visual Effect System needs access to the player and enemy entities, including their position, sprite/ship type, hitbox, and destruction state. This allows us to correctly attach effects such as enemy hit flashes, explosions, and player-destruction effects to the corresponding ship. The enemy/ship information is also needed so that effects can be positioned correctly and remain consistent with different player and enemy variants.

2. Level Design System Team

Our Visual Effect System needs reliable wave/level start, wave completion, and level-transition events. These events allow us to trigger effects such as wave-clear animations, level-transition effects, and new-wave introduction effects at the correct point in the gameplay sequence. Without these events, the visual effects may be triggered at the wrong time or become disconnected from the actual game progression.

3. Sound Effects/BGM Team

Our Visual Effect System needs to coordinate with the Sound Effects/BGM Team for shared gameplay events such as player shooting, enemy hits, enemy destruction, and player damage/death. Visual and audio effects should be triggered from the same gameplay event and use consistent timing so that, for example, an enemy explosion and its explosion sound occur together. This coordination will help maintain consistent and responsive gameplay feedback
