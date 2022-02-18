# Game-220-Exercise-2
Source or create sounds given an asset list


## Assignment

A client is working on an Untitled Cat Game. An [Asset List](asset-list.tsv) has been provided. In it are several sounds needed for the demo level of the game. 

Source or create the sounds provided, and place the files in the `sound_assets` directory, and update the [Asset List](asset-list.tsv) file with the filename. 

### Audio asset requirements
- **Each file must be a 24bit, 44.1kHz Stereo .wav file.**
- Each filename should be human readable and use the `Asset Name` in it's filename:
    - For example, for an `Asset Name`: "Kitten Meow": 
        - `Kitten meow.wav`, `kitten-meow.wav` and or `KITTEN_MEOW.wav` are all acceptable.
        - `FSWEB__einen_katzenmeow__FREESOUNDZWEB-293847298347.wav` is not.
- Each file should be peak normalized to -0.5 dBFs
- Each file should have less than 0.5 seconds of silence at beginning
- Each file should have less than 1 seconds of silence at ending
- If providing a sound file with multiple versions of a sound, please separate each sound with at least 2 seconds of silence.


### Communication
Some `Designer Notes` are included for a couple sounds. Please read these.

If needed, please leave any notes on the sounds provided in the `Sound Designer Notes` field.

**Update `asset-list.tsv` with the filename, and any notes you have for the game designer.** Notes should be clear in meaning and directed toward the Game Designer in how to use the sound.

For example, this is a helpful note:

> "File includes multiple meows with 2 seconds of silence between each. Whole file is peak normalized to loudest sound in clip"

If you have any questions about the asset list, please open a github issue on this repo, and mention @nharsch in the comment.

## How to edit .tsv files

`.tsv` files are plain text files for tabular data. They can be opened with spreadsheet apps like Excel, Numbers, and/or Google Sheets. If you use spreadsheet apps to edit the Asset List, be sure that you Save As or Export a tsv file. 

Here's a [quick video](https://www.youtube.com/watch?v=XbXL-ZrprCw) on how to import and export TSV files with Google Sheets.

Since TSV files are plain text, they can be edited with any text editor. Each column in a row is separated by a tab, each row separated by a line break.
