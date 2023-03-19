# Microchallenge-II

For the second Microchallenge, we continued with the idea of bio-sensing and further developing our first prototype.
Our interests overlapped in concepts surrounding mental and physical health, and a more holistic perspective on wellness. We discussed the wisdom that our bodies hold, and their constant expression of feeling. It is important to listen to our bodies and follow what they desire if we want to enjoy living well. So, we decided to prototype a biofeedback device that aids in understanding information that our nervous systems are transmitting so as to provide tools to improve wellbeing. We thought, what if we can visualize clearly what our nervous system is expressing? Can this help us to control our bodily states and the way our minds interpret existence?

We decided to explore this concept by building a model that visualizes Heart Rate Variability (HRV). HRV is the amount of time between heartbeats, which vary constantly depending on the state of balance of the nervous system. Both sympathetic and parasympathetic nervous systems are competing against each other, and the result from this balancing equation provides a value in ms. A higher value usually indicates a more balanced nervous system, while a lower value might indicate that one either sympathetic or parasympathetic system is dominating. This is expected while exercising, for instance, but might not be beneficial while sleeping. Since it is highly influenced by our nervous system, this implies that HRV represents valuable information transmitted to our brain on how our bodies should react to the stimuli it is exposed to. This could include the environment we are in, what we are feeling, what we are thinking, the people around us or the activities we engage in. There are many other types of biofeedback data that could also be considered, but we understand that HRV is easy to measure and provides comprehensive information. 
 
If we could visualize HRV in real time, can we learn how to achieve balance? 

By collecting heart rate data from ECG sensors, calculating HRV of a user, and visualizing this information in an engaging format, we could allow users to understand their bodily states and redirect them towards states of higher benefit.


---

Project planning:
Habing 3 parts to the project, we divided and planned our work while further developing the concept.
![Project planning](https://user-images.githubusercontent.com/114681912/226207674-feef9e87-f232-4f25-93f4-4475d92110cd.jpg)

Concept and Design Development :

![concept](https://user-images.githubusercontent.com/114681912/226208115-6bac7820-ea34-4523-8090-6b5f173a7cce.jpg)
We started off with experimenting with new ideas and designs that we could use to demsonstrate our idea.

![design 1](https://user-images.githubusercontent.com/114681912/226208139-6aef0b4a-13ba-4688-a279-a2c42b80370d.jpg)

not being satisfied with these first few designs we developed the idea of having layers of painted transparencies to interact and overlap with one another, to create a sense of depth, form and movements while animating the original idea of creating an orb. created images in increasing form and trying to achieve an embodying experience which encourages a deeper outlook of understanding your state through the illumination of the patterns.

![design](https://user-images.githubusercontent.com/114681912/226208377-b2a52637-2ce2-4339-842f-be6a75890497.jpg)

---

Design Process (Fabrication Methods):

The design was to be rastered on clear acrylic sheets using the laser cut machine which needed alot of playing around with the intensities and the sizes of the design to acheive the final look. 
![laser cut](https://user-images.githubusercontent.com/114681912/226208740-42ad3090-ea5d-441c-a7e2-fbf68674afc5.jpg)

The next part of the fabrication process was to 3D print the support for these acrylic frames. It didnt work out right for us in the first try, we had multiple issues with the printer and with understanding the tolerance of the material which led us to print a few times before we got it right.
![3d print](https://user-images.githubusercontent.com/114681912/226209090-e504d113-1363-4d91-b374-5f3630b5a2d5.jpg)

The last part was the base structure- for which we used the CNC as the fabrication process as that would allow us to achieve a more clean and minimal look. we wanted a deeper box to accomodate the electronics and for that we cut 2 wood pieces and then glues them together to achieve the desired dept.

![cnc post](https://user-images.githubusercontent.com/114681912/226209955-adaa4cda-0812-4696-a12c-473fa309b168.jpg)

---

Electronics and Coding:

This aspect of the project involved the integration of two separate systems. The first part involved connecting ECG sensors to the user and collecting data. Initial results were unexpectedly foggy and inconsistent. What was expected to be an easy task turned out to be much more complex. Although we were able to achieve some interesting results after certain tweaks and calibrations (fixing the sensors to account movement, thresholds in coding), the data was not reliable and the portrayed visualizations ended up being a simulation of the concept. Still, it was an interesting learning experience to understand how ECG sensors are made and the calculations towards achieving accurate HRV. The second part of the project involved the setup of 3 rows of 3 LEDs, and using a Neopixel to provide colorful variations to illustrate the Heart Aura. We then programmed the lights to display variations between blue, purple and white when having stable data, or red colors when displaying signs of distress. Again, since the data is not consistent this entire part of the project is more conceptual than anything. 

![electronics 1](https://user-images.githubusercontent.com/114681912/226210329-71b552e3-21dc-40b8-bfac-8329698ec79e.jpg)
![electronics 2](https://user-images.githubusercontent.com/114681912/226210331-f99216a8-bed6-4df7-b9f4-4a3bddeb4b92.jpg)

---

Final product:



https://www.canva.com/design/DAFddoQNKSM/m0ss5t3Zf0uYhBHEGZIg5Q/view?utm_content=DAFddoQNKSM&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
