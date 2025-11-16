🔢 STM32 Keypad Password Lock (MM74C922 + Relay + Buzzer + LCD)

This project is a simple password-protected lock system built using an STM32F103C8T6 (Blue Pill) microcontroller.
A 4×4 keypad is connected using the MM74C922 keypad encoder, and the pressed key is decoded through GPIO pins.
When the correct password is entered, the relay turns ON.
If the password is incorrect, the buzzer activates.

The LCD displays masked password characters (*) and shows success or failure messages.

✅ Features

STM32 Blue Pill (STM32F103C8T6)

MM74C922 keypad encoder
→ Connected to PB3, PB4, PB5, PB6
(4-bit encoded output)

Interrupt-based key detection on PB0 (RISING edge)

LCD 16x2 for displaying messages

Relay output on PB7 (activates on correct password)

Buzzer output on PB8 (activates on wrong password)

Password is masked on the LCD

💻 Written using:

STM32CubeMX for configuration

IAR Embedded Workbench for compiling

📽️Working demo video available on YouTube :https://youtube.com/shorts/rqSY-HEGnnQ?feature=share 
