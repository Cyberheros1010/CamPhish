# What is CamPhish?
<p>CamPhish is techniques to take cam shots of target's phone front camera or PC webcam. CamPhish Hosts a fake website on in built PHP server and uses ngrok & serveo to generate a link which we will forward to the target, which can be used on over internet. website asks for camera permission and if the target allows it, this tool grab camshots of target's device</p>

## Features
<p>In this tool I added two automatic webpage templates for engaged target on webpage to get more picture of cam</p>
<ul>
  <li>Festival Wishing</li>
  <li>Live YouTube TV</li>
   <li>Online Meeting [Beta]</li>
</ul>
<p>simply enter festival name or youtube's video ID</p>

## This Tool Tested On :
<ul>
  <li>Kali Linux</li>
  <li>Termux</li>
  <li>MacOS</li>
  <li>Ubuntu</li>
  <li>Parrot Sec OS</li>
</ul>

# Installing and requirements
<p>This tool require PHP for webserver, SSH or serveo link. First run following command on your terminal</p>

```apt-get -y install php openssh git wget```

## Installing (Kali Linux/Termux):
```
git clone https://github.com/Cyberheros1010/CamPhish
cd CamPhish
bash camphish.sh
```
## Change Log:

<ul>
  <li>fixed: termux failed to get home directory</li>
  <li>Add support for Apple sillicon (M1/M2/M3 ARM64)</li>
  <li>Add support for arm64 like Raspberry Pi</li>
</ul>

#### For More Video subcribe <a href="http://youtube.com/@CywerLearning">CywerLearning YouTube Channel</a>
<p>CamPhish is created to help in penetration testing and it's not responsible for any misuse or illegal purposes.</p>
