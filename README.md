# videoblip
Video Action Recognition using Blip and GPT-3

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1LaIgr5L0QAD2EMVSy3GiPp_XKypa0wAD?usp=sharing)


# VideoBlip

VideoBlip is a video recognition script that aims to extract text from videos. It does so by extracting 5 frames from a video, passing them through the Blip recognition model, which identifies the contents of those frames, and sending those 5 predictions to GPT-3 to generate a text description of what is happening in the video. The script allows you to upload as many files as you want at once. It could be used as a natural language metadata generator or to generate huge datasets of videos aligned with a description. But the core function of the script is to convert video content into text descriptions.

## Usage

1. First, make a copy of this notebook to replace the API key in the code.
2. Go to File, Save a copy in Drive.
3. Change the `YOUR_API_KEY` to your OpenAI API key.
4. Run the script cell bt cell and wait for the processing to finish.

## Hardware Configuration

The script requires a machine with a GPU for optimal performance. If you don't have a GPU, you can still run the script, but it may take significantly longer to complete.

## Example

Check out an example of the script in action [here](https://colab.research.google.com/drive/1LaIgr5L0QAD2EMVSy3GiPp_XKypa0wAD?usp=sharing).

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests.

## License

This project is licensed under the [MIT license](https://github.com/ivfloyd/videoblip/blob/main/LICENSE).

