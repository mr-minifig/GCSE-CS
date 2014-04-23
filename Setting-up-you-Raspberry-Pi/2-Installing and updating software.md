#Installing and updating Software

The Raspberry Pi runs an operating system called Linux which is free and fast. 
One of the first things we need to do is learn how to keep the software on it up to date and install new software.

##Updating Software
Open up an LXTerminal Window 
[!alt text](http://images.jeremymorgan.com/raspberry-pi-linux-2.png "LXterminal")

Type the following command and press enter:
```bash
sudo apt-get update
```
This connects to the internet and checks if any software updates are available.

Next enter:
```bash
sudo apt-get upgrade
```

Which will install any available updates for software you have installed

The process may take some time depending on when the Pi was last updated. You should run this command regularly to ensure your Pi is kept up to date.

##Installing new software.
With an LXTerminal window open you can install new software quite easily.
We need to install a piece of software called **git** to do so we run:
```bash
sudo apt-get install git
```

We can also install several pieces at once, try:
```
sudo apt-get install tightvncserver avahi
```
