# rpi-emulationstation-music
bootgames is a little bash script I made for playing music behind emulationstation on the raspberry pi using vlc.

- Put your music/videos into /home/pi/Music (the videos are not displayed)
- Put the script in an easy to remember place (I put the script in /bin)
- Run the bootgames script from the terminal that the rpi can boot to (I set my rpi to boot to the shell so that I can choose between emulationstation and startx. With the bootgames file in /bin I am able to simply run the command "bootgames" without the quotes and the script is run)
- You will be asked whether you want music or not. no just starts emulationstation. yes asks which song from your Music folder you wish to play
- Pick your music. The first music screen lets you choose one song to play on loop or choose to play them all on loop. If you select multiple then you can choose specific songs to make and play a playlist on loop.
- After song is chosen then the music will play and emulationstation will start. the music should still be playing. You can change the volume of the music through the volume setting in the emulationstation start menu (press enter > audio settings)
- If you selected no for music then your game music will play. If you selected yes then your game music will be muted (currently only works with retroarch games).


I have an rpi2 and some of my songs freeze for a bit once or twice. Not often. I would assume that the rpi1 would freeze more and the rpi3 would perform just fine. I wouldn't recommend running very demanding games though.
