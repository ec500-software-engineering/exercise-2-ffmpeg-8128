# FFMPEG - ex2

[![Build Status](https://travis-ci.com/ec500-software-engineering/exercise-2-ffmpeg-8128.svg?branch=master)](https://travis-ci.com/ec500-software-engineering/exercise-2-ffmpeg-8128)

## Prerequisites 

Prerequisites can be installed by requirements.txt

Also, ffmpeg is needed. Please download the ffmpeg from https://www.ffmpeg.org/ and set the PATH

## Quick run  
To run this program, please input 
```shell
python main_async.py 'REPLACE THIS WITH YOUR FILE NAME'
```
in your command line.

In test, you can use the test video named "video.avi" in my repo

## Introduction

By using this program two threads will be created and run simultaneously to transcode the files into 480P and 720P videos. After the job is done, the program will print "job is done". 

## Error Handler

If you did not install the ffmpeg, the program will raise the error to inform you about the problem. Also, if you did not enter the file name in the command line, there will be errors telling you to add paramter