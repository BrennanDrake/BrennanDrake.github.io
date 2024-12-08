---
layout: post
title: "Project Goals V1.0"
date: 2024-10-23
---

## Current Project Goals

1. **[COMPLETED] Containerize Turtlebot3_bringup and RFID capture code**
   - Allow for easier development with docker images saved on server registry
   
2. **[IN PROGRESS] Containerize rtabmap in VSCode dev container for easier development**
   - By doing this, I'll have a backup image / baseline to work off of.
   
3. **[COMPLETED] Create node to output RFID detection events as landmarks**
   - Tie the RFID tag ID to the location transform from the map frame at the instant of detection

3. **[IN PROGRESS] Integrate RFID detection events into rtabmap as landmarks**
   - Save detections with the map and use them for relocalization

<img src="assets/img/Turtlebot/onshape_turtlebot_formatted.png" alt="Docker cmd line" style="display: block; margin: 0 auto; width:100%; max-width:300px;" />

<!-- more -->
<br>
<br>
<footer>
    Blog content © Brennan Drake, 2024. Licensed under a 
    <a href="https://creativecommons.org/licenses/by-nc-nd/4.0/">CC BY-NC-ND 4.0 License</a>.
</footer>