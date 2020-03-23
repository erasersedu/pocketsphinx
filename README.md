# pocketsphinx

*From: https://www.robocupathomeedu.org/learn/turtlebot2-ros 

Install PocketSphinx:

> sudo apt-get install python-pip python-dev build-essential

> sudo pip install --upgrade pip

> sudo apt-get install libasound-dev

> sudo apt-get install portaudio19-dev

> sudo apt-get install python-pyaudio

> sudo pip install pyaudio

> sudo apt-get install swig

> sudo apt-get install pocketsphinx



Install ROS package for Pocketsphinx

> cd

> mkdir -p ~/erasersedu_ws/src

> cd ~/erasersedu_ws

> catkin_make

> cd ~/erasersedu_ws/src

> git clone https://github.com/erasersedu/pocketsphinx.git

> cd ~/erasersedu_ws

> catkin_make



Add language model

Download and copy the hub4wsj_sc_8k language model to

/usr/local/share/pocketsphinx/model/en-us/en-us/


https://sourceforge.net/projects/cmusphinx/files/Acoustic%20and%20Language%20Models/Archive/US%20English%20HUB4WSJ%20Acoustic%20Model/ 

> sudo mkdir -p /usr/local/share/pocketsphinx/model/en-us/en-us/
