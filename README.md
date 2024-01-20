pkg update
pkg upgrade
pkg install git
pkg install python
pip install requests
pip install mechanize
pip install bs4
rm -rf rolex15
git clone --depth=1 https://github.com/rolex15/ROLEX.git

cd ROLEX
python rolex15.py
