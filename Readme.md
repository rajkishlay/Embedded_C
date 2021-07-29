# Embedded C Mini Project

# Activities Description

|Activity|Description|
|:--:|:--:|
|Activity 1| Blink the LED when the passenger is in the seat and the heater is pressed|
|Activity 2| Convert the analog signal from the temperature sensor to the digital value|
|Activity 3| Generate the PWM signal according to the converted digital value|
|Activity 4| Send the temperature value to the serial monitor using UART protocol|

# Assumptions
* Switches are used to the realize the passenger in the seat and the press of the heater
* The temperature sensor is realized using the potentiometer

# Activity 1

## In Action

|Case 1: When Both Switches are OFF|Case 2: When Switch 1 is OFF and Switch 2 is ON|
|:--:|:--:|
|![image](https://github.com/rajkishlay/Embedded_C/blob/main/simulation/Switch_OFF_OFF.PNG)|![image](https://github.com/rajkishlay/Embedded_C/blob/main/simulation/Switch_OFF_ON.PNG)|

|Case 3: When Both Switch 1 is ON and Switch 2 is OFF|Case 4: When Both Switches are ON|
|:--:|:--:|
|![image](https://github.com/rajkishlay/Embedded_C/blob/main/simulation/Switch_ON_OFF.PNG)|![image](https://github.com/rajkishlay/Embedded_C/blob/main/simulation/Switch_ON_ON.PNG)| 

# Activity 2 

## In Action

![image](https://github.com/rajkishlay/Embedded_C/blob/main/simulation/ADC.PNG)

# Activity 3

## In Action

|Case 1: Duty Ratio = 0.2 |
|:--:|
|![image](https://github.com/rajkishlay/Embedded_C/blob/main/simulation/20%25DutyRatio.PNG)|

|Case 2: Duty Ratio = 0.4|
|:--:|
|![image](https://github.com/rajkishlay/Embedded_C/blob/main/simulation/40%25DutyRatio.PNG)|


|Case 3: Duty Ratio = 0.7 |
|:--:|
|![image](https://github.com/rajkishlay/Embedded_C/blob/main/simulation/70%25DutyRatio.PNG)|

|Case 4: Duty Ratio = 0.95|
|:--:|
|![image](https://github.com/rajkishlay/Embedded_C/blob/main/simulation/95%25DutyRatio.PNG)|

# Activity 4

## In Action

|Case 1: Temperature = 20 |
|:--:|
|![image](https://github.com/rajkishlay/Embedded_C/blob/main/simulation/temp%3D20.PNG)|

|Case 2: Temperature = 25|
|:--:|
|![image](https://github.com/rajkishlay/Embedded_C/blob/main/simulation/temp%3D25.PNG)|


|Case 3: Temperature = 29 |
|:--:|
|![image](https://github.com/rajkishlay/Embedded_C/blob/main/simulation/temp%3D29.PNG)

|Case 4: Temperature = 33|
|:--:|
|![image](https://github.com/rajkishlay/Embedded_C/blob/main/simulation/temp%3D33.PNG)|


# Final Working
![image](https://github.com/rajkishlay/Embedded_C/blob/main/simulation/Final_Working.PNG)



