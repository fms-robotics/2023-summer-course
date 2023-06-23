# IT Lab Course Structure

## Introduction to Software Engineering and Arduino

### 3/7

-   Morning Session
    -   Get started with Visual Studio Code
    -   Learn how to correctly wire a breadboard
    -   Upload programs using [PlatformIO](https://platformio.org/) and
        [C++](https://github.com/adrianchong518/Mini-Robocon-2018/blob/master/auto-control/src/sample.cpp)
    -   Introduce concepts of digital and analog signals
    -   Practice the [LED Blink](https://docs.arduino.cc/built-in-examples/basics/Blink) example to
        turn an LED on and off every second

-   Afternoon Session
    -   Get started with digital input using buttons
    -   Introduce variables and its naming style
    -   Use `Serial.println` to output values

### 4/7

-   Learn about control flow by drawing state diagrams and using iterations
    -   **Example Task**: Turn on LED only when both buttons are pressed
-   Gain an understanding of analogue input and PWM (Pulse Width Modulation) output
    -   Learn to use `analogWrite` and `analogRead`
    -   Learn to use potentiometers
    -   Linear mapping

### 5/7

-   Learn non-blocking design patterns
    -   Time-keeping using `millis()`
    -   Simple "state machine" with Boolean flags
    -   **Example Task**: Multiple blinking LEDs with varying intervals
    -   **Example Task**: Button debounce
