# Ring Fit Mega Man

![RingFit_MegaMan](img/RingFit_MegaMan.jpg)

![architecture](img/architecture.drawio.svg)

Instruction to play Mega Man (known as Rockman in Japan) using Ring Fit Adventure controller for exercise

## How to play Mega Man in Ring Fit way

![RingCon](img/RingCon.jpg)

### Option 1 (Recommended):

- Programmed in [ringfit_megaman_squatbuster.gpc](https://github.com/Minyus/RingFit_MegaMan/blob/master/ringfit_megaman_squatbuster.gpc).
- Squat to fire a Mega Buster shot.
- Tilt the Ring-Con to left/right to move.
- Tilt the Ring-Con to backward (lift) slightly to climb up ladders.
- Tilt the Ring-Con to forward (put down) to climb down ladders.
- Tilt the Ring-Con to backward (lift) or press button A or B to jump. Recommended to hold the Ring-Con at the positions above the grips to press a button.
- Tilt the Ring-Con to forward (put down) and press button A or B to slide (action introduced in Mega Man 3).
- [Unsupported] Charge shot (action introduced in Mega Man 4)

### Option 2: 

- Programmed in [ringfit_megaman_squatjump.gpc](https://github.com/Minyus/RingFit_MegaMan/blob/master/ringfit_megaman_squatjump.gpc).
- Squeeze or pull the Ring-Con to fire a Mega Buster shot.
- Tilt the Ring-Con to left/right to move. 
- Tilt the Ring-Con to backward (lift) to climb up ladders.
- Tilt the Ring-Con to forward (put down) to climb down ladders.
- Tilt the Ring-Con to backward (lift) while squatting to jump. You will jump as high as the Ring-Con tilted backward.
- Tilt the Ring-Con to forward (put down) while squatting to slide (action introduced in Mega Man 3).
- [Unsupported] Charge shot (action introduced in Mega Man 4)


## Instruction to set up

### Disclaimer

I shall not be liable for any damage to your body or hardware/software products you use following the instruction below.
The following steps worked for me (after struggling), but I can not guarantee in other cases.

0. Prepare hardware

    - [Nintendo Switch, Dock, and Joy-Cons](https://www.nintendo.com/switch/)
    - [Ring-Con and leg strap that comes with Ring Fit Adventure](https://www.nintendo.com/games/detail/ring-fit-adventure-switch/)

    - [Titan Two](https://www.consoletuner.com/products/titan-two/)
    - [Titan Expansion Kit](https://www.consoletuner.com/products/titan-two/) (to connect Joy-Cons with Titan Two via Bluetooth)

    - PC (Windows 64bit (10, 8.1, 7) or Mac (OS X 10.13+) computer)
    - Additional Micro-USB cable (A Micro-USB cable comes with Titan Two, but you will need one more to connect both PC and 
    Nintendo Switch Dock. I could use an old Micro-USB cable used to charge my old Android smart phone.)

1. Purchase and download [Mega Man Legacy Collection](https://www.nintendo.com/games/detail/mega-man-legacy-collection-switch/) to your Nintendo Switch.

2. Turn on "Pro Controller Wired Communication" in Nintendo Switch following the [instruction](https://www.nintendo.co.uk/Support/Nintendo-Switch/How-to-Enable-Disable-Nintendo-Switch-Pro-Controller-Wired-Communication-1516284.html) to use Titan Two later.

3. Download and Install [Gtuner IV](https://www.consoletuner.com/downloads/?) to your Windows or Mac computer.

4. Install Titan Expansion Kit to Titan Two and connect to your PC (using "PROG" connector of Titan Two) following the [instruction](https://www.consoletuner.com/wiki/index.php?id=t2:expansion_kit). Don't forget [First Time Configuration](https://www.consoletuner.com/wiki/index.php?id=t2:expansion_kit#first_time_configuration)!

5. Pair up the 2 Joy-cons with Titan Two following [instruction](https://www.consoletuner.com/wiki/index.php?id=t2:usage_guides:controllers:switch). You may need to sleep Nintendo Switch to avoid the Joy-Cons paired up with Nintendo Switch unexpectedly. 

6. Download and Install a GPC script ([ringfit_megaman_squatbuster.gpc](https://github.com/Minyus/RingFit_MegaMan/blob/master/ringfit_megaman_squatbuster.gpc) or [ringfit_megaman_squatjump.gpc](https://github.com/Minyus/RingFit_MegaMan/blob/master/ringfit_megaman_squatjump.gpc)) to a memory slot (e.g. 1) of Titan Two following the [instruction](https://www.consoletuner.com/wiki/index.php?id=t2:gpc_scripting).

7. Connect Titan Two to your Nintendo Switch Dock (using "Output" connector of Titan Two). Use an additional Micro-USB cable if you have so you can monitor the signals from Joy-Cons in Gtuner IV application. Otherwise, you need to disconnect the Micro-USB cable that connects Titan Two and PC.

8. Set the number indicated by LED on Titan Two to 0 by pressing the DOWN/UP button and start Mega Man in Nintendo Switch.

9. Set the number indicated by LED on Titan Two to the memory slot number (e.g. 1) to enable the installed gpc script.

10. Install the 2 Joy-Cons to Ring-Con and leg strap, respectively.

11. Enjoy!

## Other games to play with Ring Fit Adventure controller

- [Mario Kart X Ring Fit Adventure](https://www.controllerbend.com/mariokart-ring-fit.html)
- [Animal Crossing X Ring Fit Adventure](https://www.controllerbend.com/animalcrossing_ringfit.html)
- [Zelda: Breath of the Wild X Ring Fit Adventure](https://www.controllerbend.com/ringfitbotw.html)

## References for gpc scripting

- https://www.consoletuner.com/wiki/index.php?id=t2:gpc_language_reference
- https://www.consoletuner.com/wiki/index.php?id=t2:gpc_scripting:examples_1
