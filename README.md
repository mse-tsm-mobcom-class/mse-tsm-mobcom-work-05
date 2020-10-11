# MSE TSM MobCom
## Hands-on of lesson 5
For slides and example code, see [lesson 5](../../../mse-tsm-mobcom/blob/master/05/README.md)

> *Note: Do not work on this repository right away.*<br/>
> *[Create your personal copy by clicking this GitHub Classroom link](https://classroom.github.com/a/TODO).*

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

### c) Humidity alert, 15'
* Design a state machine with this specification:
* Button press sets humidity += 10% as threshold.
* Red LED turns on, as long as monitoring is active.
* Once threshold has been crossed, blue LED turns on.
* Button confirms alert, red led turns on 1 s, then off.

### d) Homework, max. 3h
* Implement the humidity alert you designed before.
* Document the device state machine (PDF or PNG).
* Commit the code and docs to the hands-on repo.
* Test your device in a humid environment<sup>*</sup>.

<sup>*</sup>Never submerge or sprinkle electronics.
