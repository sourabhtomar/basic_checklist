# basic_checklist
If you are a beginner then you should definitely check this out 

1-> Find a scope 
2-> If its API based then first read documentation (it will surely help you out)
3-> find subdomains (as many subdomains as you can) 
  FOR FINDING SUBDOMAINS ---> (some effective tools from my side)
  a: Assetfinder
  b: Findomain
  c: Amass
  d: Subfinder
  e: Sublist3r
  f: crt.sh
  g: certspotter
  h:  chaos.projectdiscover.io etc

4 -> Find unique and alive subdomains
5 -> screenshot them all
6 -> go to main website and use it like a normal user (do not hunt just capture in burpsuite) and understand the 
program well.

Information Gathering
 Manually explore the site
 Spider/crawl for missed or hidden content
 Check for files that expose content, such as robots.txt, sitemap.xml, .DS_Store
 Check the caches of major search engines for publicly accessible sites
 Check for differences in content based on User Agent (eg, Mobile sites, access as a Search engine Crawler)
 Perform Web Application Fingerprinting
 Identify technologies used
 Identify user roles
 Identify application entry points
 Identify client-side code
 Identify multiple versions/channels (e.g. web, mobile web, mobile app, web services)
 Identify co-hosted and related applications
 Identify all hostnames and ports
 Identify third-party hosted content

7-> If you understand the program better then you are good to go.
  
  Here is some checklists that will help you for finding some low hanging fruites (sometimes p3 or p2)

First checklist -> https://github.com/KathanP19/HowToHunt 
Second checklist -> https://spinthehack.in/bug-hunting-methodology-and-bug-hunting-checklist/
Third checklist -> https://github.com/KathanP19/HowToHunt/blob/master/CheckList/Web_Checklist_by_Chintan_Gurjar.pdf
Fourth checklist -> https://alike-lantern-72d.notion.site/Web-Application-Penetration-Testing-Checklist-4792d95add7d4ffd85dd50a5f50659c6
Fifth checklist -> https://pentestbook.six2dez.com/others/web-checklist
Sixth checklist -> https://github.com/6vr/Bug-Bounty-Tips
Seventh checklist -> https://github.com/0xmaximus/Galaxy-Bugbounty-Checklist

I think it would be enough for checklist


For directory and port fuzzing

Nmap,naabu,rustscan scan (these three are port scanning tools)
 Burp crawler
 ffuf (directory and file fuzzing)
 hakrawler/gau/paramspider
 Linkfinder


Authentication based finding
 Test for user enumeration
 Test for authentication bypass
 Test for bruteforce protection
 Test password quality rules
 Test remember me functionality
 Test for autocomplete on password forms/input
 Test password reset and/or recovery
 Test password change process
 Test CAPTCHA
 Test multi factor authentication
 Test for logout functionality presence
 Test for cache management on HTTP (eg Pragma, Expires, Max-age)
 Test for default logins
 Test for user-accessible authentication history
 Test for out-of channel notification of account lockouts and successful password changes
 Test for consistent authentication across applications with shared authentication schema / SSO


Data Validation
 Test for Reflected Cross Site Scripting
 Test for Stored Cross Site Scripting
 Test for DOM based Cross Site Scripting
 Test for Cross Site Flashing
 Test for HTML Injection
 Test for SQL Injection
 Test for LDAP Injection
 Test for ORM Injection
 Test for XML Injection
 Test for XXE Injection
 Test for SSI Injection
 Test for XPath Injection
 Test for XQuery Injection
 Test for IMAP/SMTP Injection
 Test for Code Injection
 Test for Expression Language Injection
 Test for Command Injection
 Test for Overflow (Stack, Heap and Integer)
 Test for Format String
 Test for incubated vulnerabilities
 Test for HTTP Splitting/Smuggling
 Test for HTTP Verb Tampering
 Test for Open Redirection
 Test for Local File Inclusion
 Test for Remote File Inclusion
 Compare client-side and server-side validation rules
 Test for NoSQL injection
 Test for HTTP parameter pollution
 Test for auto-binding
 Test for Mass Assignment

Will update this checklist 
