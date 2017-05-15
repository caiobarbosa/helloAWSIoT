# Downloading Python 2.7.9 TGZ
# install AWS Device SDK for Python if not already installed
# Check to see if root CA file exists, download if not
sudo start.sh

# Install python 2.7.9
cd Python-2.7.9
./configure
make
make install

# Python default directory
/usr/local/lib/python2.7.9/bin/python
