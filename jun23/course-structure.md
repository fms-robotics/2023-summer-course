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
-   Hardware related concept: button bouncing

## Land-based Robot Controlling

-   **Target**: Program the provided robot to complete a simplified version of
    [BottleSumo](https://www.robofest.net/images/2223/BottleSumo2023v22_Final.pdf)
-   Students are to be grouped into teams of 2-3
    -   This is to begin the process of team communication and cooperation

### Hardware required

-   1 "Mecanum Robot" for each team

### 6/7

-   Build the land-based mecanum robot used in the course
-   Learn how to program a tank-drive
-   Integrate joystick control

### 11/7

-   Gain an understanding of communication protocols
    -   I2C
    -   Serial
-   Learn to use TFMiniS with I2C (`Wire.h`) and provided library
-   **Task**: Self-rotate until finding the bottle

### 12/7

-   Continue the tasks on 11/7
-   Complete the following task:
    -   A previously unknown "starting task"
    -   Find the bottle
    -   Push over the bottle
