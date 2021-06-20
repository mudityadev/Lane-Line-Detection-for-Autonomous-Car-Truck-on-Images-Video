<!-- PROJECT -->
  <h3 align="center">Lane Line Detection Project 
</h3>

  <p align="center">
   Build for autonomous cars and trucks.
    <br />
    <a href="https://rmuditya.github.io/MudityaRaghav/"><strong>Muditya Raghav Portflio »</strong></a>
    <br />
    <br />
    <a href="https://github.com/rmuditya/Lane-Line-Detection-for-Autonomous-Car-Truck-on-Images-Video/blob/master/test_videos_output/solidWhiteRight.mp4">View Demo</a>
    ·
    <a href="https://github.com/rmuditya/Lane-Line-Detection-for-Autonomous-Car-Truck-on-Images-Video/issues">Report Bug</a>
    ·
    <a href="https://github.com/rmuditya/Lane-Line-Detection-for-Autonomous-Car-Truck-on-Images-Video/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#overview">Overview - About The Project</a></li>
    <li><a href="#tools">Tools and Technique</a></li>
    <li><a href="#pipeline">Pipeline</a></li>
    <li>
      <a href="#getting-started">How to Run</a>
      <ul>
        <li><a href="#prerequisites">Environment Setup</a></li>
        <li><a href="#installation">Installation of Libraries</a></li>
        <li><a href="#installation">Command on Terminal</a></li>
      </ul>
    </li>
    <li><a href="#improve">Possible Improvements</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>




<!-- ABOUT THE PROJECT -->
## Overview - About The Project
![alt text](https://github.com/rmuditya/Lane-Line-Detection-for-Autonomous-Car-Truck-on-Images-Video/blob/master/Screenshots/laneLines_thirdPass.jpg)
<br />
Humans have eyes to understand the sounding but machines don't. Autonomous systems have Cameras to see the world and by using the Computer Vision algorithm, they can understand them, take decisions.
I designed a Lane Line detection program that helps autonomous cars and trucks to find the line in any environment or weather.


<!-- Tools -->
## Tools and Technique

* Color Selection
* Region of Interest Selection
* Grayscaling
* Gaussian smoothing
* Canny Edge Detection
* Hough Transform line detection

<!-- Pipeline -->
## Pipeline

* Import all library - NumPy, OpenCV, Matplotlib
* Image Images
* Convert RGB image to Grayscale image
* Using Canny Edge detection 
* Region of Interest - 4 Sided polygon to Mask
* Hough Transform
* Draw the lines
* Output



### Installation

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```JS
   const API_KEY = 'ENTER YOUR API';
   ```
