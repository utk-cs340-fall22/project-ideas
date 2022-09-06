# Automatic Video Subtitles

## Brief Summary of the Project Idea

The goal of this project is to create a program which uses a pre-trained neural network to create subtitles for any short video (1-2 mins). The project can then be expanded with a web interface, on which the user can upload video files.

## What Problem is Being Solved

Video content is very prevalent throughout the internet, especially as bandwidths have increased to accomodate them. With this comes the need for subtitles for those who cannot hear or speak another language. There are even paid services that offer subtitle creation manually for any of your videos. This will solve the problem by creating a free service for easy subtitle creation.

## Some of the Major Features

The main features of this program will be the interface with video files, the web interface, and the neural network. The neural network will be pre-trained since there are already many open source models for speech-to-text and training a model ourselves would be time consuming. The web interface would allow users to easily create subtitles without the need for downloading software first. Finally, the video interface should be able to work with the most common video file formats (mp4, mkv, etc.).

## Languages, Tool Sets, Third-party Code, etc.

The primary language for this project would by Python. This is because with Python, we can use Pytorch, a neural network framework. Pytorch, in combination with torchvision and torchaudio, can provide the means to perform inference using a pre-trained neural network. We can also take advantage of OpenCV for interfacing with the video files. This tool is able to recognize multiple video file data types and we can then parse out the audio from the video.

## Who Would Buy/Use This Solution
This could be advertised as a cheap alternative to the subtitle writing services which use people to write. Also, this could simply be introduced as a free service available on the web to generate reliable subtitles. The other benefit is that, since it is automated, the subtitles could be generated within a few minutes instead of having to wait for a person to write them. Although it is unlikely that we can achieve the accuracy of a human writer, the discounted cost and time savings should make up for it.
