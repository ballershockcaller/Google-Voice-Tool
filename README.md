After years of trying to find a way to leverage my Google Takeout SMS history from Voice, I've hired a developer who has created a tool for me.  If you would like to donate for this tool, you can buy me a cup of coffee. https://www.buymeacoffee.com/voicesmstool

The script parses your Google Voice SMS history from Google Takeout, and gives you a single .xml file that can be read by SMS Backup and Restore. From there you can import your Google Voice text message history so Google Messages can read it.

Necessary tools:
1. Windows PC
2. Google Takeout
3. SMS Backup and Restore
4. Method of getting a file to your phone (Google Drive, Dropbox, or USB cable)


Steps:

1. Request your Google Voice history via Google Takeout. Request it to be all in one large file (not 2GB chunks)
2. Download the zip file from Google Takeout.
3. Unzip your Google Voice history to an easily found location (C:\Voice). Note that text messages are in the "Calls" folder.
4. Copy all the .jpg images to a separate folder, called "Images".
5. Disable "Real-Time protection" on your antivirus. 
6. Open the zip file with GV Import Tool.exe, and run the .exe file. 
7. In the "Input Files Folder Path" box, click "browse" and select the path where your "Calls" folder is stored (like C:\Voice\Calls).
8. In the "Input Images Folder Path", click "browse" and select the path where your "Calls" folder is stored (like C:\Voice\Images).
9. In the "Output Filename/File Path" box, click "browse" and select the location where you want the output file to be created. 
10. Click "Convert" and wait until the file is created. This may take some time, depending on how large your SMS history is.
11. Copy the file to your phone (use Google Drive, Dropbox, or copy via USB cable)
12. Install SMS Backup and Restore on your phone, click the 3  horizontal lines in the top right corner then click "Restore".
13. Browse to the .xml file in your Google Drive, Dropbox, or saved locally on your phone. 
14. SMS Backup and Restore may ask you to change your default messaging app temporarily. Go ahead and do that.
15. Let the import process run. 
16. Once the import process is complete, change the default messages app from SMS Backup and Restore to Google Messages.
17. You may need to clear the cache or storage of your Google Messages app. 

Some caveats:

1. Use at your own risk! I'm not responsible if you mess up your phone or messaging history in some way. 
2. Make sure your messages inside Google Messages are backed up first (if you want to keep those).
3. This is only for SMS messages, not call logs or voicemails or anything else.
4. Only .jpg images will be imported, not video files or GIFs.
   
Hope you found this helpful. If so, feel free to buy me a cup of coffee. https://www.buymeacoffee.com/voicesmstool
