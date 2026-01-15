# Chess Microcontrollers
Tinkering with electronic chess games.  I'm am useless at chess but it still fascinates me.<br>

Related videos:
- [LogiChess Part 1](https://youtu.be/34F9DbmAjUU)
- [LogiChess Part 2](https://youtu.be/Y_kRFhx9leI)

## [Tandy 1650](/Tandy_1650_Chess)
Information about the Tandy 1650 Computerised Portable Sensory Chess game.  It uses the SciSys TE1 which is 4KB LogiChess implemented on an Hitachi HD6301V microcontroller.<br>

![Tandy 1650 chess](/Tandy_1650_Chess/Tandy_1650_Chess.png)

## [VIC-20 Chess Co-processor](/VIC-20_LogiChess)
I had a thought to re-use the MCU in the Tandy 1650, the SciSys TE1 implementing 4KB LogiChess, as a "co-processor" for vintage 8-bit computers, for example the Commodore VIC-20.<br>

This isn't the same as simply having the game code on a cartridge as the VIC's CPU is still running the code.<br>

I was wondering if it would be interesting to have a dedicated microcontroller doing the "chess processing".  It might be beyond my capabilities but this is how you learn new things.<br>

Ultimately it might be easier to just use an ATmega MCU with a chess program running on it.  But let's see.

## [LogiChess-Arduino Testing](/LogiChess-Arduino_Testing)
As part of my work on trying to get LogiChess MCU working with a VIC-20, I will first do some investigation on how to interface with the SciSys TE-1 by using an Arduino.  If I can get that working then it might give me some idea how to get it working on the VIC.<br>

## [Chess Keypad](/Chess_Keypad)
In conjunction with the Arduino interfacing, I'm creating a keypad to replicate the original Tandy 1650 hardware.<br>

So ...
- Step 1: get the SciSys TE1 working with my chess keypad and the Arduino logging information
- Step 2: get the Arduino (in place of the VIC-20) working with the SciSys TE1
- Step 3: get the VIC-20 working with the SciSys TE1

![Chess keypad 3D](/Chess_Keypad/Chess_Keypad_for_Tandy_1650_3D.png)

