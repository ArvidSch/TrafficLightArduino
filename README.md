# Arduino traffic light(and more)

### Parts:
- 3x 150 Ω Resistor.
- 3x 3v Led (Red, yellow and green).
- Arduino UNO.
- Breadboard (optional).
 
> [!NOTE]
> Connect pin 2 to the red, pin 3 to the yellow and pin 4 to the green. (Or change the pin int's in the start)

> [!IMPORTANT]
> Dont forget the resistors, failiure to connect them can lead to the diode getting too much power and breaking.

> [!TIP]
> To change "mode" you can change the variables inside the parentheses to "on" or "off".
> ```C++
> void loop() {
>
>  trafficLight(on);
>  bounce(off);
>  refresh(off);
>}
>```



> [!IMPORTANT]
> B = 2  
> C = 3  
> D = 4  
> E = 5  
> F = 6  
> G = 7  
> A = 8  
> ![350-00027a (1)](https://github.com/user-attachments/assets/8f860dd7-fcd6-4269-9146-6df793b7b3b5)
