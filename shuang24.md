# Profanity Eraser

## Summary
The Profanity Eraser is a website that allows the user to upload a video and returns the same video but with the unwanted profanity silenced.

## Problem
YouTube often demonetizes videos that have swearing and derogatory words in them. As users of YouTube, we know the struggles that many YouTubers have with trying to filter themselves in videos to avoid getting demonetized. It is also a pain to have to re-edit your video to take out the cursing when you just finished editing it, losing money because you are now behind on the upload schedule.

## Major Features
- Upload a video you just filmed or a YouTube URL, and it will edit out all curse words. 
- Choose what words to mute with the word search filter
- Download the video and resubmit it on YouTube without having to edit it yourself

## Implementation
- Python and the Flask library used to build the webserver
- Python also has libraries with handling mp3 files.
- Assembly AI API used to transcript the video and have a word search filter to mute parts of the video
- Google Coud Storage API used to store videos while it's being edited

## Stakeholders
The target audience are the content creators who will save time by not having to edit out their profanity.
