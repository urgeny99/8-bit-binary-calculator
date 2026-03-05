# 8-bit-binary-calculator
## This is an 8-bit adder that adds two 8-bit numbers together (255+255).

### How it works and what parts I used:




- 4x quad XOR gates (SN74HC86)
- 4x quad AND gates (SN74HC08)
- 2x quad OR gates (SN74HC32)
- 2x DIP switch x08
- 11x Decoupling capacitors 
- 9x single color LEDs for showing the output
- 25x resistors for setting switches Low and protecting LEDs (9x 1k; 16x 100k)
- 1x screw terminal for connecting to power

#### HOW IT WORKS

The adder works by having 8 + 8 inputs (A0-A7; B0-B7) and taking them into half and full adders.
Use the DIP-switches to set the input values, and read LED output.
The Half adder looks like this | And this is a Full adder 
:------:|:---------:
<img width="381" height="266" alt="image" src="https://github.com/user-attachments/assets/b57e6bd5-c22d-472a-a64f-65bf5d39abb2" /> | <img width="904" height="415" alt="image" src="https://github.com/user-attachments/assets/e7edaca3-380e-4c40-aa0c-01b11939539b" />





<img width="1111" height="360" alt="image" src="https://github.com/user-attachments/assets/2f51c066-2424-44aa-8b8b-10291b6b52c6" />


# BOM

<img width="1112" height="239" alt="image" src="https://github.com/user-attachments/assets/5daa0c12-6f2e-45a7-8d25-965162176fa3" />


Shematic   | PCB | 3D model
:-------------:|:-----------:|:-----------:
<img width="1353" height="902" alt="image" src="https://github.com/user-attachments/assets/c9ae9e34-aa8d-421f-8db8-f35652385722" /> | <img width="930" height="869" alt="Screenshot 2026-03-05 144015" src="https://github.com/user-attachments/assets/89017653-c13f-4084-aac1-7c77383a5ecb" /> | <img width="935" height="910" alt="Screenshot 2026-03-05 144004" src="https://github.com/user-attachments/assets/313a1075-bfa0-4bb5-ba57-e6ec4cd45fe9" />
