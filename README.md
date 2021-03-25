# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **JANICE LIU**

Time spent: **6** hours spent in total

Link to project: (https://glitch.com/edit/#!/equinox-sudden-narwhal)

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each light up and play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern
- [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [x] Buttons use a pitch (frequency) other than the ones in the tutorial
- [ ] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [ ] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] "Game Instructions" button toggles between "info"(title of button) and "infoDialog" (displayed instructions) when clicked.

## Video Walkthrough

Here's a walkthrough of implemented user stories:
\Game Over: WIN
![player wins video walkthrough)](https://github.com/liujanice/light-and-sound-memory-game/blob/main/playerwins.gif)
\Game Over: LOSE
![player loses video walkthrough](https://github.com/liujanice/light-and-sound-memory-game/blob/main/playerloses.gif)
\Game Instructions
![game info video walkthrough](https://github.com/liujanice/light-and-sound-memory-game/blob/main/gameinstructions.gif)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.\

- https://www.w3schools.com/
  \I referred to the HTML, CSS, and JavaScript sections.
  \StackOverFlow
  For markdown formatting issues

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)\

   One of the features I added was a button to display game play, or the game instrcutions, since the game isn't entirely intuitive once you go on the website.
   In my game instructions dialog, my list of instructions initially where not left-aligned. I thought that I could left-align the text
   in the respective div-section, "instructDialog," that the corresponding buttons, "info" and "infoDialog," were in. However, that did not fix the issue that I had.
   From searching for the solution online, I found that I had to give CSS styling specifically on the `<ul> </ul>` tags for bulleted lists in HTML.
   I found a minor bug when I tested my code in the console. While going through the tutorial, I accidently declared a global variable twice: once in the beginning and again in a function.
   I would not have identified this error if I hadn't narrowed down where this error was occuring from independently testing each step in the code. Minor errors may be overlooked, but sometimes they are the main cause of bigger errors in yor code, which is why I prioritize testing my code frequently!

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)\
   In this brief project, I learned primarily about the front-end of web applications. This is the most JavaScript that I've used in any coding project that I've done so far. I found it very fun to implement, and
   I would like to dive deeper into web developement technologies and possibly explore the back-end of implementing websites. Since quality-testing applications is something I value doing, I wonder what other ways
   web developers test their applications other than through printing their `console.log()` statements when testing JavaScript. I wonder if they write unit tests, I wonder what are the most challenging aspects of web development that web developers run into often.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)\
   If I had a few more hours to work on this project, I would work on making the game more complex to better test a user's memory and stimulate their brain by helping them focus on small details and increase their attention. I've actually played the memory screening test by the Alzheimer’s Foundation of America, and I think this game could be a more casual version of that. I would add at least 2 more difficulty levels, with the
   current version of this game acting as Level One, or the Easy Level. On the medium-level of difficulty, I would add a fifth button and extend the sequence to be a pattern of 10 buttons.
   On the final level of difficulty, or the most difficult level, I would keep the fifth button, but the pattern would be eight steps. To test out a player's attentiveness to detail, I'm hoping to add similar images to each of the five buttons to see if the player can remember the order of the pattern if the images are a bit harder to distinguish from each other.
   The player can change levels by clicking on one of the three buttons: Easy, Medium, and Hard. I'm hoping to display these three buttons on the right-side of the website to add balance to the appearance of the website.
   Finally, I would add more instructions about these new additional game changes to my existing Game Instructions button. I strongly believe in making games all user-friendly to learn how to play.

## License

    Copyright [Janice Liu]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
