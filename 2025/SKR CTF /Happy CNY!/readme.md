# 🎁 Angpow  CTF Challenge Write-Up
![Angpow Example](desc.jpg)
## 📖 Challenge Description

Happy Chinese New Year to all participants!
I received many 🧧 during this week, I lazy to count how much money inside the 🧧.
Can you help me to count? Here's is my Angpow

## **SOLUTION**  
in this challenge we are given 41 folder that contain picture of money. As Hint clue to ASCII so i think we need to count the money in each angpow 

## 🧩 Clue
while doing the counting i found something interesting.
I discovered that only specific image sizes translated to money values, according to this mapping:

| Image Size (KB) | Angpow Value (RM) |
|-----------------|-------------------|
| 120             | RM50              |
| 108             | RM20              |
| 113             | RM10              |
| 130             | RM1               |
| 123             | RM5               |



## 🛠️ The Script

We wrote a Python script to:
- Traverse each `AngpowX` folder
- Read the size of each image
- Match the size to the corresponding RM value
- Calculate the **total RM value per folder**

👉 [See the full script here](#) (link your script if public)

## 💰 Final Output

Here’s the **total RM found in each folder**:


