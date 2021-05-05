# Win-Sc-utility
This is how I quickly take screenshots. If you have any better idea, please let me know, since this has been bothering me for years 🤔😐

## Background: 
* Uses a simple windows batch script to anonymously open the very useful and beautiful nircmd application and ask it to take screenshot and save it to a folder.
* I use it to take notes from my online class. 
* I couldn't use any key mappings, because I was already using all the keys on my board.
* Required:
Nircmd windows application   
https://www.nirsoft.net/utils/nircmd.html   
Scroll down you will see download link.   
Download the zip. Extract them to a convenient location. I copied them them to my Program Files folder.   
Make sure you add the location address to the path environment variable so that nircmd can be accessed from anywhere in windows.   


Steps:
Edit the .bat file to your need and run.

Pro tip, How I've done: 🤭
1. In your desktop, right click, create a shortcut,
Paste the code in uploaded script, which is (Edit it as per your requirement):
Before that, make sure you have downloaded the nircmd application and added it's location to the "PATH" environment variable of your system.
> nircmd.exe savescreenshot "D:\ClassNotes\NoteS~$currdate.MM_dd_yyyy$-~$currtime.HH_mm_ss$.jpg" 
2. Save and Drag it to your taskbar, So that whenever you need to take sc, just click that button.
3. You can also change the icon of the shortcut from it's settings, for more fun. (I have that mouse and earth icon)   

This works on the idea that you can execute commands through shortcut files also. So you can pass any cmd commands you use in the shortcut input field while creating the shortcut.   


Initially I planned to write a vb script for pressing Windows and Printscreen key to take sc and save it in screenshots folder, but I couldn't find the keycode for start button.   
That'd be a better idea I guess, since it won't then need the help of any 3rd party application.   

## Add on:
Fire ants destroyed some few important keys on my laptop keyboard. It was also incovenient for me to use on screen keyboard.
So I used nircmd to create shortcut for those keys and added them to a folder and then to my taskbar. So each time I click that shorctut for a particular key that key which is stored in a text file get copied to my clipbard so that I can paste it.
