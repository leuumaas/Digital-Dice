# Digital-Dice (Using CircuitVerse)
This project involves designing a digital dice display system using a 3x3 grid of LEDs (A, B, C, D, E, F, G, H, J) and utilizing only NAND gates to achieve the desired logic. The display corresponds to a 4-bit binary input, with each combination lighting up specific LEDs to represent different dice patterns.
Here is a detailed description of the design:

A B C

D E F

G H J

Binary Input and LED Mapping
0000 (0): No LEDs light up.
0001 (1): LED E lights up.
0010 (2): LEDs A and J light up.
0011 (3): LEDs A, E, and J light up.
0100 (4): LEDs A, C, G, and J light up.
0101 (5): LEDs A, C, E, G, and J light up.
0110 (6): LEDs A, D, G, C, F, and J light up.
0111 (7): LEDs A, C, D, E, F, G, and J light up.
1000 (8): LEDs A, B, C, D, F, G, H, and J light up.
1001 (9): All LEDs A, B, C, D, E, F, G, H, and J light up.
1010 (10): LEDs B, D, E, F, and H light up. (Plus sign)
1011 (11): LEDs D, E, and F light up. (Negative Sign- only the 2nd row)
1100 (12): LED J lights up. (Dot)
1101 (13): LEDs D, E, F, G, H, and J light up. (The last two row)
