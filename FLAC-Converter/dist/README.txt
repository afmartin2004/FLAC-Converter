Welcome to the wav to flac converter!

Make sure python is properly downloaded before use. Verify by opening a cmd and using "python --version"

To set your source/destination directories simply open config.json then type in the directories you want.

Whenever you're ready, select wav_to_flac_conversion.exe and let it run! 

You can run any amount of instances simultaneously, just change the source/destination as desired and run again.

copy_failures.csv is a log of failed copies, unless you want to do anything specific with it you can mostly just ignore it.

Make sure you have properly installed ffmpeg before use.

You'll need to install pip, which you can find by downloading the get-pip.py script from https://pip.pypa.io/en/stable/installation

Next open a cmd and run "python get-pip.py". Verify your installation by running "pip --version".

If the .exe isn't working properly, make your own by opening a cmd and writing "pip install pyinstaller".

Once installed, cd into the folder that contains wav_to_flac_conversion.py

Then, run "pyinstaller --onefile wav_to_flac_conversion.py". The .exe will be in the "dist" folder
