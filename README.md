To run this project on your machine, after unzipping the project follow these commands:
<ol>
  <li>
    Create Several Empty directories with these exact names:
    <ol>
      <li>Attendance</li>
      <li>ImagesUnknown</li>
      <li>TrainingImage</li>
      <li>TrainingImageLabel</li>
    </ol>
  </li>
  <li>Then open Command Prompt in same Project directory and run these Commands:
    <br>
    (Assuming you have Python3 and pip installed)
    <ol>
      <li>pip install -r required.txt --user</li>
      <li>pip install -r opencv-contrib-python --upgrade --user</li>
      Now you are all set to start this project, just start by this command:
      <li>python train.py</li>
    </ol>
  </li>
  <li>You will be shown a window like this:<br>
    <img src="Face_Recogniser 13-06-2020 9.14.42 PM.png" width=75%>
  </li>
  <li> Enter Numeric value for Id. </li>
  <li> Enter your Name in the field provided.</li>
  <li> Click on Take Images.
    <br>
    (Another window will open and your webcam will be activated you can see it is taking your picture to train its model.
    <br>
    The window will close automatically,if it doesn't press q to close it.)
  </li>
  <li>Click on Train Images.</li>
  <li>Now Click on Track Images.
    <br>
    (Another window will open and your webcam will be activated you can see it is showing your name below your face.)
  </li>
  <li> Press q to close the window.</li>
  <li>Now go to your project diectory and open Attendance folder(remember you created blank folders).
    <br>
    Here you can see a .csv file is created open it with excel you can see it contains your name id and a datestamp of you when you tracked the image.
  </li>
</ol>
Similarly You can train it for multiple peoples.(Place one person in the frame while taking the image.)
<br>
Although try with multiple people in the frame when you are marking the attandance i.e. Tracking Images.
<br>
<br>
For further assistance raise a Issue.
