# IR Obstacle Sensor (STM32F407)

## Description
This project uses an IR obstacle sensor with STM32F407.
When an object is detected, LEDs indicate the obstacle and a buzzer is activated.

## Hardware Used
- STM32F407 Discovery
- IR Obstacle Sensor (Active-LOW)
- Buzzer
- External LEDs with resistors

## Pin Configuration
- PA2  → IR Sensor OUT
- PD12 → Status LED
- PD14 → Status LED
- PD8  → Buzzer

## Logic
- Obstacle detected  → GPIO LOW (0)
- No obstacle       → GPIO HIGH (1)

## Notes
The IR sensor output is active-LOW by design.
