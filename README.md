# KinderKode
Winning submission for Apple's WWDC 2021 Swift Student Challenge
## About
I submitted KinderKode, a Swift playground intended to help early elementary teachers and young students near “Kinder”garten, especially during virtual learning due to COVID-19. This idea was formed due to my mother being a kindergarten teacher and is actually used daily in her virtual classroom.
## Technical Description
The welcome page simply introduces how to use the playground and showcases some information in the about section. It is powered via UI View Controllers, Core Graphics, Sprite Kit, and AV Foundation for the accessible speech reading, as is most of the playground. The Blending Board features a technique to introduce reading words while paying attention to the sounds each letter makes. It features the same spoken AV Voice Synthesizer to read the instructions to those learning to read, true randomization of the letters in each virtual pile, and arrays with searching to determine if the randomly generated word is real or nonsense. The Scavenger Sounds page features an activity to help children independently recognize that letter sounds are all around them. It features a UI Button, randomization of an array containing the English alphabet, and utilization of the device camera to take a picture of the found item with. Lastly, the Math Mat page has a number line to help students visualize their addition as they solve. I created a function that determines a math problem and says it aloud to the user. The current problem is temporarily stored and the speaker icon can be clicked to have it repeated. The user can then drag the Core Graphics and Sprite Kit counter with their finger or Apple Pencil to solve, imitating how they would normally use a physical counter. I also used Sprite Kit buttons for the numbers to receive the answers and act in a recursive way by generating the next problem once the correct answer is given. 
## Demonstration
Watch the screen recording on YouTube: https://www.youtube.com/watch?v=z6NKXlI0gKY
## Installation
This playground can be run in the Swift Playgrounds app on iPadOS or MacOS, though it was designed for iPadOS. 
1. Download Swift Playgrounds app
2. Download KinderKode.zip
3. Open and run the playground
