# Sukhoi Board – Build Journal

This is a raw log of the grind, chaos, wins, and minor meltdowns that happened while building the Sukhoi Board. Five days of PCB pain, schematic stares, and CAD caffeine loops. If you're reading this and thinking of building your own board, may this journal help you feel less alone in the madness.

---

## Day 1 – July 6  
**Time Spent:** 4 hours

Kicked things off with the schematic. Started from a blank KiCad canvas because I’m allergic to templates. Placed the MCU, resistors, diodes, and all the usual suspects. Wiring the matrix gave me a little existential crisis because ortholinear means everything is clean until it’s not. Kept checking the datasheet of the Elite-C like it owed me money. Also made space for the rotary encoder and reset switch which felt like stuffing a sofa into a suitcase. Ended the session with a basic sanity ERC check, which obviously screamed at me, but it’s a start.



![Screenshot 2025-07-10 010025](https://github.com/user-attachments/assets/d85f09d7-2de2-4954-b7d1-8249315f979e)





---

## Day 2 – July 7  
**Time Spent:** 4-5 hours

Moved into PCB layout and instantly got hit with pin placement regret. Had to reroute the entire column setup because I flipped the rows and didn’t realize until traces started looking like spaghetti. Switched to grid view, slapped the MCU dead center, and tried to keep traces symmetrical. Also made room for the encoder up top and slightly offset the OLED header. Routed power lines with thicker traces because I’ve learned from past drama. Used zones for GND and VCC because I like pretending I know what I’m doing. No silkscreen yet, just vibes and vias.

![image](https://github.com/user-attachments/assets/b657111f-60eb-4b85-b057-cee0d9574ba2)

![image](https://github.com/user-attachments/assets/c3a1602e-1de7-4a63-9b17-6a87d04b8993)

---

## Day 3 – July 8  
**Time Spent:** 6 hours

This was the CAD day. Got into Fusion 360 and built the bottom case first. Made the walls extra chunky for that clean minimalist feel but added subtle lines to hint at fighter jet fuselage panels. The top plate got a centered Sukhoi logo that’s shallow engraved, which took way too long to align. Played around with the USB port cutout until it stopped clipping through the case. The encoder needed a custom cavity and that honestly took a while to model properly.

![image](https://github.com/user-attachments/assets/48a44815-2ddd-4652-9ef9-107d20e03c00)
![image](https://github.com/user-attachments/assets/c789d2eb-1386-475b-9664-9fe5fd5c39d3)
![image](https://github.com/user-attachments/assets/b11286c9-e2b6-4806-9570-04473164b91b)
![image](https://github.com/user-attachments/assets/6301097a-78ba-4e01-bbc5-43b242232ab6)


---

## Day 4 – July 9  
**Time Spent:** 2.5 hours

Revisited the PCB to clean things up. Added silkscreen labels for everything because future me deserves that. Made sure the encoder has proper clearance and also gave the OLED socket extra buffer. Threw in test points for VCC and GND in case I need to troubleshoot later. Had a short argument with KiCad about via stitching and then gave up and left it semi-stiched like a thrift store patch job. Re-ran DRC and fixed like 12 tiny errors that had been haunting me since day 2. Still deciding if I want a bottom plate logo or keep it clean.

![image](https://github.com/user-attachments/assets/7894f965-4903-4b06-9ae4-0722a1545e26)

![image](https://github.com/user-attachments/assets/6f63d70c-5638-426b-bb35-2e7c4424dac7)

![image](https://github.com/user-attachments/assets/608736aa-5770-4b86-9d6c-c68fdcdcdd87)


---

## Day 5 – July 10  
**Time Spent:** 1 hour

Prepared evrything for submission, updated everything added cad images step files etc










---

## Total Hours: 18.5 hours

The Sukhoi Board is shaping up and it’s already way more personal than I thought. Seeing the keyboard come together from an idea to an actual usable board in five days is surreal. Still some way to go with firmware polish and physical assembly, but yeah we’re airborne.

