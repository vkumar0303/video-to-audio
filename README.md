
# Title: Extract Audio from Video (Python with moviepy)

# Methodology:
![Requirements Gathering](https://github.com/user-attachments/assets/0fdbfdc0-f0fc-4961-a78e-5192742eeb7c)


# Description:

    This script allows you to easily extract the audio track from a video file and save it as an MP3 format. It utilizes the moviepy.editor library for video manipulation and the tkinter.filedialog module for user-friendly file selection dialog.


# Prerequisites:

    1. Python 3.x (ensure you have it installed: https://www.python.org/downloads/)
    2. moviepy library (install using pip: pip install moviepy)

    
# Instructions:

    1. Installation: If you haven't already, install the required library using pip:

        Bash:
            pip install moviepy

    2. Running the Script:

        > Save the script as a Python file (e.g., extract_audio.py).
        > Open a terminal or command prompt, navigate to the directory where you saved the file, and run:

            Bash:
                python extract_audio.py

# Functionality:

    > The script will open a file selection dialog box, allowing you to choose the video file from which you want to extract the audio.
    > Once you select the video, the script will use moviepy.editor.VideoFileClip to read the video.
    > It will then extract the audio stream from the video using the video.audio property.
    > Finally, the audio will be saved as a separate MP3 file named demo.mp3 in the same directory as the script.

    
# Example Usage:

    > Run the script using the command mentioned above.
    > In the file selection dialog, navigate to the location of your video file and select it.
    > The extracted audio will be saved as demo.mp3 in the same directory.

