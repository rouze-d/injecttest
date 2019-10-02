INJECTTEST : SIMPLE TEST INJECT PARAMETER FOR WEB VULNERABILITY

Injecttest is simple tool for inject web parameter for test vulnerability (GET/POST)

need:<br>
```
sudo gem install lolcat
sudo apt install curl
```

usage:<br>
```
bash injecttest.sh
bash injecttest.sh -m get -u http://localhost/index.php?id=3
bash injecttest.sh -m post -u http://localhost/index.php -d "page=5&id=1" <- use " close the data
```

for continue test target lists on file:<br>
```
for x in `cat target-list.txt`;do bash injecttest.sh -m get -u $x ;done
```
## Demo
[![asciicast](https://asciinema.org/a/254248.svg)](https://asciinema.org/a/254248)
sorry, old demo
