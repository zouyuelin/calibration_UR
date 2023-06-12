# 1. ArUco marker preparation
enter https://chev.me/arucogen/ to download ArUco markers
select the dictionary as "Original ArUco", unless it would not work.
Then, type 323 (as you want) into the space labled Marker ID.

# 2. Change the launch file.
enter easy_handeye/easy_handeye/launch and find the ur3e_calibration.launch,
edit the Marker ID and Robot ip

# 3. pip install transforms3d

# 4. roslaunch easy_handeye ur3e_calibration.launch

# 5. click the Global Options
change the Fixed Frame to base.

# 6. open a terminal, type in rqt_image_view

# 7. Start to collect the data.
## 7.1 click the "check starting pose"
## 7.2 click the Next pose
## 7.3 click plan
## 7.4 execute to move the robot arm to other posture.

# 8. Take sample

# 9. Finished it!
