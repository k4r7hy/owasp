# Awesome Tools For Owasp Top 10 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of hacking toolsssss.

## Preamble
This is a list of tools which are not included anywhere in the Owasp top 10 list. 

## How to use this list
Some items in this list could easily fit in more than one category, so to make sure you find what you're looking for please use `Ctrl + F` (or `Cmd + F` on macOS).

## Emoji
You will notice some items on this list have a :star2: next to them. Items with a :star2: represent the author's top pick for that category. This is an entirely opinionated rating from someone who doesn't know everything about every item on the list, so be sure to check out alternative options before assuming something is "the best". That said, I do explore and test every resource I add to this list wherever possible.

## Background Information
This is a list compiled by me. karthy.k

## Contents
- [Information Gathering](#information-gathering)
    - [Conduct Search Engine Discovery Reconnaissance for Information Leakage](#conduct-search-engine-discovery-reconnaissance-for-information-leakage)
    - [Fingerprint Web Server](#fingerprint-web-server)
    - [Review Webserver Metafiles for Information Leakage](#review-webserver-metafiles-for-information-leakage)

## Information Gathering

### Conduct Search Engine Discovery Reconnaissance for Information Leakage
- [go-dork](https://thatoneprivacysite.net/vpn-section/) The fastest dork scanner written in Go.
- [ATSCAN SCANNER](https://github.com/AlisamTechnology/ATSCAN) Advanced Mass Search / Dork / Exploitation Scanner
- [DORK SCANNER](https://github.com/madhavmehndiratta/dorkScanner) A typical search engine dork scanner that scrapes search engines with queries that you provide in order to find vulnerable URLs.
- [XGDork² - SQLi Google Dork Scanner](https://github.com/E4rr0r4/XGDork-2) A simple 'naive' python tool to find SQLi Vulnerable websites in the wild.
- [RobsScanner](https://github.com/NeloF4/RobsScanner) SIMPLE A ROBOTS.TXT SCANNER!
- [RobotScraper](https://github.com/robotshell/robotScraper) RobotScraper is a simple tool written in Python to check each of the paths found in the robots.txt file and what HTTP response code they return.

### Fingerprint Web Server
- [httprecon](https://www.computec.ch/projekte/httprecon/?) The goal is the highly accurate identification of given httpd implementations. This is very important within professional vulnerability analysis.
- [asp-audit](https://seclists.org/basics/2006/Sep/128) An ASP fingerprinting tool and vulnerability scanner.
- [blindelephant](https://blindelephant.sourceforge.net/) A web application fingerprinter. Attempts to discover the version of a (known) web application by comparing static files at known locations
- [httprint](http://www.net-square.com/httprint.html) A web server fingerprinting tool.
- [p0f](http://lcamtuf.coredump.cx/p0f3/) is a tool that utilizes an array of sophisticated, purely passive traffic fingerprinting mechanisms to identify the players behind any incidental TCP/IP communications (often as little as a single normal SYN) without interfering in any way.

### Review Webserver Metafiles for Information Leakage
- [MetaFinder](https://github.com/Josue87/MetaFinder) Search for documents in a domain through Search Engines (Google, Bing and Baidu). The objective is to extract metadata.
- [metagoofil](http://www.edge-security.com/metagoofil.php) An information gathering tool designed for extracting metadata of public documents.     
- [Curl](https://github.com/curl/curl) is a command-line tool for transferring data specified with URL syntax.

### Enumerate Applications on Webserver
- [Monsoon](https://github.com/RedTeamPentesting/monsoon) A fast HTTP enumerator that allows you to execute a large number of HTTP requests.
- [nullinux](https://github.com/m8sec/nullinux) is an internal penetration testing tool for Linux that can be used to enumerate OS information, domain information, shares, directories, and users through SMB.
- [Sublist3r](https://github.com/aboul3la/Sublist3r) is a python tool designed to enumerate subdomains of websites using OSINT
- [SubScraper](https://github.com/m8sec/subscraper) is a fast subdomain enumeration tool that uses a variety of techniques to find subdomains of a given target. Subdomain enumeration is especially helpful during penetration testing and bug bounty hunting to uncover an organization's attack surface.
- [WebBorer](https://github.com/Matir/webborer) is a directory-enumeration tool written in Go and targeting CLI usage.
