


# Project Name: Detect Helmet Impact in videos of NFL plays


### Company Name: The Eagle-Eyed Zealots

## Why Choose Our Company?
The Eagles-Eyed Zealots work continously to build world class recognition systems for all areas of society from Sports to Softwares. 

##### Prepared For: CS301, Computer Vision Area.
*24 April, 2022*
</div>

## Table of Contents

<!--toc max2-->

## Overview
CTE, or Chronic traumatic encephalopathy, is a dangerous brain condition that develops due to continuous blows to the head. With new research and statistics being released yearly about this deadly condition, safety has become a topic of huge concern in the football community. One research that was conducted by Boston University found CTE in 99% of brains obtained from NFL players.

## Problem

The Problem for this project is to teach the computer to automatically detect whether a player was involved in head/helmet contact through NFL game footage. This topic is very interesting as it tries to make the most popular game in the States more safe for all parties involved. In the past couple of years, the NFL implemented new rules in order to protect the safety of players which have been dubbed as “soft” by critics and former players alike. However, if a computer is able to automatically detect helmet contact 83 times faster than a person conducting the analysis manually, that would bridge the gap between the discontent of the safety enthusiast and the conservative football fan. 



## Helpful Readings
https://www.bu.edu/articles/2017/cte-former-nfl-players/

This article by BU describes the mind blowing number of football players who have “tested positive” for CTE.

https://www.vox.com/science-and-health/2018/2/2/16956440/super-bowl-2020-concussion-symptoms-cte-football-nfl-brain-damage-youth
This article above shows the frequency of concussion in the NFL and the consequences of being diagnosed with CTE.

## Data In Question

The data that we’ll use are from [NFL 1st and Future - Impact Detection](https://www.kaggle.com/competitions/nfl-impact-detection/data) competition. We are tasked with identifying helmet collison from video files. The training set videos are in train with corresponding labels in train_labels.csv, while the videos for which we must predict are in the test folder.
We’re also provided with files to aid in helmet detection. The images are in the images folder while the bounding boxes are on the image_label.csv

## What Algorithm?

The area of concern for this project is computer vision. There are a few algorithms that we are interested in as we factor in the size of the objects especially considering that there are two angles/video for each play in the training set, which include the sideline and end zone view. For this project, we are interested in the convolutional neural network(CNN) approaches. The YOLO and the SSD are our top choices with the latter seeming to be more favored.  We will not take into account the severity of the hit, as we are only worried if the helmets of two players hit each other or a shoulder to helmet hit, though that might be a bit too complex. 



### Members
Below are the Group Members

| First Name        | Last Name |  Email |
|-------------|---------------|-------------|
| Simon | Kurbiel | sak74@njit.edu |
| Austin | Ignarra  | ai37@njit.edu |
| Cristhian | Molina  | cdm9@njit.edu |






