A month away from the deadline, also my first time making one of these PCBs.
I’m thinking about a split-in-the-middle 65% keyboard with integrated plate design

Written Clear goal:
- Make it work, of course
- Standard 65% Keyboard
- A split in the middle so it can fold for portability
- Future wireless upgrade
- Function keys by pressing down on a designated fn key
- Leaving space for additional features in the future

Rough idea sketch, took me like an hour, this is not going to go well =(

<img width="490" height="655" alt="image" src="https://github.com/user-attachments/assets/94e34b6f-839e-4561-9187-d76a057caca7" />
**TIME SPENT: 1h**
Finished the Schematics in roughly 5 hours, really took longer than I expected, I had to go into the library and add 3D models manually which is a pain. Also have to check for connection errors individually. Added some extra features including an encoder and an OLED screen because why not? They are quite useful sometimes.

<img width="857" height="604" alt="Screenshot 2026-09-06 200716" src="https://github.com/user-attachments/assets/1d2c1dea-e99b-44c2-83fb-c68182404238" />
**TIME SPENT: 5h**

Laying out the PCB right now, I spent a long time getting the spacing part figured out since I have never used KiCAD before. I didnt even know you’d have to drag from the exact same place (The center, usually) to make everything aligned. Though I do have experience with other older school project software like Traxmaker, It’s like apple to bananas, therefore I took a while to get everything all looking nice and well placed even following the guide

<img width="777" height="272" alt="Screenshot 2026-09-06 200447" src="https://github.com/user-attachments/assets/77ed8fc5-a6a2-4003-90ab-630bf25c6d1a" />

Finished PCB that took me 4 hours of grinding, Might look odd but everything should work. Got like 48 different DRC errors but after checking each one of them they are all false in my case.

Cool 3D render I would REALLY like to show, raytraced with my 5060 (Why is there a raytracing button there anyway?)

<img width="768" height="434" alt="Screenshot 2026-09-08 081904" src="https://github.com/user-attachments/assets/8de5e564-af18-4913-9c5d-2c5b15444446" />
**TIME SPENT: 4h**

Exported the 3D model of the entire PCB and ready for case design now.

Case design is done now, took me roughly 2 hours, integrated plate so it’s easy to assemble, used the top empty space as sort of a reserve for future new features if i were ever going to add something new.

<img width="902" height="355" alt="Screenshot 2026-09-11 114219" src="https://github.com/user-attachments/assets/dd73753d-b4db-4fe8-b1bf-428262eba6b8" />
**TIME SPENT: 2h**

Fun fact: the encoder knob is the result of an intersection boolean of a cylinder with a gear.

<img width="352" height="315" alt="Screenshot 2026-09-13 125942" src="https://github.com/user-attachments/assets/9afd4bd9-524f-4365-90b0-bec773a5e39c" />

The top empty space is left empty for future add-ons. For example, Since I love driving in Assetto Corsa but I travel frequently and can't bring a whole racing setup with me, it could be used to install a whole LED bulb bar recreating the rev speed LED panel of a race car, That will be really handy for sim racing.

Screen well integrated into the keyboard chassis with some fillet and chamfer.

<img width="704" height="445" alt="Screenshot 2026-09-13 130040" src="https://github.com/user-attachments/assets/ec8e4f85-b355-4912-a3d0-a576201667eb" />

Put it in my slicer and sliced for my Elegoo CC (not Claude Code, it means Centauri Carbon), uses roughly 230 grams of PETG filament by estimation.
And with that, I’m gonna start with the firmware =)

<img width="768" height="610" alt="Screenshot 2026-09-11 222836" src="https://github.com/user-attachments/assets/68762e6b-1d15-4418-8869-c2c38dd834a9" />

Hours Passed, I’m still mapping out the keyboard in the .toml, this is genuinely a pain, but one good thing is I do get to map the encoder in RMK which makes everything more convenient.

<img width="613" height="502" alt="Screenshot 2026-09-13 130214" src="https://github.com/user-attachments/assets/ae45806e-5018-44ff-966b-d9b32b04e333" />

For now, I will pass on the OLED screen since I do want to get everything shipped and test the keyboard itself out first.

Yay me happy hehehehhe build.yml yeye green checkmarkeiorhaoiwh me happy

<img width="461" height="188" alt="Screenshot 2026-09-13 094904" src="https://github.com/user-attachments/assets/c8261fad-c1a2-45ba-9235-f7b699d1eddd" />
**TIME SPENT: 3h**

Really took me a long time to map each individual keys and verifying them later just to find out i messed up somewhere and took another few hours to figure it out.

And with that on the clock, I spent around **15 hours** in total, the PCB part is extremely time consuming though it isn't complex.

BOM included in the repository.
