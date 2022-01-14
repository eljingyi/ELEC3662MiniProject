# Mini Project
Schematic Diagram 
-----------
![image](https://user-images.githubusercontent.com/81463065/149384335-0d63139d-46d4-454b-8ca9-4d14a37bda81.png)
<details><summary>CLICK ME TO ACCESS THE PDF VERSION OF THE SCHEMATIC DIAGRAM</summary>
<p>

[Schematic diagram.pdf](https://github.com/eljingyi/ELEC3662MiniProject/files/7864959/Schematic.diagram.pdf)
</p>
</details>

Connection table 
-----------

**KEYPAD**
|Component pin|Microcontroller pin|
|:---:|:---:|
|COL 1|PD0|
|COL 2|PD1|
|COL 3|PD2|
|COL 4|PD3|
|ROW 1|PE0|
|ROW 2|PE1|
|ROW 3|PE2|
|ROW 4|PE3|

**LCD SCREEN**
|Component pin|Pin No.|Microcontroller pin|
|:---:|:---:|:---:|
|VSS |1|PD0|
|Vdd |2|5|
|Vo |3|Middle pin of the potentiometer (other pins connected to 5V and GND)|
|RS|4|PA3|
|R/W |5|GND|
|E |6|PA2|
|DB0 |7|-|
|DB1 |8|-|
|DB2 |9|-|
|DB3 |10|-|
|DB4 |8|PB0|
|DB5 |8|PB1|
|DB6 |8|PB2|
|DB7 |8|PB3|
|A|15|VBUS(5V)|
|K|16|6.67Ohms resistor (I used 10 ohms for this mini-project) + GND|

![photo_2022-01-14_13-46-37](https://user-images.githubusercontent.com/81463065/149458143-98703cb2-6b23-44a7-abba-6bb1eb8ee299.jpg)
*I've tied up the wires so that it looks less messy*

Calculator Functions 
-----------

| Function      | Function description |
| ------------- | -------------------- |
| Plus (`+`)      | Calculating the sum  |
| Minus (`-`)     | Calculating the difference  |
| Divide (`/`) | Calcuating the division|
| Multiplication (`x`)| Calculating the multiplication|
| Times ten to the power (`E`)| Calculating the value of |
| Decimal point (`.`)| Allowing for decimal calculations|
| `Ans` | Stores the previous calculated answer|
| `Shift` | To access the other functions (when shifted, the screen would display '^')|
| `=`| To calculate the equation entered|
| `Exit`| To leave the Calculator Page |

3. Other functions 

| Function      | Function description |
| ------------- | -------------------- |
| `Delete` | To delete one character |
| `Clear` | To clear the whole screen|
| `Register` | Store the password and the name of the user| 
| `Login` | To login into an account that was previously registered|

Keypad
-----------

**Keypad layouts**

| Original Keypad Layout | Keypad Layout (Enter `Password`) | Keypad Layout (Enter `name`)| Keypad Layout (Calculator)|Keypad Layout (Calculator `shift` activated)|
| :---:| :---:| :---:| :---:| :---:|
|![image](https://user-images.githubusercontent.com/81463065/149389449-52396d80-a20c-4e9f-a3bf-6b0b5644ede9.png)|![image](https://user-images.githubusercontent.com/81463065/149507994-aa19591e-78a1-4ba1-bcf9-59d25339e0f7.png)| ![image](https://user-images.githubusercontent.com/81463065/149394983-c8d1818f-817d-44b5-92d3-8529f486e3bb.png)| ![image](https://user-images.githubusercontent.com/81463065/149393873-570fc1e1-17eb-4763-ab84-d2d95002a58c.png)| ![image](https://user-images.githubusercontent.com/81463065/149392702-4978b4a7-d9cc-4534-93f9-f5c0dd385952.png)|


**Login**

| Functionality | Keypad Layout | Keypad Description|
|------| :---:|---|
| Select Options | ![image](https://user-images.githubusercontent.com/81463065/149394739-44443caa-ca21-44d2-9f41-eed61dd04c45.png) | To choose and select the options displayed on the screen| 
| Enter `Password` | ![image](https://user-images.githubusercontent.com/81463065/149507994-aa19591e-78a1-4ba1-bcf9-59d25339e0f7.png)| The stored password is numeric, therefore user can enter their password using the keypad and proceed by pressing 'Enter"| 
| Enter `name` | ![image](https://user-images.githubusercontent.com/81463065/149394857-85b37910-4732-4f9d-a584-53779a911d92.png) |The user can enter their names using the keypad, each characters could be accessed and will be selected everytime the user press '#'.|

**Calculator**

| Functionality | Keypad Layout |Keypad Description|
|------| :---:|---|
|Not shifted| ![image](https://user-images.githubusercontent.com/81463065/149395271-f3e538ff-b514-45f6-a85b-10b48d2d3343.png) | When no values are pressed, when the `=/EXIT` button is pressed, there would be a prompt to ask if the user wants to leave the calculator page.|
|Shifted | ![image](https://user-images.githubusercontent.com/81463065/149392702-4978b4a7-d9cc-4534-93f9-f5c0dd385952.png)| The symbols highlighted in grey could only be accessed after the shift button is pressed, which would be indicated by `^` on the LCD display screen|

*The functions of each symbols in the keypad are explained in section 1*

The following are some examples of my calculator alongside with a scientific calculator to prove that the calculation is accurate for both integer values and decimal values 

| Multiplication| Sum | No operators|
|:---:|:---:|:---:|
|![multiplication](https://user-images.githubusercontent.com/81463065/149521272-7c01a0cc-6110-41a7-8d27-2a190900c4f4.jpg)|![sum](https://user-images.githubusercontent.com/81463065/149521383-be26bd70-f0ea-4908-a25b-f9db00e0056e.jpg) | ![no operators](https://user-images.githubusercontent.com/81463065/149521302-eb6d5ad1-f345-4bcd-a3ed-47a3c3d3e8c2.jpg)|


| Multiple operators example 1 | Multiple operators example 2 | No operators|
|--|--|--|
|![two operators](https://user-images.githubusercontent.com/81463065/149521455-ee03a4a4-4037-489d-8c03-2de6a61c6fe4.jpg)| ![two operations](https://user-images.githubusercontent.com/81463065/149521459-d33dd381-bb2d-47d6-b1a5-507fb15e535b.jpg)| ![undefined](https://user-images.githubusercontent.com/81463065/149522724-381f9c60-bd6a-45c7-bc09-3974ee8e1fc6.jpg)|


Video demonstration of calculation:
https://user-images.githubusercontent.com/81463065/149522809-88304d37-1817-48f5-a2e0-0837e2515d71.mp4




LED Lights
-----------

LED lights of the microcontroller is used to indicate which page user is currently accessing 

| Colour      | Description |
| ---------- | ----------- |
| `Blue` | User to input information (password or name) | 
| `Red` | Wrong password | 
| `Green` | Login / Registration is successful|
| `Pink` | Main Menu |
| `White` | Calculator is activated |

| Blue LCD (User information) | Wrong Password (Error)| Correct Password (Sucessful) | Profile page (Pink) | Calculator (White)|
|-----------| -----------|---|---|---|
|![photo_2022-01-14_06-39-38 (2)](https://user-images.githubusercontent.com/81463065/149475900-bccbdf85-78f3-4bf3-826b-eb1e7f2bb5e6.jpg)| ![photo_2022-01-14_06-39-40 (2)](https://user-images.githubusercontent.com/81463065/149475343-ec78137d-dcd8-4306-b8eb-8e8ea8d359e3.jpg) |![photo_2022-01-14_06-39-41](https://user-images.githubusercontent.com/81463065/149475583-23298a70-d955-47c0-90b9-6e68f621fde2.jpg)|![photo_2022-01-14_06-39-42](https://user-images.githubusercontent.com/81463065/149476409-04d04e94-304e-4f97-bf9e-b1d2218e7be5.jpg)|![photo_2022-01-14_20-38-12](https://user-images.githubusercontent.com/81463065/149516774-c5897e21-45ec-4910-9d04-354e2f31ed53.jpg)|

Graphics 
--------

Password 

![password](https://user-images.githubusercontent.com/81463065/149518657-cc054e34-5ee2-4043-a9cb-f6699df56420.gif)

Set new password

![Set new](https://user-images.githubusercontent.com/81463065/149518654-da31ccb1-3a51-4d28-93e0-ebd64a7595f1.gif)

Input Name

![name](https://user-images.githubusercontent.com/81463065/149520134-602e9f5b-b709-423a-8f8f-c6c8f7d49c1a.gif)

Loading

![loading](https://user-images.githubusercontent.com/81463065/149524842-a6029d1b-ca83-40a9-aab1-f994b8a1a3fb.gif)

Shutting Down

![shutting dow](https://user-images.githubusercontent.com/81463065/149524864-a0cf7867-bc4c-4cc0-ab01-7996caf334ce.gif)

Contrast

![contrast](https://user-images.githubusercontent.com/81463065/149519056-b6ed77bd-3edb-4ee1-a985-b2421e6e9a23.gif)|

