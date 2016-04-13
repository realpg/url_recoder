apt-get install libpcap-dev -y
gcc url_recoder.c -lpcap -o url_recoder 
./url_recoder eth0
