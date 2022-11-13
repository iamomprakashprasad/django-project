# Steps to setup Projects

git clone https://github.com/iamomprakashprasad/AddressBook.git
cd AddressBook
virtualenv -p python3 .venv
source .venv/bin/activate
pip install -r requirements.txt
git submodule init
git submodule update
