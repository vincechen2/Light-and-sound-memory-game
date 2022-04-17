# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Vincent Chen**

Time spent: **2** hours spent in total

Link to project: (https://glitch.com/edit/#!/light-and-sound-game-pre?path=index.html%3A1%3A0)

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](gif1-link-here)![ezgif com-gif-maker-12](https://user-images.githubusercontent.com/68205883/163725118-080cb8e8-1c93-4b7c-aa19-74d5642c4c12.gif)

![](gif2-link-here)![ezgif com-gif-maker-13](https://user-images.githubusercontent.com/68205883/163725142-bb3a0ab8-8971-427d-a9a8-7f2f4490f512.gif)

![](gif3-link-here)![ezgif com-gif-maker-14](https://user-images.githubusercontent.com/68205883/163726080-777a7b3a-c360-4b64-99cf-150e78d9ae66.gif)

![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
StackOverflow, GeeksforGeeks

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
I had some experience with web development prior to this submission, but this submission introduced new concepts such as adding sound on click, so that portion was definitely the most challenging and interesting, since it was something I hadn’t seen before. Initially I was stumped, because I didn’t know of any CSS or Javascript functionality to play sound. I was able to overcome this issue with the help of the CodePath resources. Through CodePath, I was able to learn about the AudioContext library and how to utilize it to play set frequencies. CodePath provided a code snippet to play sound, and by working backwards with that code snippet, I was able to gain a better understanding of the AudioContext library.
   
3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I am interested in the lower-level details of how Javascript libraries are able to provide functionalities such as playing sound. I also want to learn more about best practices in web development, because seeing as there are many ways to achieve the same thing in web development, I would like a standard to follow when coding. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had more time to work on this project, I would like to add additional features such as a difficulty slider, and a leaderboard. To implement the leaderboard, a backend would be needed, but I believe the project would be far more interesting if you’re able to compete against other users. To implement the leaderboard feature, many other features would also have to be implemented. For instance, users would have to be able to create profiles, and a way to calculate score would have to be implemented. With the addition of user profiles, I would also like to implement a separate page that allows a user to view their personal stats. 


## Interview Recording URL Link

[My 5-minute Interview Recording] https://drive.google.com/file/d/1Xa51ziBZZTakVgzoe9jHpZr97UKzv1wD/view?usp=sharing


## License

    Copyright [Vincent Chen]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
