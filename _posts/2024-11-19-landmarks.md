---
layout: post
title: "Landmarks"
date: 2024-11-19
---
<strong>Today's Summary:</strong>
Today I implemented an rfid_landmark node that would publish the transform from the map frame to the PN5180 RFID reader's frame for rfid detection events. As you can see in the video below, there is a lot of tolerance for that detection, and so the landmark moves with the robot a bit. In addition, you can see that the landmark is preexisting at the beginning of the video but rather than localizing the robot, the detection frame moves itself. This will be addressed soon. Immediate objectives are in the full post.

<div class="video-container" style="max-width: 100%; margin: 0 auto;">
    <video id="Nov19" controls style="max-width: 100%; height: auto; display: block;">
        <source src="assets/blog/Nov24/Nov19.mp4" type="video/mp4" style="width:300px" />
    </video>
</div>

<!-- more -->

<br>
With that said, the next objectives are to 1. integrate the landmark data into the map saver packager so that the landmark is baked into the saved maps. 2. ensure that the landmarks tied to the map then influence the localization on a new map. 3. allow detection events to contribute to a larger area of detection which will likely be a polygon or sphere enlarged by detection events and used as a whole for localization.

<br>
<br>
<br>
<footer>
    Blog content © Brennan Drake, 2024. Licensed under a 
    <a href="https://creativecommons.org/licenses/by-nc-nd/4.0/">CC BY-NC-ND 4.0 License</a>.
</footer>