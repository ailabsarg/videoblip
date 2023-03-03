# videoblip
Video Action Recognition using Blip and GPT-3

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1LaIgr5L0QAD2EMVSy3GiPp_XKypa0wAD?usp=sharing)


VideoBlip
VideoBlip is a Google Colab script that allows you to upload multiple video files and attempts to recognize the contents of the videos using a combination of computer vision and natural language processing.

First, VideoBlip extracts 5 frames from each video and passes them through a BLIP recognition model to generate 5 predictions. It then sends these predictions to GPT-3 and asks it to "guess" what the video is about.

The script is designed to handle multiple video files simultaneously, making it useful for generating large datasets of videos aligned with natural language descriptions.

Note: Before running the script, you need to make a copy of the Colab notebook and replace the API key in the code with your own.

Installation
To use VideoBlip, you will need to have access to a Google Colab account. Once you have created a copy of the notebook, simply follow the instructions in the code to upload your video files and run the script.

Usage
VideoBlip can be used for a variety of applications, including:

Generating natural language metadata for videos
Creating large datasets of videos aligned with natural language descriptions
To use VideoBlip, simply upload your video files to the specified directory and run the script. The output will be a text file containing the predicted descriptions for each video.

Hardware requirements
VideoBlip requires a computer with a graphics processing unit (GPU) to run efficiently. Please make sure that your hardware meets the minimum requirements before running the script.
