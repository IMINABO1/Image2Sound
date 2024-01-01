## Description
The code takes an image as an input. If it is length or width is larger than 256 pixels, it resizes it to 256 pixels. 

It uses every pixel HSV value to make a sound.

### Hue
Hue (H) will be converted to one of the 12 frequencies of musical notes. <br />
    1: 16.35 ==    "C0" <br />
    2: 17.32 ==     "C#0" <br />
    3: 18.35 ==     "D0" <br />
    4: 19.45 ==     "E_flat0" <br />
    5: 20.6  ==     "E0" <br />
    6: 21.83 ==     "F0" <br />
    7:23.12  ==     "F# 0" <br />
    8: 24.5  ==    "G0" <br />
    9: 25.96 ==    "A_flat0" <br />
    10: 27.5 ==    "A0" <br />
    11:29.14 ==    "B_flat0" <br />
    12:30.87 ==    "B0" <br />

### Saturation

Saturation (S) will be converted to an octave between the first octave to 7th octave (Humans can't hear 0th Octave)

### Value
Value (V) will be converted to the amplitude of the note played.
<br /><br /><br />
Two pixels will be played at the same time which means two notes will be played at the same time. It will follow the 4-4 Time signature which means 4 pixels or 4 notes will played every second.
