This is a simple python script that automatically manage your downloads

credits ---> https://github.com/tuomaskivioja/File-Downloads-Automator
youtube video ---> https://www.youtube.com/watch?v=NCvI-K0Gp90&ab_channel=InternetMadeCoder

I modified main so i can choose to save logs in a logfile or console

Then I added the .desktop file to autostart the script on system boot (I'm using ubuntu 20.04)
This file has to be put in ~/.config/autostart/ and the format should be like this:

[Desktop Entry]
Encoding=UTF-8
Name=MyScript
Comment=MyScript
Icon=gnome-info
Exec=python /home/your_path/script.py
Terminal=false
Type=Application
Categories=

X-GNOME-Autostart-enabled=true
X-GNOME-Autostart-Delay=0


credits ---> https://stackoverflow.com/questions/24518522/run-python-script-at-startup-in-ubuntu/25805612#25805612