# Install John The Ripper

```
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install git build-essential libssl-dev zlib1g-dev yasm pkg-config libgmp-dev libpcap-dev libbz2-dev
$ cd /usr/share
$ git clone https://github.com/openwall/john.git
$ cd john/src
$ ./configure && make -s clean && make -sj4
$ export PATH=$PATH:/usr/share/john/run
$ alias john=/usr/share/john/run/john
```
