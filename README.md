# Nice SSL

:memo: Lil SSL/TLS vuln checker

- [x] Test Certificate Common Name Mismatch

- [x] Test Certificate Expired

- [x] Test TLS 1.1 Weak Protocol

- [x] Test TLS 1.0 Weak Protocol

- [x] Test Weak Cipher Suites Supported

- [x] Test Missing HTTP Strict Transport Security Policy


## Getting Started

U need to install https://github.com/drwetter/testssl.sh

### Installing

Just git clone the repo

    sudo git clone https://github.com/suraei/nicessl.git


Give execution permisions to the script

    sudo chmod +x ./nicessl

And run the script, u can use a URL or a Domain list

    ./nicessl -t <URL>|<list>






