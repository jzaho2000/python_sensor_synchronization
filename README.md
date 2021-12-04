# Python sensor synchronization

This project were created for my thesis where I am researching ECGs.

In this project, I developed a method for synchronizing ECG data collected by sensors using timestamp data collected 
from sensors and a mobile phone. As you can see from the image in the PDF file, the data collected by the three sensors 
was synchronized very well.

If you are wondering, the acceleration and gyroscope data are collected only from the first sensor. I made this kind of solution because there exists a risk when using multiple sensor, that the mobile application would crash in the middle of data collection. My solution were to collect multiple data from main sensor and only ECG data from other sensors.
