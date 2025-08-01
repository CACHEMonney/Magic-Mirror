---
title: "MAGIC-MIRROR"
author: "Jayden M."
description: "A Mirror to tell you who is the prettiest of them all"
created_at: "2025-7-20"
---

#Project time ~20hrs

# 20/07/25 PLANNING

during undercity i tried to do some experimentation with facial recognition using open cv so i wanted to make a prooject that takes soem of those lessons and makes something cool i started planning a general idea

![20250801_025025](https://github.com/user-attachments/assets/83575d82-b353-4d2f-a5cd-60d1a45bab89)

after doing more research i found that using a camera esp32 and a would be better for my purposes and solve complexity issues i also mearsured out my mirror to create the slotting on design

![20250801_025031](https://github.com/user-attachments/assets/83ef126b-0748-4f41-85ce-51c4e053eccf)

**~3hrs**


# 21/07/25 PARTS SELECTION AND MODELLING

I started by modelleing out my desing making spots for the camera and speakers

<img width="1067" height="442" alt="image" src="https://github.com/user-attachments/assets/d680b56b-831d-404c-9d15-f2caa4454cc0" />

due to the distance between parts and the finiky nature of esp32 wiring and short turnaroud i opted for hidden bread board to create easiliy ammendable by using a slideing board

<img width="1088" height="317" alt="image" src="https://github.com/user-attachments/assets/ddae491b-6f4e-4d45-ae7f-ec034e5cf2ad" />

**~4hrs**

# 24/07/25 WIRING

I had to look for and learn a new resource to model this circuit and chose fritzing and i couldnt figure it out whatsoever so i just drew the wiring diagram out

![20250801_053105](https://github.com/user-attachments/assets/55127234-6108-47cb-ba2e-3c57fe5d7cc4)

I connected speakers in parallel for identical outputs and any of the difference would creat a cool echo

**~3hrs**

# 25-30/07/25 FIRMWARE

I cobbled together some firmware that uses the cams facial recognition to play positive affirmations when a known face walks across and negative one when an unkonwn does

had to use audacity to change audio files into their components 
**~10hrs**
