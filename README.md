# 🐰 HopSSL

:fast_forward: HopSSL is a tool to quickly obtain TLS/SSL-related vulnerabilities info from a domain or a domainlist.


![image](https://user-images.githubusercontent.com/25567768/205352166-f30c35ac-00a8-4272-80be-9261ca4fbb21.png)


### Installing

Just git clone the repo

    sudo git clone https://github.com/suraei/hopSSL.git


Give execution permisions to the script

    sudo chmod +x ./hopSSL

And run the script

    ./hopSSL -h


### What vulnerabilities does hopSSL check for?


- [x] TLS 1.1 Weak Protocol

- [x] TLS 1.0 Weak Protocol

- [x] Weak Cipher Suites Supported

- [x] Forward Secrecy

- [x] Certificate Common Name Mismatch

- [x] Certificate Revoked

- [x] Missing HTTP Strict Transport Security Policy

- [x] Missing HTTP Header Information Disclosure

- [x] Different attacks:
    
    - [x] Heartbleed
    - [x] BEAST
    - [x] OpenSSL CSS Injection
    - [x] Tickedbleed
    - [x] ROBOT
    - [x] POODLE
    - [x] Zombie POODLE
    - [x] GOLDENDOODLE
    - [x] 0-Length Padding Oracle
    - [x] FREAK








