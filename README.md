![GitHub last commit](https://img.shields.io/github/last-commit/UFTHaq/Extraction-Envelope-EMG-Signal-Myo-Armband-Forearm?style=for-the-badge)
![GitHub top language](https://img.shields.io/github/languages/top/UFTHaq/Extraction-Envelope-EMG-Signal-Myo-Armband-Forearm?label=Python&logo=python&logoColor=white&style=for-the-badge)
![GitHub top language](https://img.shields.io/github/languages/top/UFTHaq/Extraction-Envelope-EMG-Signal-Myo-Armband-Forearm?logo=Jupyter&style=for-the-badge)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/UFTHaq/Extraction-Envelope-EMG-Signal-Myo-Armband-Forearm?style=for-the-badge)
![GitHub Repo stars](https://img.shields.io/github/stars/UFTHaq/Extraction-Envelope-EMG-Signal-Myo-Armband-Forearm?color=red&style=for-the-badge)

# Extraction Envelope - EMG Signal - Myo Armband Forearm
How to get Envelope Extraction from EMG signals generated from Myo Armband sensors. The EMG signal comes from 7 different hand movements. This digital signal processing can be used to determine the movement of the robotic arm to be made.

If you consider this page is useful, please leave a star

## Myo Armband
<p align="center">
  <img src="https://user-images.githubusercontent.com/104829519/213673258-a1f7efe1-59f5-4daa-95c6-db164ab327e4.png" width="300" height="300" />
</p>
The Myo armband is a gesture controller that triggers a variety of actions on the computer based on the contractions of your muscles and the movements of your arm.

## Myo Armband on Forearm
<p align="center">
    <img src="https://user-images.githubusercontent.com/104829519/213673306-698f3999-ed47-4407-b104-14f29260f781.jpg" width="350" height="250" />
</p>

## Raw Data Signal
<p align="center">
  <img src="https://user-images.githubusercontent.com/104829519/213698850-7dd6bff7-a698-43cd-b908-6cf7dfb8a6fe.jpg" width="350" height="350" />
</p>
Myo Armband will record EMG signal from 8 different angle, and give 8 point of view to record EMG from different handshapes or handmovements. Raw data will save to csv and you can process it to DataFrame using Pandas.

## Envelope Extraction
<p align="center">
  <img src="https://user-images.githubusercontent.com/104829519/213707264-bc5d58a4-83e3-4232-8673-65e5ba05705c.png" width="900" height="180" />
</p>
In physics and engineering, the envelope of an oscillating signal is a smooth curve outlining its extremes The envelope thus generalizes the concept of a constant amplitude into an instantaneous amplitude. The figure illustrates a modulated sine wave varying between an upper envelope and a lower envelope. The envelope function may be a function of time, space, angle, or indeed of any variable. 
<p align="center">
  <img src="https://user-images.githubusercontent.com/104829519/213707308-92f7051c-be31-4d3d-9832-1ff7868834cd.png" width="900" height="180" />
</p>
<p align="center">
  <img src="https://user-images.githubusercontent.com/104829519/213708051-4cfd0205-b905-46f3-b05b-e5ada99bf4c8.jpg" width="700" height="800" />
</p>
<p align="center">
  <img src="https://user-images.githubusercontent.com/104829519/213717283-120c576e-a441-4a9c-bb69-a2b250b798fd.jpg" width="700" height="800" />
</p>
<p align="center">
  <img src="https://user-images.githubusercontent.com/104829519/213717536-8e89eea7-2542-462b-bd3c-a235d1ca59eb.jpg" width="1000" height="160" />
</p>

Here we can use the data envelope to further project to make bionic arm from action potential from hand nervous system.
