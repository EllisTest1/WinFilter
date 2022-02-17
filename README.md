# WinFilter

This executable is intended to modify search a number of search settings across multiple browsers. Right now it has limited capability but can be expanded to accomodate more settings.



# To Use:

-Click through the WinFilter.exe application
-Click "Download" or "View Raw" to download the file
-Under the location it is downloaded, right-click the "WinFilter.exe" file and "Run as Administrator"
-You will get a security prompt asking you if it is ok to run, click "Ok"
-The script will run and automatically make changes to the computer for all users

*You only need to run this once and then restart the computer*




# To Verify:

If you want to make sure this is the intended file and it has not been modified, use the following instructions:

-Use Windows Explorer to open your downloads folder (or wherever the file was downloaded)
-In the search bar, type 'powershell' and press enter
  *A blue screen should pop up with a place for you to enter commands*
-From the command line, enter the following: Get-FileHash .\WinFilter.exe

If you did this correctly, you should have the following output under the Hash column, verifying it has not been changed:
7603F076D982CA225A41930630F710C607E81E6FC092822909C4E6C2F67B5C39
