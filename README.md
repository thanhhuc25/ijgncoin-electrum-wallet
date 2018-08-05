Electrum-IJC - Lightweight Ijgncoin client
==========================================

Build Mac OSX
------
```
./contrib/build-osx/make_osx
virtualenv -p python3 env
source env/bin/activate
python setup.py install
brew install pyqt5
pip install PyQt5
pip install scrypt

```
run: `python run_electrum`

Warning
--------
If you have use Electrum-LTC wallet before, please backup your wallet, because this program will overwrite your Electrum-LTC wallet data and you will lose your Litecoin forever.

We are planning to fix this issue.
