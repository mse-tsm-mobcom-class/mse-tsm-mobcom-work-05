# MSE TSM MobCom
## Hands-on of lesson 5
For slides and example code, see [lesson 5](../../../mse-tsm-mobcom/blob/master/05/README.md)

> *Note: Do not work on this repository right away.*<br/>
> *[Check existing forks to find the specific repository for your class.](../../network/members)*

### a) Button-triggered LED, 15'
* Use blue onboard LED, pin 4, and the button, pin 7.
* Combine the previous examples to switch the LED.
* Or wire a LED to Grove port D2 and a button to D4.
* Use the [pin mapping](https://github.com/tamberg/mse-tsm-mobcom/wiki/Grove-Adapters#mapping) to adapt the pin numbers.

### b) State machine, 15'
* Copy and complete the code of the state machine.
* Make sure it works, with a button and LED setup.
* Change it to switch off only, if the 2nd press is long.
* Let's define long as > 1s, measure time with [millis()](https://www.arduino.cc/reference/en/language/functions/time/millis/).

### c) Kitchen timer, 15'
* Design a kitchen timer to the following specification:
* Displays a countdown to 0, in minutes and seconds.
* Let's the user reset to _00:00_, enter a new timespan.
* Allows the user to start the countdown at _mm:ss_.
* Starts buzzing if the countdown reaches _00:00_.
* Use a state machine, get the time with [millis()](https://www.arduino.cc/reference/en/language/functions/time/millis/).

### d) Homework, max. 3h
* Implement or finish the kitchen timer you designed.
* Document the timer state machine (PDF or PNG).
* Commit the code and docs to the hands-on repo.
* Bring the (working) timer to the next lesson.
