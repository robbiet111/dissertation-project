# Game Design Document

<img width="234" alt="Screenshot 2023-12-04 at 22 10 01" src="https://github.com/robbiet111/dissertation-project/assets/77496088/6e9c4be4-4c1e-4fa2-864b-ce653eec2364">


## Elevator Pitch
We're developing a soothing music game specifically for individuals dealing with brain disorders like Alzheimer's. With a stress-free approach and no fail states, the game kicks off with a foundational sound. Unlock the complete song by navigating through mini-challenges, including memory games, rhythmic tasks, and platforming elements. It's a serene and therapeutic exploration of music for a unique gaming experience.

## Overview
* Genre: Open-world Music-based

* Target audience: Individuals dealing with brain disorders like Alzheimer's

* Monetisation: Free

* Platforms & system requirements:  

    * Mid-range processor

    * 4GB RAM

    * Windows, macOS, or Linux
 
## Timeline
Sure, I've added a '*' before every line:

* Research (27/09/2023 - 02/10/2023):

   * Research on the project's topic.

   * Decision to use Unity for game development.

   * Initial exploration of Unity and music theory.

* Unity Exploration (02/10/2023 - 09/10/2023):

   * Continued Unity exploration.

   * Creation of a Unity project with movement and user controls.

   * Research on music-based projects and their interaction.

* Sound Interaction Examples (09/10/2023 - 16/10/2023):

   * Creation of two sound interaction examples in Unity.

* Title Screen and Camera System (16/10/2023 - 03/11/2023):

   * Game titled as 'HarmonyScape.'

   * Implementation of a 3rd Person Camera System.

   * Creation of a terrain, skybox, and a testing environment.

* User Study and Next Steps (13/11/2023):

   * Setup of a testing environment with trigger zones.

   * Conducted a hallway user study on game elements.

   * Discussion of study results and feedback from the advisor.

   * Setting objectives for the next week, including a design document.

* Implementation and Documentation (20/11/2023):

   * Implementation of boundaries to prevent falling off the terrain.

   * Research on the best way to implement world boundaries.

   * Discussion of hallway study results and planning for the upcoming weeks.

* Upcoming Focus (20/11/2023 - 27/11/2023):

   * Implementation of quality of life updates based on the user studies.

   * Introduction of natural guiders in the world to guide players.
   
   * Exploration of a mini-map system or at least a compass.

   * Implementation of design document.

## Backstory
In the captivating world of "HarmonyScape," you take on the role of Rillo, a little red blob from a distant galaxy. Rillo's home, where music binds everyone together, is under threat from disharmony. Following a mysterious portal, Rillo finds themselves on HarmonyScape, an island shaped by the essence of the alien's presence.

Guided by ancient spirits, Rillo explores meadows, snowy peaks, sandy shores, and hidden caves, encountering interactive elements that respond to their every move. As Rillo unravels the island's history, the ambient sounds and interactive features influence a continuous evolving melody.
Along the journey, Rillo befriends creatures embodying different aspects of the island's musical magic. Together, they face challenges, uncover secrets, and work to restore harmony. The island transforms into a living symphony, shaped by Rillo's actions and interactions.

## Gameplay

### Game Progression
The progression involves overcoming challenges and puzzles embedded in the environment. These could include rhythm-based puzzles, memory challenges, or platforming elements, aligning with the game's therapeutic design. Each successfully completed challenge unlocks new elements of the continuous music, further enriching the harmonious experience.

### Objectives
In the game's climax, Rillo ascends to a crescendo of harmony, unlocking the complete symphony of the island. This peak marks a moment of unity, where the disruptive force is triumphed over, restoring the celestial realm to a state of balance.

### Minigames

#### Guitar Minigame

##### Game Concept: Memory Strings
In the guitar-themed memory game each key represents a different note. The challenge lies in remembering and reproducing the correct order of notes to progress through the game.

##### Game Logic:
The game environment consists of five blocks, each symbolising different strings on a guitar. The player initiates the game by walking into the designated 'Start Zone' trigger.

##### Play Melodic Sequence:
A song comprising five unique notes is played.

##### User Interaction:
Players wait for their cue and, upon receiving it, are prompted to input notes by walking into the corresponding note block. Each note corresponds to a specific block, and players input their choice by jumping on the corresponding block.

##### Validation and Progress:
The game waits for a sequence of five notes from the player. If the player successfully reproduces the correct sequence, the game ends. Successful completion unlocks the guitar block, transforming it back into a trigger, so the player can acquire the guitar and is therefore added to the song.

##### Objective:
Challenge your memory and musical skills as you explore the rhythm of the game. Can you remember and play back the notes in the right sequence to master the melody?

##### Inspiration:
[Memory Game (Unity 3D)](https://learn.awesometuts.com/courses/199187/lectures/3034407)

## Characters

### Main Player: Rillo
In the vast expanse of the cosmos, Rillo was born on a distant celestial body known for its harmonious connection through the language of music. As a small, red blob alien, Rillo was different from others in their community. While their fellow beings thrived on creating harmonies, Rillo possessed a unique ability to feel and shape the very essence of the music around them.

<img width="144" alt="Rillo" src="https://github.com/robbiet111/dissertation-project/assets/77496088/678c604d-4dfb-4736-8f57-7caf8171451b">

## Location
The game is set on an island surrounded by water. The landscape features grassy areas, trees, and flowers, with dynamic variations such as peaks and valleys. Future development plans include adding snowy and sandy areas to enhance the diversity of the environment. Players will explore these changing landscapes as they progress through the game.

In the evolving island environment, upcoming additions will invite player interaction. Expect scattered elements like wind chimes, leaves, and fireflies, enhancing engagement. Each area will feature ambient sounds, such as rustling leaves or lapping waves, creating a sensory-rich experience. Unique rock formations will also be introduced, adding distinctive landmarks to the landscape.

[Terrain Design Inspiration](https://www.youtube.com/watch?v=zvrQM8rFLe0&list=PLxBP4SL7zdxq90JRM_cYP0hcYU1MOFr5n)
