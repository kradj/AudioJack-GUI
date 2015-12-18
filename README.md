![AudioJack-GUI](https://raw.githubusercontent.com/Blue9/AudioJack-GUI/master/logo/AudioJack%20Logo.png)

A smart YouTube-to-MP3 converter that automatically finds and adds ID3 tags (artist, title, album, cover art) to downloaded MP3 files.

[Official website](http://blue9.github.io/AudioJack-GUI/)

## Screenshots
![AudioJack-GUI v2 in action](https://raw.githubusercontent.com/Blue9/AudioJack-GUI/master/screenshots/Screenshot_v2.png)

![AudioJack-GUI in action](https://raw.githubusercontent.com/Blue9/AudioJack-GUI/master/screenshots/Screenshot.png)

## Usage
After installing necessary requirements, using the program is quite self-explanatory.

0. Run `python audiojack_gui.py` or `python audiojack_gui_v2.py` (`v2` is preferred and more actively developed).
![Step 0](https://raw.githubusercontent.com/Blue9/AudioJack-GUI/master/screenshots/AudioJack%20Steps/Step%200.png)
1. Paste a YouTube or SoundCloud URL in the search box and click on "Go!"
![Step 1](https://raw.githubusercontent.com/Blue9/AudioJack-GUI/master/screenshots/AudioJack%20Steps/Step%201.png)
2. Wait for about 10 seconds as the program loads.
![Step 2](https://raw.githubusercontent.com/Blue9/AudioJack-GUI/master/screenshots/AudioJack%20Steps/Step%202.png)
3. A grid of song titles, artists, and albums will appear.
![Step 3](https://raw.githubusercontent.com/Blue9/AudioJack-GUI/master/screenshots/AudioJack%20Steps/Step%203.png)
4. Click on the metadata you wish to add to your downloaded MP3 file, or if none of them are correct, fill out the "Custom tags" form.
![Step 4](https://raw.githubusercontent.com/Blue9/AudioJack-GUI/master/screenshots/AudioJack%20Steps/Step%204.png)
5. Voilà! The MP3 file will be in the same directory you ran the program from.
![Step 5](https://raw.githubusercontent.com/Blue9/AudioJack-GUI/master/screenshots/AudioJack%20Steps/Step%205.png)

## Requirements
1. Python 2.7
2. [AudioJack](https://github.com/Blue9/AudioJack)
2. [FFmpeg](https://www.ffmpeg.org/) (for MP3 conversion).  
3. In addition, you will need to install the following modules for AudioJack to work:
 - [mutagen](https://bitbucket.org/lazka/mutagen)
 - [musicbrainzngs v0.6.dev0](https://github.com/alastair/python-musicbrainzngs)
 - [youtube-dl](https://github.com/rg3/youtube-dl)

## FAQ
Why are there two versions?
- I made `audiojack_gui.py` using `Tkinter` widgets. After realizing how ugly the native `Tkinter` widgets were, I decided to create a new version using `ttk` widgets, which use the native system UI. As of now, I plan to continue development on `audiojack_gui_v2.py`.
