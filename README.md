# PyMacroRecord
PyMacroRecorder is an completely free Macro Recorder, coded with Python.

# Overview
PyMacroRecorder works with a gui made with tkinter, so this is easier for users to interact with it.\
![image](https://github.com/LOUDO56/PyMacroRecord/assets/117168736/53632869-e661-42ca-9ee7-ee4e34fdd803)


# Features
- Free. No limitation. No "premium" purchase
- Repeat
- Speed
- Save
- Load
- Universal Files (work with .json)
- After playback options e.g Standby or shutdown computer
- Mouse Movement, click and keyboard recorded
- Smooth record of the mouse

# How is this working?
To start recording, you have to simply press the red button, or the `o` key (By default)\
From that, you can move your mouse, click and type on your keyboard and everything will be recorded. (You can chose to enable what will be recorded)
\
\
Then, to stop the record, you simply click on the black square or the `escape` key (By default)\
To play a record, you simply click on the green play icon or or the `p` key (By default)\
And to stop the playback, press the `escape` key (By default)
\
\
Here's some video to show you the proccess:

https://github.com/LOUDO56/PyMacroRecord/assets/117168736/bccd0da1-8102-4418-9458-acda114af2d4
https://github.com/LOUDO56/PyMacroRecord/assets/117168736/6159b161-fbe8-4d02-99a5-d9f3cb8580f3

# My computer detect this program as a Virus

This is normal, my program is totally unknown from Windows, so at first it can be considered like a Virus. But, this is a false positive don't worry.\
You can still check the code, this is Open Source.
\
\
But, if you are still unsure about that, you can follow these steps to avoid the setup.exe.

- Download the source code like this







![image](https://github.com/LOUDO56/PyMacroRecord/assets/117168736/575097b0-3eef-4461-ae16-0e16513a14d4)
- Extract it where you want
- Open the cmd by typing on your windows search "cmd"
- Type, **seperatly**
  ```bash
  pip install pynput
  pip install requests
  pip install Pillow
  pip install pystray
  ```
- After that, type `cmd` here, then press enter

![image](https://github.com/LOUDO56/PyMacroRecord/assets/117168736/89776a49-0cc4-4be0-ab54-62b6687d2b3b)

- And finally type: `python software.py`
- And boom! The software is now operate to use
