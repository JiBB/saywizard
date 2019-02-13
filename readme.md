# Say, Wizard!

Press shortcut keys to have your Mac read aloud phrases from a text file (or play short audio clips). 

Designed for running a Wizard of Oz voice interface test on OS X using `say` and `afplay`.

## USE

1. Download and unzip this script to your mac
2. Edit the text file 'script.txt' in the unzipped 'saywizard' folder with your phrases.
	* Lines surrounded in [] or {} will be interpreted as paths to audio files, which will be played using the built in `afplay` command.
	* [filename] indicates that the file should be played synchronously, like the spoken utterances.
	* {filename} indicates that the file should be played asynchronously, allowing other audio clips or spoken phrases to be triggered before it completes
3. Double-click startSayWizard.command to run a test (if mac security settings prevent this, right-click on it, Choose: Open With > Terminal, and click Open).
4. Press the relevant key to have your mac say your phrases. Close the window to quit. 

Written by @bensauer. 
Hat-tip to @jonesabi at Google for the idea.
Audio file support added by @JiBB.
