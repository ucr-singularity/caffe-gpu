Bootstrap: docker
From: bvlc/caffe:gpu

%post
# Update list of packages and install packages for ease of use.
apt-get update 
apt-get install -y vim
apt-get install -y tmux screen
apt-get install -y xterm

# OpenCV from pip, including contrib.  This makes the install MUCH faster.
# See https://pypi.python.org/pypi/opencv-contrib-python for capabilities 
# and limitations.  
pip install --no-cache-dir opencv-contrib-python
