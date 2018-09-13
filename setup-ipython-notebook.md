# Procedure to Install IPython Notebook

## Descriptions


```bash

# run the following with sudo

sudo apt-get install virtualenv build-essential
sudo apt-get install python-dev python-pip

mkdir ~/breaking
cd ~/breaking

pip install beautifulsoup4
pip install selenium

# download and install geckodriver (https://stackinstall.com/how-to-install-geckodriver-on-ubuntu-16-04/)

cd "$HOME"
wget -O "geckodriver-v0.20.0-linux64.tar.gz" "https://github.com/mozilla/geckodriver/releases/download/v0.20.0/geckodriver-v0.20.0-linux64.tar.gz"
tar xf "geckodriver-v0.20.0-linux64.tar.gz"
sudo cp "geckodriver" "/usr/local/bin/geckodriver"
sudo chmod +x "/usr/local/bin/geckodriver"
rm -f "geckodriver"
rm -f "geckodriver-v0.20.0-linux64.tar.gz"


# pip install numpy scipy matplotlib

# Due to Laziness, use apt-get to install numpy scipy matplotlib and opencv

sudo apt-get install python-numpy python-scipy python-matplotlib python-pandas python-sympy python-nose python-opencv ipython-notebook



```
