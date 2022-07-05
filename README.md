![4-Subbrute-results](https://user-images.githubusercontent.com/106522935/177383529-28d72bcb-c0b7-4812-ab27-49a93ec5fad4.png)


# Sublist3r

Footprinting (Teconnaissance) Tool

Sublist3r is a Python subdomain discovery tool that has been designed to enumerate subdomains of websites using data from publicly available sources and brute force techniques. The public sources consist of a wide range of popular search engines such as Google, Yahoo, Bing, Baidu, Ask and also Netcraft, Virustotal, ThreatCrowd, DNSdumpster and ReverseDNS to discover subdomains.

You can also brute force subdomains using an integrated tool named Subbrute. Subbrute is a DNS meta-query spider that enumerates DNS records and subdomains by using an extensive wordlist. This tool uses open resolvers to avoid rate limiting issues that prevent Subbrute from completing the list or attempting all entries.

# Installation

$ git clone https://github.com/aboul3la/Sublist3r

$ cd Sublist3r

$ sudo pip install -r requirements.txt

# How to use it?

Run it using python

$ python sublist3r.py
or
$ python sublist3r.py  [options] [website name]

# Option’s

-d –domain To enumerate subdomains of Domain name

-b –brute-force Include subbrute brute-force module

-p –ports Scan subdomains that are in specific tcp ports

-v –verbose Real-time results display in the verbose mode

-t –threads Threads to use for subbrute brute-force

-e –engines Search engines will be specified with a comma-separated

-o –output Save the output into a text file

-h –help Show the help message before exit

# Examples

To list all the basic options use:
python sublist3r.py -h

To enumerate subdomains of specific domain:
python sublist3r.py -d example.com

To enumerate subdomains of a specific domain and show only subdomains with open ports 80 and 443 :
python sublist3r.py -d example.com -p 80,443

To enumerate subdomains of a specific domain and show the real-time results
python sublist3r.py -v -d example.com

To enumerate subdomains and enable the brute-force module:
python sublist3r.py -b -d example.com

To enumerate subdomains and use specific engines on demands
python sublist3r.py -e google,yahoo,virustotal -d example.com

# For Termux users

# Installation :

$ apt update

$ apt upgrade

$ apt install git

$ apt install python2

$ git clone https://github.com/aboul3la/Sublist3r

$ cd Sublist3r

$ pip2 install requirements.txt

$ pip2 install requests

Run :

$ python2 sublist3r.py

$ python2 sublist3r.py -h

it shows all options how you can use this tool

$ python2 sublist3r.py -d site.com

-d = domain name

# Summary

Hope you have learned A step by step guide on – What is Sublister? | How to install and run it? | get hands-on How to use it? To know more about Subdomain Takeover.

# Thanks for reading !

# Happy Hacking !

# ☞Social Media Links:
Facebook: https://www.facebook.com/manojshrestha00

Instragram: https://www.instagram.com/manojshrestha00

Twitter: https://www.twitter.com/manojshrestha00
