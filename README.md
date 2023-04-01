# poodle

cd vulnerabilities
cd testssl.sh
./testssl.sh website


if vulnerability is found 
nmap -sV --version-light --script ssl-poodle -p 443
nmap --script ssl-enum-ciphers -p 443
