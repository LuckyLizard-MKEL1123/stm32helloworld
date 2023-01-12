# Milestone3.1: stm32helloworld
Group Name: **Lucky Lizard** :lizard:

Group Member: 
1. **Andi Nur Asyikin Binti Andi Zainuddin**
2. **Lim Yong Chuan**
3. **Nur Fatini Binti Isa**

## Ojective
Interface the UART and one more devices using the STM32F4 ports
## Equipment
- [x] Board used: **NUCLEO-F411RE**
- [x] Software used: **STM32CubeIDE**
- [x] Breadboard
- [x] Jumper
- [x] DIP switch
## Software
- [x] PuTTY
## Procedure
1. In this milestone, the PuTTY terminal is used as the output display of the board.
2. The source code [stm32helloworld.c](https://github.com/LuckyLizard-MKEL1123/stm32helloworld/blob/main/stm32helloworld.c)
3. The input from the 4-bit DIP switch be read once once the push button is pressed.
4. Both the DIP switch and push button only requires GPIO interfacing.
5. However, the PuTTY terminal requires interfacing to the board through UART protocol which is provided by the STM32 Cube IDE.
6. In order to display the value, HAL_UART_Transmit function to transmit the message string to the PuTTY terminal.
7. he function takes the huart2 variable as the first argument, the message string as the second argument, the length of the message string as the third argument and the delay as fourth argument.


## References
1. https://deepbluembedded.com/stm32-debugging-with-uart-serial-print/
2. https://elearning.utm.my/22231/pluginfile.php/505626/mod_resource/content/0/10-serial%20communications%20.pdf
