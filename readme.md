# Note
Original Script are https://github.com/Utinax/reload-skillbar I chage the color of the reloadskill so i reupload it

# Preview
https://streamable.com/s6ag9o

# Description
This mod adds the following:

- A taskbar which requires skill to get the outcome players want or fail.
- Includes exports so you can use it in other scripts.
- It Is used for hotwiring vehicles, repairing vehicles, etc. on No Pixel.
- Easy to use and set up.

# How to use
- Press the key, "E" within the lines for successful outcome.
- If you press the key, "E" outside of the lines you fail.

# Installation
Add script to your server resource file
Write 'start reload-skillbar' in your server.cfg

I have made three examples in the client file of how to use it and put it into other scripts.
Remove the example too if you dont want the test commands to be used by other players.

In the line
----------------------------------------------------------------
local finished = exports["reload-skillbar"]:taskBar(4000,math.random(5,15))
----------------------------------------------------------------
Edit the "4000" to how fast you want the bar to complete in. lower is faster, higher is slower.
Edit the "math.random(5,15)" to make the gaps bigger/smaller. lower is harder, higher is easier.

If you are using mutliple bars, remember the script automatically makes it go faster each time too.




























































































































































































































-- Ryder
