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
    - [Enumerate Applications on Webserver](#enumerate-applications-on-webserver)
    - [Review Webpage Content for Information Leakage](#review-webpage-content-for-information-leakage)
    - [Identify Application Entry Points](#identify-application-entry-points)
    - [Map Execution Paths Through Application](#map-execution-paths-through-application)
- [Configuration and Deployment Management Testing](#configuration-and-deployment-management-testing)
    - [Test Network Infrastructure Configuration](#test-network-infrastructure-configuration)
    - [Test File Extensions Handling for Sensitive Information](#test-file-extensions-handling-for-sensitive-information)
    - [Review Old Backup and Unreferenced Files for Sensitive Information](#review-old-backup-and-unreferenced-files-for-sensitive-information)
    - [Enumerate Infrastructure and Application Admin Interfaces](#enumerate-infrastructure-and-application-admin-interfaces)
    - [Test HTTP Methods](#test-http-methods)
    - [Test HTTP Strict Transport Security](#test-http-strict-transport-security)
    - [Test RIA Cross Domain Policy](#test-ria-cross-domain-policy)
    - [Test File Permission](#test-file-permission)
    - [Test for Subdomain Takeover](#test-for-subdomain-takeover)
    - [Test Cloud Storage](#test-cloud-storage)
- [Identity Management Testing](#identity-management-testing)
    - [Test Role Definitions](#test-role-definitions)
    - [Test User Registration Process](#test-user-registration-process)
    - [Test Account Provisioning Process](#test-account-provisioning-process)
    - [Testing for Account Enumeration and Guessable User Account](#testing-for-account-enumeration-and-guessable-user-account)
    - [Testing for Weak or Unenforced Username Policy](#testing-for-weak-or-unenforced-username-policy)

## Information Gathering

### Conduct Search Engine Discovery Reconnaissance for Information Leakage
- [go-dork](https://thatoneprivacysite.net/vpn-section/) The fastest dork scanner written in Go.
- [ATSCAN SCANNER](https://github.com/AlisamTechnology/ATSCAN) Advanced Mass Search / Dork / Exploitation Scanner
- [DORK SCANNER](https://github.com/madhavmehndiratta/dorkScanner) A typical search engine dork scanner that scrapes search engines with queries that you provide in order to find vulnerable URLs.
- [XGDork?? - SQLi Google Dork Scanner](https://github.com/E4rr0r4/XGDork-2) A simple 'naive' python tool to find SQLi Vulnerable websites in the wild.
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

### Review Webpage Content for Information Leakage
- [Curl](https://github.com/curl/curl) is a command-line tool for transferring data specified with URL syntax.
- [Wget](https://github.com/mirror/wget) GNU Wget is a free utility for non-interactive download of files from the Web.
- [Burp Suite](https://portswigger.net/burp/enterprise)  is a set of tools used for penetration testing of web applications.
- [MetaFinder](https://github.com/Josue87/MetaFinder) Search for documents in a domain through Search Engines (Google, Bing and Baidu). The objective is to extract metadata.

### Identify Application Entry Points
- [Fiddler](https://www.telerik.com/fiddler) Fiddler is the beloved network proxy for countless developers. We look under the covers to explore various flavors of Fiddler and how it continues to serve developer needs.

### Map Execution Paths Through Application
- [gospider](https://github.com/jaeles-project/gospider) Fast web spider written in Go.
- [manspider](https://github.com/blacklanternsecurity/MANSPIDER) Spider entire networks for juicy files sitting on SMB shares. Search filenames or file content - regex supported!
- [Spider](https://github.com/buckyroberts/Spider) This is an open source, multi-threaded website crawler written in Python.
- [DotnetSpider](https://github.com/dotnetcore/DotnetSpider) DotnetSpider, a .NET Standard web crawling library. It is a lightweight, efficient, and fast high-level web crawling & scraping framework.
- [BurpExifToolScanner](https://github.com/LogicalTrust/BurpExifToolScanner) This Burp extension reads metadata from various filetypes (JPEG, PNG, PDF, DOC, XLS and much more) using ExifTool. Results are presented as Passive scan issues and Message editor tabs.

## Configuration and Deployment Management Testing

### Test Network Infrastructure Configuration
- [OP5](https://www.itrsgroup.com/products/network-monitoring-op5-monitor) A server monitor that enables capacity planning and trend analysis.
- [SolarWinds](https://www.solarwinds.com/server-configuration-monitor) SolarWinds??? server configuration monitor is a tool that can be used to detect any changes to the benchmark or a baseline configuration on both Windows and Linux servers..
- [Motadata](https://www.motadata.com/) A network, server, and application monitoring tool that tracks disk volumes and spare capacity, CPU usage, and memory utilization.

### Test File Extensions Handling for Sensitive Information
- [fuxploider](https://github.com/almandin/fuxploider) Fuxploider is an open source penetration testing tool that automates the process of detecting and exploiting file upload forms flaws. This tool is able to detect the file types allowed to be uploaded and is able to detect which technique will work best to upload web shells or any malicious file on the desired web server.
- [Image Upload Exploits](https://github.com/barrracud4/image-upload-exploits) This is a compilation of various files/attack vectors/exploits
- [razboynik](https://github.com/raskyer/razboynik)Razboynik wants to be the best reverse shell based on PHP backdoor

### Review Old Backup and Unreferenced Files for Sensitive Information
- [Backup-Finder](https://github.com/moeinfatehi/Backup-Finder) A burp suite extension that reviews backup, old, temporary, and unreferenced files on the webserver for sensitive information.
- [gHybridWebSearch](https://github.com/drgfragkos/gHybridWebSearch) Quick Hybrid Web Search for Old, Backup and Unreferenced Files for Sensitive Information

### Enumerate Infrastructure and Application Admin Interfaces
- [OKadminFinder](https://github.com/mIcHyAmRaNe/okadminfinder3) OKadminFinder is an Apache2 Licensed utility, rewritten in Python 3.x, for admins/pentesters who want to find admin panel of a website. There are many other tools but not as effective and secure. Yeah, Okadminfinder has the the ability to use tor and hide your identity
- [Breacher](https://github.com/s0md3v/Breacher) A script to find admin login pages and EAR vulnerabilites.

### Test HTTP Methods
- [HTSHELLS](https://github.com/wireghoul/htshells) Self contained web shells and other attacks via .htaccess files.
- [DotDotPwn](https://github.com/wireghoul/dotdotpwn) The Directory Traversal Fuzzer
- [defparam/smuggler](https://github.com/defparam/smuggler) An HTTP Request Smuggling / Desync testing tool written in Python 3
- [uploooadit](https://github.com/o-o-overflow/dc2020q-uploooadit) Author Walkthrough: https://youtu.be/F4khES7KBR4

### Test HTTP Strict Transport Security
- [sslstrip](https://github.com/moxie0/sslstrip) is a MITM tool that implements Moxie Marlinspike's SSL stripping attacks.
- [zaproxy_ssl](https://github.com/arthepsy/zaproxy_ssl) This is SSL/TLS termination plugin for OWASP Zed Attack Proxy (ZAP), when it is being used as transparent (man-in-the-middle) proxy. Plugin takes advantage of TLS extension SNI (Server Name Indication).

### Test RIA Cross Domain Policy
- [CrossDomain Scanner](https://github.com/mandatoryprogrammer/xpire-crossdomain-scanner) Scan domains' crossdomain.xml file for expired security issues.
- [MalaRIA-Proxy](https://github.com/eoftedal/MalaRIA-Proxy) Proof of concept code for a proxy abusing unrestricted cross domain policies.
- [Nikto](https://github.com/sullo/nikto) Nikto web server scanner
- [W3af](https://github.com/andresriancho/w3af) Web Application Attack and Audit Framework.

### Test File Permission
- [namei](https://man7.org/linux/man-pages/man1/namei.1.html) can also be used to recursively list file permissions.
- [ls](https://man7.org/linux/man-pages/man1/ls.1.html) command to check the file permissions

### Test for Subdomain Takeover
- [Takeover](https://github.com/m4ll0k/takeover) Sub-domain takeover vulnerability occur when a sub-domain (subdomain.example.com) is pointing to a service (e.g: GitHub, AWS/S3,..) that has been removed or deleted. This allows an attacker to set up a page on the service that was being used and point their page to that sub-domain.
- [NtHiM](https://github.com/TheBinitGhimire/NtHiM) NtHiM (Now, the Host is Mine!) is a command-line utility built with Rust, which enables security enthusiasts to discover subdomain takeover vulnerabilities in hostnames (domains and subdomains) from different organizations.

### Test Cloud Storage
- [hackingthe.cloude](https://github.com/Hacking-the-Cloud/hackingthe.cloud) Hacking the cloud is an encyclopedia of the attacks/tactics/techniques that offensive security professionals can use on their next cloud exploitation adventure. The goal is to share this knowledge with the security community to better defend cloud environments.
- [AWS Hacking](https://github.com/opendevsecops/guide-aws-hacking) This guide provides some basic instructions how to compromise AWS. The hope is that by knowing how to take advantage of various types of AWS weaknesses you will be verse enough to provide the correct countermeasures.

## Identity Management Testing

### Test Role Definitions
- [Autorize](https://github.com/Quitten/Autorize) Autorize is an automatic authorization enforcement detection extension for Burp Suite. It was written in Python by Barak Tawily, an application security expert.
- [ZAP???s Access Control Testing add-on](https://www.zaproxy.org/docs/desktop/addons/access-control-testing/) This add-on enables users to compare which parts of a web-application are available to some users, do access control testing and identify potential access control issues. It allows configuration of access rules and conducts a full attack aimed to help identify sections of a web application which are accessible by unauthorized clients.
- [sudo](https://github.com/sudo-project/sudo) Sudo is a program designed to allow a sysadmin to give limited root privileges to users and log root activity. The basic philosophy is to give as few privileges as possible but still allow people to get their work done.
- [userdel](https://github.com/shadow-maint/shadow/blob/master/src/userdel.c) The shadow-utils package includes the necessary programs for converting UNIX password files to the shadow password format, plus programs for managing user and group accounts. 

### Test User Registration Process
- [binproxy](https://github.com/nccgroup/BinProxy/) A proxy for arbitrary TCP connections.
- [datajackproxy](https://github.com/nccgroup/DatajackProxy) Datajack Proxy a tool to intercept non-HTTP traffic between a native application and a server. This would allow for communications interception and modification, even if encryption and certificate pinning were in use. This is done by hooking the application and intercepting calls to common socket and TLS libraries, and reading the data prior to encryption.
- [pappy-proxy](https://github.com/roglew/pappy-proxy) An intercepting proxy for web application testing.
- [mitmproxy](https://mitmproxy.org) SSL-capable man-in-the-middle HTTP proxy

### Test Account Provisioning Process
                                                    ??\_(???)_/??
The most thorough and accurate approach to completing this test is to conduct it manually, HTTP proxy tools could be also useful.

### Testing for Account Enumeration and Guessable User Account
         THE GAME PLAN IS TO GENERATE PASSWORDS AND USERNAMES USING TTPASSGEN AND ATTACK IT USING THC-HYDRA
- [ttpassgen](https://github.com/tp7309/TTPassGen) 	Highly flexible and scriptable password dictionary generator based on Python.
- [THC-Hydra](https://github.com/vanhauser-thc/thc-hydra) Number one of the biggest security holes are passwords, as every password security study shows.This tool is a proof of concept code, to give researchers and security consultants the possibility to show how easy it would be to gain unauthorized access from remote to a system.

## Testing for Weak or Unenforced Username Policy
- [Scythe](https://github.com/ChrisJohnRiley/Scythe) Account Enumerator is designed to make it simple to perform account enumeration as part of security testing. The framework offers the ability to easily create new modules (XML files) and speed up the process of testing.
- [smtp-enum](https://github.com/z0mbiehunt3r/smtp-enum) Enumerates email accounts through different methods like VRFY, EXPN and RCPT TO.

## Authentication Testing

### Testing for Credentials Transported over an Encrypted Channel
Test using wireshark if the website is leaking sensitive information, try https downgrade attacks. by downgrade i mean dropping the client from https to http, check if HSTS is enabled if not then we have an attack vector

### Testing for Default Credentials
Use thc-hydra or any password dictionary attack script along with a good world list, for example https://wiki.skullsecurity.org/index.php/Passwords and try to attack the website if its vulnerable to default creds it should not take long to find the users

### Testing for Weak Lock Out Mechanism
Some websites will lock you out if you try and fail three times in a row some will fail if u guess 5 consecutive times. websites which dosent are suseptable to brute force and dictionary attacks. hence websites must have a lock out mechanisms.

### Testing for Bypassing Authentication Schema
- [sqlmap](https://github.com/sqlmapproject/sqlmap) sqlmap is an open source penetration testing tool that automates the process of detecting and exploiting SQL injection flaws and taking over of database servers. 
- [PyBrute](https://github.com/rashidalabri/PyBrute)A python script to bruteforce post, get and cookie values.

### Testing for Vulnerable Remember Password
- [Clickjacking Tester](https://github.com/D4Vinci/Clickjacking-Tester) A python script designed to check if the website is vulnerable of clickjacking and creates a poc.
- [Bolt](https://github.com/s0md3v/Bolt) A dumb CSRF scanner

### Testing for Browser Cache Weaknesses
- [HackBrowserData](https://github.com/moonD4rk/HackBrowserData) HackBrowserData is an open-source tool that could help you decrypt data ( password|bookmark|cookie|history|credit card|download|localStorage|extension ) from the browser. It supports the most popular browsers on the market and runs on Windows, macOS and Linux.
-  [Track Incognito Browsing History](https://github.com/saiprasad2595/Incognito-browser-history) This small script helps you to get browsing history which you have searched even in incognito mode.

### Testing for Weak Password Policy
- [bruteforce-database](https://github.com/duyet/bruteforce-database) A Password dictionaries.
- [rischanlab/bruteforce_py](https://github.com/rischanlab/bruteforce_py) bruteforce with python, ssh bf, wordpress bf, cpanel bf, mysql bf, etc

### Testing for Weak Security Question Answer
                                                             ??\_(???)_/??
- [The OWASP Security Questions Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Choosing_and_Using_Security_Questions_Cheat_Sheet.html) While there are no acceptable uses of security questions in secure software, this cheat sheet provides guidance on how to choose strong security questions for legacy purposes.

### Testing for Weak Password Change or Reset Functionalities
                                                              ??\_(???)_/??
- [OWASP Forgot Password Cheat Sheet]https://cheatsheetseries.owasp.org/cheatsheets/Forgot_Password_Cheat_Sheet.html) Forgot Password Cheat Sheet

### Testing for Weaker Authentication in Alternative Channel
                                                              ??\_(???)_/??
Requires manual testing cannont automate 

### Authorization Testing

## Testing Directory Traversal File Include
- [Uploader](https://github.com/thec00n/Uploader) The Burp extension verifies if file uploads are vulnerable to directory traversal vulnerabilities.
- [Directory traversal tester](https://github.com/markchalloner/directory-traversal) Takes a series of paths on the STDIN and tests the against a filtering regular expression to ensure safety from directory traversal attacks.

## Testing for Bypassing Authorization Schema
- [OWASP Zed Attack Proxy (ZAP)](https://owasp.org/www-project-zap/) ZAP add-on: Access Control Testing
- [Port Swigger Burp Suite](https://portswigger.net) Burp extension: AuthMatrix, Burp extension: Autorize

## Testing for Privilege Escalation
- [GTFOBins](https://gtfobins.github.io) GTFOBins is a curated list of Unix binaries that can be used to bypass local security restrictions in misconfigured systems.
- [RogueWinRM](https://github.com/antonioCoco/RogueWinRM) RogueWinRM is a local privilege escalation exploit that allows to escalate from a Service account (with SeImpersonatePrivilege) to Local System account if WinRM service is not running (default on Win10 but NOT on Windows Server 2019).

## Testing for Insecure Direct Object References
- [Aimon-Srl-IDOR-PoC](https://github.com/kusky3/Aimon-Srl-IDOR-PoC) This linear processing bruteforce script will harvest 1 valid url every ~2000 requests at 2 requests per second. At 20 requests per second you'll harvest 1 valid url per minute or 1440 per day.
- [dore](https://github.com/naryal2580/dore) Direct Object Reference Exploitation
