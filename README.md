# Bowling Challenge

### Approach

I made several attempts at this challenge as I found it was very easy to add small features which very quickly got very out of control. The brief states that this is a one-player game, so I took the view that there did not need to be any notion of players or any real reason to score the game after each bowl, since there is no concept of "winning." The game is played out and the score can be calculated when the game is finished.


### Testing

This bowling challenge was built using TDD. The testing framework used is Jasmine which is included in the repo. To run the tests in the browser, navigate to the root directory and open ```SpecRunner.html``` in your browser.


### Usage

There is no GUI so usage is 100% from the console. Copy the code into the Chrome DevTools console or use your own preferred method.

To start a new game:

``` game = new Game(); ```

To bowl and hit ```n``` number of pins:

``` game.bowl(n); ```

To calculate the final score:

``` game.calcScore(); ```

The game won't let you knock down pins that are already knocked down (it will throw an error) and it will reset the pins after each frame is complete.


### TODO

* Proper encapsulation.
* Use SpecHelper.
* Split out feature tests and unit tests into separate files.
* Separate responisbilities into multiple objects.
* More explicit end-of-game handling.
* Frontend GUI.


### Technologies used

* JavaScript
* TDD (via Jasmine)


### Original instructions
[via the power of Git](https://github.com/forty9er/10-pin-bowling-scores/blob/8d9c3f3fc007d0de596a366e647329ee5b358cda/README.md)