# Xserver-on-AWS-EC2

If you will get error like below

Error: import apt_pkg ModuleNotFoundError: No module named 'apt_pkg'

Then follow below steps,

1) sudo apt remove --purge python3-apt
2) sudo apt autoclean
3) sudo apt install python3-apt
4) sudo apt install python3.10-distutils
5) curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
6) sudo python3.10 get-pip.py
