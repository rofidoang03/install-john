# Install John The Ripper

1. sudo apt-get update
2. sudo apt-get upgrade
3. sudo apt-get install git build-essential libssl-dev zlib1g-dev yasm pkg-config libgmp-dev libpcap-dev libbz2-dev
4. cd /usr/share
5. git clone https://github.com/openwall/john.git
6. cd john/src
7. ./configure && make -s clean && make -sj4
8. export PATH=$PATH:/usr/share/john/run
9. alias john=/usr/share/john/run/john
