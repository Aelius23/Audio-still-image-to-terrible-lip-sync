# Audio-still-image-to-terrible-lip-sync

## Overview
The Lip Sync Tool automates the synchronization of still images and audio tracks in video files, aiming to generate hilariously terrible lip syncs. It processes audio and maps it to mouth movements on a still image, creating a comedic effect.

## Features
- Syncs audio to still images with animated lip movements.
- Simple to run via command line.

## Requirements
- **Python 3.x** installed on your machine.
- Required Python libraries (install via `requirements.txt`):
  - `numpy`
  - `scipy`
  - `opencv-python`
  - `librosa`
  - `matplotlib`
  
  You can install the dependencies by running the following command:
  ```bash
  pip install -r requirements.txt

  
## Installation
To set up and run the tool on your local machine, follow these steps:
1. Clone the repository:
   git clone https://github.com/Aelius23/Audio-still-image-to-terrible-lip-sync.git
2. Navigate to the project directory:
   cd Audio-still-image-to-terrible-lip-sync
3. Install the required dependencies:
   pip install -r requirements.txt

## Usage
To run the lip sync tool, use the following command:
  python lipsync.py --image path/to/image.png --audio path/to/audio.wav --output path/to/output.mp4
Command-line options:
  --image: Path to the still image file (e.g., .png, .jpg).
  --audio: Path to the audio file (e.g., .wav).
  --output: Path to the output video file (e.g., .mp4).

  Example:
    python lipsync.py --image my_image.png --audio my_audio.wav --output synced_output.mp4
This command will take the still image my_image.png, sync it with the audio my_audio.wav, and save the output video to synced_output.mp4.

## Configuration
If the tool has customizable settings, you can modify them in the config.json file. For example, you can adjust phoneme mapping or other parameters to fine-tune the lip sync.

Example Configuration (config.json):
{
  "phoneme_map": {
    "a": [1, 0.5, 0.3],
    "e": [0.8, 0.6, 0.2]
  },
  "frame_rate": 30,
  "lip_intensity": 1.2
}

## Limitations
The tool is designed for humorous, exaggerated lip syncs and may not produce realistic results.
Works best with clear audio and a simple still image.

For a smoother more bleeding edge architecture check out:
https://loopyavatar.github.io/
Loopy takes more hours to make.

## Future Improvements
Add support for a graphical user interface (GUI).
Fully reconstruct following Loopy, above.

## License
This project is licensed under the MIT License. See the LICENSE file for more information.

### Instructions:
1. Go back to your README editor in GitHub.
2. Replace the existing content with this Markdown text.
3. Scroll down, add a commit message (e.g., "Add detailed README"), and click **Commit changes**.

This should give your project a clean, structured README with all the necessary information for others to use your tool. Let me know if you need any other changes!


