# pokerGame
###This repository contains a fully autonomous ROS2-based Poker Dealer Robot designed to function like a real casino dealer. The system uses computer vision, robotics, and custom game logic to manage an entire poker game without human intervention.

##Capabilities
###The robot automatically deals cards, tracks player chip counts, announces actions, and determines winners.
A vision module continuously scans the table to detect poker chips using OpenCV and color segmentation.
A game manager package handles blinds, betting rounds, pot updates, hand evaluation, and turn flow. 
A robot arm module controls card dealing using ROS2 motion planning.
