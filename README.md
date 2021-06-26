<h1 align="center"> Smart-home-using-face-recognition </h1>
<p align="center" > This project is divided into three section <br> </p>

#### &emsp; Face Recognition using OpenCV
#### &emsp; Alert message
#### &emsp; Web App to display the livestream
<br>
 
<h2 align="center"> Face Recognition using OpenCV </h2>
<p align="center">This section has three main function, which is divided into three parts</p>

#### &emsp;Step 1: Data Collection
&emsp; It takes the image data from the user whose image need to be trained.<br>
&emsp; Go inside **face dataset.py** and execute the program <br>
<p align="center">
<-- Command line Image Here --> <br>
 </p>

&emsp; After running this command, your webcam starts taking your sample images and stores it inside **dataset** folder<br><br>
 <p align="center">
  <img src="https://user-images.githubusercontent.com/35441380/123501492-13f81b00-d665-11eb-9e1b-c75dc17c2beb.png" width="500px" height="auto">
 </p>
#### &emsp;Step 2: Data Training
&emsp; It trains the the raw images stored in the **dataset** folder <br>
&emsp; Go inside **face training.py** and execute the program <br>
<p align="center">
 <--command line Image Here-->
</p>


&emsp; After running this command, the data will be stored as ***trainer.yml*** in **trainer** folder as an array of numbers.<br><br>
 <p align="center">
<img src="https://user-images.githubusercontent.com/35441380/123501549-705b3a80-d665-11eb-87ea-dbac4a32824e.png" width="500px" height="auto">
</p>

#### &emsp;Step 3: Face Recognition
&emsp; After following all the above steps we are now ready to go.<br>
&emsp; Go inside **face recognition.py** and execute the program <br>
<p align="center">
<-- Command line Image Here --> <br>
 </p>

&emsp; After running this command, your webcam will trace your face and tries to compare it with the trained image data inside trainer.yml. <br>
&emsp; If your face matches with the trained data it will display **Anil K.** on the frame else it will display **Unknown**<br><br>
 <p align="center">
<img src="https://user-images.githubusercontent.com/35441380/123501558-85d06480-d665-11eb-855d-2b99b9ab235c.png" width="500px" height="auto">
</p>



<h2 align="center"> Alert Message </h2>
When Unknown face comes in the camera frame, it sends the alert notification in your device.<br><br>
<p align="center">
<img src="https://user-images.githubusercontent.com/35441380/123501619-f081a000-d665-11eb-8bbf-85698f7a86a7.png">
</p>

<h2 align="center"> Web App to display the livestream</h2>
Open the website in your live server.<br>
Login: Use **admin** as User Id and Password<br><br>
<p align="center">
<img src="https://user-images.githubusercontent.com/35441380/123501626-fbd4cb80-d665-11eb-81b6-3319d31b20bb.png" width="500px" height="auto">
</p>

Browser asks permission to allow your webcam<br>
It will stream your video in the web.<br><br>
<p align="center">
<img src="https://user-images.githubusercontent.com/35441380/123501628-03947000-d666-11eb-877e-d4d3d94317cb.png" width="500px" height="auto">
</p>


#### Note:
The face recognization and the web app is completely different project.<br>
Instead, of showing notification in the pc, we can send notification as SMS or Email<br>
We can access the surveillance camera remotely in our webapp and display the stream in our browser.

#### If you take less sample data, AI will laugh on you<br><br>
<p align="center">
<img src="https://user-images.githubusercontent.com/35441380/123501732-b9f85500-d666-11eb-9cc3-3c58121bfb4f.png" width="500px" height="auto">
</p>
<br><br><br>

[![IoT Based Smart Home](https://user-images.githubusercontent.com/35441380/123502667-dba90a80-d66d-11eb-93a6-d3c3f8c346b1.png)](https://youtu.be/4j9fsOxirIg "IoT Based Smart Home")




<h2 align="center">
** Have a nice day **
</h2>

