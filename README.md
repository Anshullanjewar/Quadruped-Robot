<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->

[![LinkedIn][linkedin-shield]][linkedin-url]


<br />
<div align="center">

  <h3 align="center">Quadruped Robot</h3>

  <p align="center">
    <p align="center" float="left">
<table>
  <tr>
    <!-- front -->
    <td><img src="https://github.com/Anshullanjewar/Quadruped-Robot/blob/main/Quad%20Img/IMG_20230624_031603.jpg" width="1080" height="800"></td>
  </tr>
 </table>
This is a quadruped robot, that is self-directed using sensors and camera.!!    <br />
    <a href="https://github.com/Anshullanjewar/Quadruped-Robot"><strong>Explore the docs »</strong></a>
    <br />
    <br />
  </p>
</div>


<!-- ABOUT THE PROJECT -->
## About The Project


### Arduino Quadruped Robot with Vision and Obstacle Avoidance
This repository showcases a quadruped robot built with an Arduino UNO, MG-996R servo motors, a PCA9685 servo driver, ultrasonic sensors for obstacle avoidance, and an ESP32-Cam for vision capabilities. The robot is powered by a LiPo battery.


### Inspiration
The inspiration for this quadruped robot comes from observing the agility and efficiency of animals, particularly dogs and cats, in their movement and navigation. This project aims to mimic these characteristics in a robotic form, providing a foundation for further exploration of robotic locomotion and control. The Boston Dynamics' Spot robot also served as a significant influence, showcasing the potential of quadruped robots in various applications.


<table>
  <tr>
    <!-- started as -->
    <td><img src="https://github.com/Anshullanjewar/Quadruped-Robot/blob/main/Quad%20Img/IMG_20210505_175559.jpg" width="1080" height="500"></td>
        <td><img src="https://github.com/Anshullanjewar/Quadruped-Robot/blob/main/Quad%20Img/IMG_20210502_183455.jpg" width="1080" height="500"></td>

  </tr>
 </table>


The model was then found to be a structural fault and had an imbalance weight distribution so I decided to create a 3-D model, so used Creo to design the model and then 3-D print it. 


 

<table>
  <tr>
    <!-- designs -->
    <td><img src="https://github.com/Anshullanjewar/Quadruped-Robot/blob/main/Quad%20Img/Screenshot%20(165).png" width="1080" height="500"></td>
        <td><img src="https://github.com/Anshullanjewar/Quadruped-Robot/blob/main/Quad%20Img/Screenshot%20(163).png" width="1080" height="500"></td>
    <td><img src="https://github.com/Anshullanjewar/Quadruped-Robot/blob/main/Quad%20Img/Screenshot%20(162).png" width="1080" height="500"></td>

  </tr>
 </table>


 
### Assembly Instructions
* Frame Assembly:
  Assemble the main body and legs of the robot using appropriate materials.

<table>
  <tr>
    <!-- parts -->
    <td><img src="https://github.com/Anshullanjewar/Quadruped-Robot/blob/main/Quad%20Img/IMG_20230203_153807.jpg" width="500" height="500"></td>
  </tr>
 </table>
 
* Mounting Components:
  Attach the Arduino UNO, PCA9685 driver, and ultrasonic sensor to the main body.
  Mount the MG-996R servo motors on the legs.
  Fix the ESP-32 Cam in a suitable position for video capturing.

* Connecting Components:
  Connect the servo motors to the PCA9685 driver.
  Connect the ultrasonic sensor to the Arduino UNO.
  Connect the ESP-32 Cam to the Arduino UNO.
  Power the system using the LiPo battery.

<table>
  <tr>
    <!-- final -->
    <td><img src="https://github.com/Anshullanjewar/Quadruped-Robot/blob/main/Quad%20Img/IMG_20230624_031603.jpg" width="1080" height="500"></td>
  </tr>
 </table>

 
### Hardware Integrated

* Arduino UNO: Main microcontroller.
* MG-996R Servo Motors: High-torque servos for leg movement.
* Ultrasonic Sensor: For obstacle detection.
* ESP-32 Cam: For video streaming.
* LiPo Battery: Power supply.
* PCA9685 16-Channel Servo Motor Driver: Controls multiple servos simultaneously.
  

### WORKING 


### Usage
* Power On: Connect the LiPo battery and power on the robot.
* Walking: The robot will start walking using predefined gait algorithms.
* Obstacle Avoidance: The ultrasonic sensor will detect obstacles and the robot will adjust its path accordingly.
* Video Streaming: Access the video feed from the ESP-32 Cam through a web browser by connecting to the specified IP address.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Get Started!

To learn more about the project, explore the codebase, or contribute, visit the GitHub repository:

* **Project Link:** https://github.com/Anshullanjewar/Quadruped-Robot



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- CONTACT -->
## Contact

Name - [Anshul Lanjewar](https://www.linkedin.com/in/anshul-lanjewar) - anshullanjewar12@gmail.com

Project Link: [https://github.com/Anshullanjewar/Quadruped-Robot](https://github.com/Anshullanjewar/Quadruped-Robot)






<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[Portfolio-shield]: https://img.shields.io/github/contributors/Anshullanjewar/Best-README-Template.svg?style=for-the-badge
[portfolio-url]: https://anshullanjewar.github.io/
[stars-shield]: https://img.shields.io/github/stars/Anshullanjewar/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/Anshullanjewar/Guided_App/issues
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/Anshullanjewar/Guided_App/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]:https://github.com/Anshullanjewar/Guided_App/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/anshul-lanjewar
[Java_url]: https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white
[firebase_url]: https://img.shields.io/badge/firebase-a08021?style=for-the-badge&logo=firebase&logoColor=ffcd34
[android_url]: https://img.shields.io/badge/android%20studio-346ac1?style=for-the-badge&logo=android%20studio&logoColor=white
