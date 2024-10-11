# ipsubping

#Automate nmap for all ip
for ip in $(cat ip.txt); do nmap $ip& done
