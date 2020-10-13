# File Tracker
Automatic Excel file generator for tracking of file changes in a folder
___

## Motivation
- Multiple collaborators contributing to a single shared folder (e.g. Dropbox, Google Drive) can make multiple changes over time, with files added constantly
- File tracking service is a paid feature for certain platforms (e.g. Dropbox)


## Solution
- In order to better track the file additions into Shared folders, and to quickly generate a full list of files in a shared folder, this Python script was written such that the file tracking process can be simplified

## How to use
- Place the file_activity_tracker.py in the parent directory you wish to track. The script will automatically crawl through all sub-directories to collate the list of files. 
- Run the .py file (in Command Prompt) in the future whenever you want to have an updated list of the recent changes
- Once the script has been run, an Excel file will automatically be generated in your parent directory
