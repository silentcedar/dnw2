dnw2(gcc version 5.4.0)

$ sudo apt-get install libusb-dev
 
$ gcc dnw2.c -o dnw2 -lusb
 
$ sudo mv dnw2 /usr/bin

$ sudo minicom -c on

$ sudo dnw2 /file

Done
