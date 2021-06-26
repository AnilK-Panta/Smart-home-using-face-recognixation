# Smart-home-using-face-recognition
This project is divided into three section <br>

#### &emsp; Face Recognition using OpenCV
#### &emsp; Alert message
#### &emsp; Web App to display the livestream
<br>
 
### Face Recognition using OpenCV
This section has three main function, which is divided into three parts

#### &emsp;Step 1: Data Collection
&emsp; It takes the image data from the user whose image need to be trained.<br>
&emsp; Go inside **face dataset.py** and execute the program <br>
<-- Command line Image Here --> <br>

&emsp; After running this command, your webcam starts taking your sample images and stores it inside **dataset** folder<br>
<-- dataset Image Here -->

#### &emsp;Step 2: Data Training
&emsp; It trains the the raw images stored in the **dataset** folder <br>
&emsp; Go inside **face training.py** and execute the program <br>
<-- Command line Image Here --> <br>

&emsp; After running this command, the data will be stored as ***trainer.yml*** in **trainer** folder as an array of numbers.
<--Image Here-->

#### &emsp;Step 3: Face Recognition
&emsp; After following all the above steps we are now ready to go.<br>
&emsp; Go inside **face recognition.py** and execute the program <br>
<-- Command line Image Here --> <br>

&emsp; After running this command, your webcam will trace your face and tries to compare it with the trained image data inside trainer.yml. <br>
&emsp; If your face matches with the trained data it will display **Anil K. Panta** on the frame else it will display **Unknown**<br>
<-- Command line Image Here --> <br>


### Alert Message
Smart-home-using-face-recognixation
