# Introduction to OSINT | BlueTeam.Security

## Google Dorks

### Format
**operator:keyword**
ex: filetype:pdf

### Usage
- Retrieving files from domains.
- Finding hidden web pages and login portals.
- Subdomain enumeration.
- And more!


### Specifying File Types
#### Search_Phrase SPACE filetype:*
![image](https://hackmd.io/_uploads/BkUEf1fy0.jpg)
![image](https://github.com/YS-McGee/OSINT/assets/61614098/0882a671-b331-4a1e-9b1b-9359cf7bf6ed)


### Subdomain Enummeration
#### Look for sites including ferrari[.]com, but excludes www.ferrari[.]com 

![image](https://hackmd.io/_uploads/S1r77kMJC.png)

### Keyword Searching
#### *inurl:[VALUE]*

![image](https://hackmd.io/_uploads/r1-EUyMkA.jpg)

### More information
https://securitytrails.com/blog/google-hacking-techniques

## Defense Against Google Dorks

### Geofencing and IP Whitelisting

### Crawler Restrictions
Create a *robots.txt* to disallow any crawlers from indexing any part of the website.
```
User-agent: *
Disallow: /
```
> The above file will disallow any (*) user-agents from crawling any directory on the website (such as /images/ or /training/)

## Reverse Image Search

### TinEye

> https://tineye.com

### Google Image Search

## Tweetdeck (Deprecated)

> Elon Musk's rebranded "XPro" is now a subscribers-only platform. Credit: Dan Kitwood/Getty Images. The latest change to Elon Musk's X? TweetDeck — rebranded as XPro — is now a paid service, no longer free to use.

> This is a section of my TweetDeck that I use at work (at time of writing, Sept 2019). My primary use for this is to monitor for vulnerabilities affecting common software (such as browsers), major operation systems (in this case Windows 10), and threat actors.

