# DiningTime ![alt text](https://travis-ci.org/karatsuh/GauchoEats.svg?branch=master)
An Alexa/Echo skill developed to provide continuous metrics of the dining hall in real time.

## Summary
Alexa/Echo will answer the user with requested metrics by voice and by visual cards send to the Official Amazon Alexa App.
Metrics that GauchoEats records and logs include:
- Number of individuals in a dining hall
- Number of people in line at a dining hall
- A live image of the current line outside the dining hall

## Implementation 
- Uses object detection, OpenCV, to process live video of individuals walking in and out of the dining hall
- Tracks the number of individuals walking in and out fo the dining hall to generate metrics

## Installation
Step by step guide on installing DiningTime onto your Echo enabled device.

### Prerequisites
Python 3 is required to run the visual detection algorithm.
Boto 3 is required to interface with AWS DynamoDB, the database. 

### Installing
The code is deployed on Amazon AWS, only an Amazon Alexa account is required to utilize the app. 

## Functionality and Known Issues
The Dining Hall API is known to be buggy and malfunction. Faulty API calls can make the program crash.

## Licensing
MIT License (https://github.com/karatsuh/TheMapaches/blob/master/LICENSE)
