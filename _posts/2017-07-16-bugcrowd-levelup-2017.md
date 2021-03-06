---
layout: post
title: "Bugcrowd LevelUp 2017"
tags:
- security
- minddump
- bugcrowd
- bugbounty
- conference
categories:
- devalias
disqus: true
webmention: true
crosspost_to_medium: false
---
Today was [LevelUp, Bugcrowd's first Virtual Hacking Conference](https://pages.bugcrowd.com/level-up-virtual-hacking-conference). With 2 seperate streams over 8 hours, the [schedule was jammed packed](https://docs.google.com/spreadsheets/d/1nKnwk3qVtoQlHs32atwwTIWjOHZ9kjnbwpPTJVfvKeo/pubhtml?gid=0&single=true) with interesting talks and knowledge drops across topics including web, mobile, IoT and even car hacking.

Waking up at 1:30am (AEST) to get some Bulletproof coffee in before it started, I think I briefly moved once from the couch in the whole session. The rest was solid and intent focus on the topics, trying to keep up with all of the amazing content, while also taking notes (~1200 lines worth!), and [dropping out tweets](https://twitter.com/search?l=&q=%23ItTakesACrowd%20from%3A_devalias&src=typd&lang=en) at the same time. I don't think i've been as engaged or intently focussed on something for such a long period in a long time. Testament to the quality of the conference!

One of the common themes of the conference today (besides all the tech knowledge) was that of community and sharing. This is something that speaks to my core, and one of the things that I love about the security industry. How people can be so open, be willing to share their knowledge, and humbly learn in return. Such a great way to bring everyone up across the board, and super grateful for it.

There are a few places you can get connected with bug bounty hunters / security researchers that I wanted to list here:

* Twitter!
    * This sort of goes without saying given how active the security community is here. But with regards to this conference and related things, check out Bugcrowd's hashtag: [#ItTakesACrowd](https://twitter.com/search?q=%23ItTakesACrowd)
    * Also make sure to follow [@Bugcrowd](https://twitter.com/Bugcrowd), and if you'd like to see more from me (when I rarely but occasionally tweet) you can find me at [@_devalias](https://twitter.com/_devalias) (always feel free to say hi!)
* [Bug Bounty World](http://bugbountyworld.com/)
    * A community for bug-bounty enthusiasts, open to all.
    * Twitter: [@bugbounty_world](https://twitter.com/bugbounty_world) ([#bugbountyworld](https://twitter.com/search?q=%23bugbountyworld))
* [Bug Bounty Forum](https://bugbountyforum.com/)
    * A community of bug bounty researchers, including slack channel and more!
    * Twitter: [@bugbountyforum](https://twitter.com/bugbountyforum)
    * GitHub: [bugbountyforum](https://github.com/bugbountyforum/)
* [Bugcrowd Forum](https://forum.bugcrowd.com/)
    * Make sure to also check out the discussions over at the Bugcrowd forum.

In light of that theme, I wanted to share what I have from today, not only so I remember what I saw, but so that everyone else has the opportunity to see some of the great stuff that was presented today. This post will be largely my raw and unedited notes, with any future posts likely to be more structured/refined.

It's also worth noting that every talk from both streams was recorded, and will be published to YouTube within the next week or so, so keep an eye out for that! I'll probably update this page when they're released, and I intend to write some more thorough blog posts based on each session when I have a chance to go back through it all at a slower pace, so keep an eye out for those!

Do you have any awesome resources, comments, or things to add? I'd love for you to share in the comments below!

## Overview of this post

* [Videos](#videos)
* [Schedule](#schedule)
    * Stream 1
    * Stream 2
* [Raw Notes](#raw-notes)
    * Welcome + Kickoff (Sam Houston)
    * How to Hack Web v2 (Jason Haddix)
    * How to Fail at Bug Bounty (Caleb Kinney)
    * Giving Back to the Community (ZSeano)
    * Doing Recon Like a Boss (Ben Sadeghipour)
    * Hidden in Plain Site: Disclosing Information via Your APIs (Peter Yaworski)
    * Targeting for Bug Bounty Research (Matthew Conway)
    * How does unicode affect our Security? (Christopher Bleckmann-Dreher, @schniggie)
    * Hacking Internet of Things for Bug Bounties (Aditya Gupta)
    * Intro to Car Hacking (Alan Mond)
* [Thanks!](#thanks)

## <a name="videos"></a>Videos

* YouTube
    * [Bugcrowd](https://www.youtube.com/channel/UCo1NHk_bgbAbDBc4JinrXww)
    * [Levelup 2017 - Full Playlist of all sessions](https://www.youtube.com/playlist?list=PLIK9nm3mu-S5InvR-myOS7hnae8w4EPFV)
    * [LevelUp 2017 - Stream 1 (raw)](https://www.youtube.com/watch?v=IiMDDaZPx7k)
* Facebook
    * [LevelUp 2017 - Stream 2 (Part 1, raw)](https://www.facebook.com/Bugcrowd/videos/1515474031828959/)
    * [LevelUp 2017 - Stream 2 (Part 2, raw)](https://www.facebook.com/Bugcrowd/videos/1515710201805342/)
        * Starts a little bit before "Do you like fuzzing? Why I built fuzzapi to fuzz REST APIs for profit." by Abhijeth Dugginapeddi

## <a name="schedule"></a>Schedule

Just in case [the schedule](https://docs.google.com/spreadsheets/d/1nKnwk3qVtoQlHs32atwwTIWjOHZ9kjnbwpPTJVfvKeo/pubhtml?gid=0&single=true) goes offline sometime in the future, here are the main bits for posterity:

### Stream 1

* Welcome
    * Welcome + Kickoff, Sam Houston (20min)
    * Welcome, State of Bug Bounty & The Future of Crowdsourced Securit, Casey Ellis (60min)
    * How to Hack Web v2, Jason Haddix (50min)
* General Bug bounty and Web Hacking
    * How to Fail at Bug Bounty, Caleb Kinney (25min)
    * Giving Back to the Community, ZSeano (45min)
    * Doing Recon Like a Boss, Ben Sadeghipour (25min)
* Web Hacking
    * Hidden in Plain Site: Disclosing Information via Your APIs, Peter Yaworski (25min)
    * Targeting for Bug Bounty Research, Matthew Conway (25min)
    * How does unicode affect our Security?, Christopher Bleckmann-Dreher @schniggie (45min)
* Hardware Hacking
    * Hacking Internet of Things for Bug Bounties, Aditya Gupta (45min)
    * Intro to Car Hacking, Alan Mond (25min)
    * MarkDoom: How I Hacked Every Major IDE in 2 Weeks, Matt Austin (45min)
* Ending Ceremony
    * Final Words, JHaddix w/intro from Sam (30min)

### Stream 2

* Web Hacking and Mobile Hacking
    * OWASP iGoat – A Self Learning Tool for iOS App Pentesting and Security, Swaroop Yermalkar (25min)
    * Esoteric sub-domain enumeration techniques, Bharath (45min)
    * Finding Hidden Gems in Old Programs, Yappare (25min)
* Mobile Hacking and API Hacking
    * Breaking Mobile App Protection Mechanisms, Ben Actis (45min)
    * Reverse Engineering Mobile Apps, Emily Walls (25min)
    * Identifying and Evading Android Protections, Tim Strazzere (45min)
    * Do you like fuzzing? Why I built fuzzapi to fuzz REST APIs for profit, Abhijeth Dugginapeddi (25min)
    * Advanced Android Bug Bounty skills, Ben Actis (45min)
* Browser Hacking
    * Browser Exploitation for Fun and Profit, Dhiraj Mishra (25min)

## <a name="raw-notes"></a>Raw Notes

The following are my raw notes from todays session. Apologies in advance for the format..

### Welcome + Kickoff  (Sam Houston)

{% raw %}
<pre>
http://twitter.com/samhouston

Stream 1, mostly web, switches to hardware later
Stream 2, mostly mobile hacking

Tweet with #ItTakesACrowd and @BugCrowd

http://www.bugbountyworld.com, new slack, bugcrowd channel

## Welcome, State of Bug Bounty & The Future of Crowdsourced Security (Casey Ellis)

Casey Ellis, Founder/CEO of Bugcrowd

https://twitter.com/caseyjohnellis

casey@bugcrowd.com

@caseyjohnellis #ItTakesACrowd
</pre>
{% endraw %}

### How to Hack Web v2 (Jason Haddix)

{% raw %}
<pre>
Head of Trust and Security at Bugcrowd

https://twitter.com/jhaddix
https://securityaegis.com
https://blog.bugcrowd.com/author/jason-haddix

The Bug Hunters Methodology (Def Con 23)
    distilling a lot of learnings over the years
  google it for the video

The Bug Hunters Methodology v2
  XXS, SSTI, SSRF, code/command injection, fuzzing, tooling
  API testing, object deserialisation, XXE in v2.5

Light reading:
  Web Application Hackers Handbook
  OWASP Testing Guide
  Web Hacking 101
  Breaking into information security
  Mastering modern web penetration esting

Discovery
  Enumall (recon-ng, alt-dns wrapper, etc)

Sub scraping
  https://github.com/aboul3la/Sublist3r
    scrapes search engines/etc for mentions of domains
    sources are different from enumall

  anshumanbh/brutesubs
    set of docker images that include multiple tools
      inc enumall and sublister
      along with gobuster and altdns
      run against a domain you want
      need to modify config/docker scripts to add custom bits
      disable bruteforce for enumall
    did a presentation about this topic recently (TODO)

  mandatoryprogrammer/cloudflare_enum
  anshumanbh/censys.py

Subdomain bruteforcing
  Like: subbrute, gobuster, massdns, dns-parallel-prober, blacksheepwall
  gobuster (21m) and massdns (1.5m) are quick
  massdns found more quicker, but more false positives
  could feed massdns stuff into gobuster to reduce?

  blechschmidt/massdns

  all.txt: https://gist.github.com/jhaddix/86A06C5DC309D085/80A018C66354A056
           https://gist.github.com/jhaddix/86a06c5dc309d08580a018c66354a056
    list of all the dns brute lists in one

Acquisitions
  crunchbase
    protected by distil bot protection
    can write a tool to beat that

Port scanning
  nmap is great, but don't try and scan 65536 hosts with the default port list
  massscan
    doesn't provide a default port list
    use nmaps (giant list of ports)
      https://twitter.com/_devalias/status/886280729327312896

Visual identification
  https://github.com/ChrisTruncer/EyeWitness
    checks HTTP(S), RDP and a couple of other protocols too
  https://github.com/breenmachine/httpscreenshot
    another tool

Platform identification and CVE searching
  retire.js, wappalyzer, builtwith

  https://vulners.com/
    combine a lot of CVE/etc sources

  https://github.com/vulnersCom/burp-vulners-scanner
    search in scope domains
    find versions/etc
    link to vulns for lower than that version
    get list of CVE's that might be related

Content discovery/directory bruting
  TBHMv1
    wordlists: seclists, raft, digger_wordlists
    patator
    wpscan
    cmsmap
  
  https://github.com/maurosoria/dirsearch

  
   https://github.com/OJ/gobuster
    super fast

  burp content discovery
    in burp pro
    pretty good, but sort of bogs down java

  danielmiessler/RobotsDisallowed

Parameter bruting?
  https://github.com/maK-/parameth
    This tool can be used to brute discover GET and POST parameters

PortSwigger/backslash-powered-scanner
  /resources/params
    good wordlist

XSS
  TBHMv1
    polyglot strings, seclists, flash reversing, common input vectors
  TBHMv2
    blind XSS
      sleepy puppy (python)
      xss hunter (python)
      ground control (ruby, small)
    polyglots
    xss mindmap

  Blind XSS
    input may eventually end up on some backend app and executes somewhere
    use a payload that loads JS
    need a framework to catch it

    XSSHunter
      payload gathers a lot of really useful data

Polyglots
  injection string that executes in multuple contexts
  may bypass multiple filters
  starting to integrate in lots of scanners
  0xS0bky/HackVault
    unleashing an ultimate xss polyglot

Jackmasa's XSS Mindmap
  breaks down attacks based on context
  PoC's
  ideas for all sorts of things
  used to just be in Japanese
  ported recently to english
  huge image file (svg)
    https://github.com/jackmasa
      seems to have a bunch of projects worth looking at
    https://github.com/jackmasa/XSS.png/tree/master

Server Side Template Injection (SSTI)

  engine identification
    wappalyzer, builtwith, vulners scanner
    test fuzzing
    tooling
    tplmap + burp extension
    backslash powered scanner?

  tl;dr: send some template payload and check for result
    {{2*3}}

  epinna/tplmap
    code/server side template injection detection/exploitation

  other SSTI resources
    lots of links

Server Side Request Forgery (SSRF)
  look for any paths/urls referenced
  wilded/psychoPATH
  will release a tool with his Def Con talk in a week
  can bypass filtering blacklists using alternate IP encoding
  SSRF bible: https://www.reddit.com/r/netsec/comments/2tpfz7/ssrf_bible_cheatsheet_by_onsec/
    protocol/schema mappings
    exploit examples
    update coming soon, BlackHat US-17?
  SSRF resources
    many links
    including BishopFox link: burp, collaborate and listen

Code Inject, Command Injection, Future of Fuzzing
  SQLi
    polyglot, seclists, swlmap, params, tooling, resources

  https://github.com/commixproject/commix
    CMDi
      supports PHP code injection
      custo modules
      powershell and python shells

Burp backslash powered scanner
  generic payloads
  multi-tiered
  checks responses
  basically gives you an idea of where it might be useful to look
    supports testers rather than replacing them!
  watch the video THEN read the paper
    see link

Infrastructure and coding
  subdomain takeover
    register, control traffic that goes there
    lists a bunch of services most often vuln
    github
      autoSubTakeover
      HostileSubBruteforcer
      tko-subs

  Article: Deep dive into AWS S3..
  yasinS/sandcastle
  michernriksen
  gitrob
  dxa4481/truffleHog
  
Domain Discovery at Def Con
DefCon hunt tool

jhaddix/tbhm
  The Bug Hunters Methodology

jhaddix@bugcrowd.com
</pre>
{% endraw %}

### How to Fail at Bug Bounty (Caleb Kinney)

{% raw %}
<pre>
Twitter: @aphire
Blog: http://bountyhuntersguild.com
GitHub: calebkinney OrOneEqualsOne

Lessons learned during bug bounties

Conferences: rushing to see talks, not networking

Failed to read the bug bounty program brief
  rules of engagement
  scope
  focus areas
  out of scope
  excluded vuln types
  rewards/incentives
  disclosure rules

Failed to show impact
  used to submit every bug, priority often wasn't in thought process
  understand vulnerability prioritisation and explain it to program owners
    P1 - Critical
    P2 - Severe
    P3 - Moderate
    P4 - Low
    P5 - Informational / Won't Fix
  can you combine a self-XSS with CSRF to up the priority?

Failed to understant criticality
  submitting a won't fix will hurt your average vuln score
  utilize the Bugcrowd Vulnerability Rating Taxonomy

Failed to understand the application
  eg. 'vuln' that is a feature of the application
  research the application and ask questions
  cross-reference functions between different platforms (eg mobile/web)

Failed to plan for private programs
  Don't ignore the start time, may make you hit many duplicates
  Schedule time to work on the program as soon as it's published

Failed to plan for blacklisting
  have a way to get a new IP address
  or use a VPN/proxy

Bug Bounty != Penetration Test

Part time hunt tips
  wide scopes
    acquisitions/mergers
  assume automated scanning
  recon, recon, recon
    subdomain bruteforcing, port-scanning, google dorking
    censys.io
    shodan.io
  burp extensions
    reflected parameters
    https://github.com/allfro/BurpKit
      used Webkit to better render responses in burp
      JS
    Co2
  payload lists
    polyglots!
  community
    read, give back, collaborate

Hunting makes me a better tester
  understand whats important
  attuned to emergent security trends
  challenge for more technical exploits
  etc..

Personal mobile recon setup
  iPhone with Blink Shell
    doesn't require jailbreak
  DietPi with MOSH (jump mox)
  Port Fowarding
  personal recon script
    Sublist3r, domain, knock, eyewitness
    wraps a bunch of things and combines
    https://github.com/OrOneEqualsOne/Recon
    next gen will be a webapp to help 

Bug Bounty Resources
  https://twitter.com/_devalias/status/886295129807396865
</pre>
{% endraw %}

### Giving Back to the Community (ZSeano)

{% raw %}
<pre>
https://twitter.com/zseano
http://zseano.com
  tutorials, blog posts, etc
full time bug bounty, ranked #2 on bugcrowd
25 years old

Overview
  Finding first bug, chaining to higher priority
  Recon: what are you missing
  Big bounties for a living, and staying sane

Open URL Redirects
  easy to find
  aboutads.info, run burp whilst opting out
  google dorking
    inurl:refirect inurl:&
  bypasses
    will release a lit of bypasses later
  making them more useful
    chain to account takeover via misconfigured oauth
      check their facebook app
        mobile app logs in via FB with app_token
    make sure to url encode the redirect_url
  Stored XSS + Oauth
    redirect user to stored XSS page, JS executes, grab oauth token and login to users account
  key things people miss
    bypassing filters
      generally use some form of regex
      fuzz as much as possible
      plan to update zseano.com with section on bypasses
    not checking for oauth systems in place
    try vulnerable parameter on as many endpoints as possible
      eg. one param on one program used througout the web application
      burp intruder against all endpoints, etc
    check their mobile app
      sometimes use oauth, FB login
      google logins tend to be more secure
    redirect oauth to stored XSS

In future, want to do more talks on more topics

Recon: go back in time
  waybackmachine
    search for old files like robots.txt
    https://gist.github.com/mhmdiaa
      waybackurls
      waybackrobots
    tool idea
      scraping website from years back for URLs/links/etc
      eg. burp-wayback-spider
  .js files are your friends
    way things work, paths
    discovery of new endpoints
    hardcoded app secrets
    sometimes user information
  built a couple of tool
    Burp
      copy selected URLs
      copy links in selected items
    zScanner
      burp spider to discover endpoints
      copy ites found, import to inputscanner
      visits each url, extracts all input names + ids and links to js files
      outputs to burp intruder format
        mass test XSS/sql/etc
      outputs 3 files, ready for burp intruder
        getoutput.txt
        postoutput.txt
        posthostoutput.txt
    use output from zScanner with JS-Scan
      visit each .js file, extract URLs using regex
      displays results on page
      easier to see whats in files without manually reading
    didn't plan on releasing these until recently

Finding bugs full time
  remain calm, take a step back
  see if someone has found something similar
  don't be afraid to ask people  
  be professional, waiting to be paid can be annoying
  be smart, learn where to spend your time
  test programs before diving in
  look at disclosed reports
  bugcrowd are managed programs
  managed programs on hackerone/synack can be good too
  you don't need an update every week, unless its a P1
  chain bugs to achieve the highest possible impact
    usually leads to bigger payout
  collaborate
  You WILL have bad days. Take time to relax, collect your thoughts, then keep going.
  re-test endpoints, re-visit certain areas of a site
    can either report on the old bug, or open a new report
    depends how much time you put in
  Find a program you love that treats you fair and give it your all
  Sharing is caring! If the program allows for it, share your bugs!  

People need to fuzz more

Store all vulnerable paramets found in a text file

Include your bug bounty name/how to contact/etc in your user agent

Have a few blog posts in the works
</pre>
{% endraw %}

### Doing Recon Like a Boss (Ben Sadeghipour)

{% raw %}
<pre>
https://twitter.com/Nahamsec

Agenda
  Overview
  Traditional way (brute forcing)
  AWS
  Abusing Github
  Asset identification

Why
  bigger attack surface
  more bugs
  more bounties
  more problems

Bruteforcing
  tools
    sublist3r, enumall, massdns, altdns, brutesubs, dns-parallel-prober, dnscan, knockpy, tko-subs, HostileSubBruteforce
  find a patterns
    .dev, .corp, .stage
  brute force again
    different permutations/environment

Amazon Web Services
  look for S3 buckets
    site:s3.amazonaws.com + ...
  use google for patterns
  GitHub
  automate your work

Automation
  create a list of subdomains
  create a list of environments
  automate
  catch them all
  new tool: Amazon S3 Bucket finder
    other tools: sandcastle, bucket_finder
    hopefully will release on github sometime next week

AWS Recon, what could go wrong
  S3 bucket not owned by company
  may be out of scope
  S3 bucket without sensitive info
  3rd party apps

Github Recon
  environments (dev, stage, prod)
  secret keys (API_key, AWS_Secret, etc)
  internal credentials
  API endpoints
  Domain patterns
  example
    "foo.com" "dev"
    "dev.foo.com"
    "bar.com" API_key
    "bar.com" password
    "api.bar.com"
    google dork
      site:"github.com" "org"
  tools
    gitrob
    git-all-secrets
    truffleHog
    git-secrets
    repo-supervisor
    do it manually..

Asset identifcation
  censys.io
    look for SSL certificates
    "company" + internal

  shodan.io
    search by hostname
    filter for
      ports 8443, 8080, 8180, etc
      title: "dashboard [jenkins]"
      product:Tomcat
      hostname:corp.levelup.com
      etc
    buy book by shodan creator for $5

  archive.org
    review source
    find old endpoints/functionality
    look for JS files
    exploit them!

  .js files
    endpoints
    credentials/tokens
    subdomains (inc internal)
    new tool being released next week

All tools included in this talk will be on the bugbountyforum website
Personal tools will be released next week

Burp 'should' be able to do JS parsing stuff
  in reality, seems to not work as well as it should
  can be easier to make external tools, do them your own way, etc
  hope someone takes this tool (when released) and create a burp plugin for it
  another tool (might get released)
    crawl website, download all JS files locally
</pre>
{% endraw %}

### Hidden in Plain Site: Disclosing Information via Your APIs (Peter Yaworski)

{% raw %}
<pre>
https://twitter.com/yaworsk

Application Security Engineer at Shopify
Wrote Web Hacking 101
  Hopefully Real World Web Hacking via No starch press

Overview
  What we're talking about
  Why we care
  Why it happens
  How you find it
  Examples

What we're talking about
  API's that reveal personal info or app sensitive info
  Focus on API's that render info to page source, parsed by react/angular/etc

Why we care
  Easy
  Impacts range from benign to critical
  Sometimes they can be chained together

Why it happens
  automation of repetitive tasks
  code abstraction
  easy to make mistakes, incur technical debt

Automation
  eg. rails is great at automating repetitive tasks, generate scaffold
  Will generate HTML view, but also .json endpoint for API
  You could remove those from the HTML view, won't see the information
  But can still get the full data from the API endpoint
  May not realise you need to edit the json file as well

Code abstraction
  eg. merging all json fields
  add new secret field
  manually, haven't updated json file, so fine
  but using json merge, the new param will be exposed

How do you find it
  initial recon
    identify software on site
      wappalyzer
        look for rails, angular, react
      eg rails sites follow certain patterns
  watch your proxy history
    look for gian json blobs in page sources
    watch for API calls
  mobile apps

http://www.leanpub.com/web-hacking-101
http://www.shopify.com/careers
</pre>
{% endraw %}

### Targeting for Bug Bounty Research (Matthew Conway)

{% raw %}
<pre>
Lead product security engineer: Heroku, Salesforce

https://twitter.com/mattreduce

Focuses
  Efficient, repeatable discovery
  Judge targets on measurable criteria
  Keep flexible/portable records
  Put it into use

Reconnaissance Stage

When to enumerate
    start first, return to

Why spend time on info gathering?
  don't miss a target/vuln
  better coverage for program owner
  deep understanding yields great findings

Enumeration methods
  Before you find problems, you need to find all the places they live 
  need to cast the net wide

Enumerating hosts
  information sources
    dns
      for info, but also vulns
      eg. subdomain takeovers, exfil data, command&control
    github
      may identify api's/etc
    rapid7 project sonar
      scans the whole public internet, seeing what's vulnerable
    google search
      hosts
      software running
      secret pages
    google certificate transparency report
      can find hosts through subdomains company registered certs for
    beta access
      if a company with bug bounty program has beta program, try it
      test new features
      follow them on twitter, other social media, be aware of what they put out there
    other open sites
      dnsdumpster
      threatcrowd
      thratminer
      https everywhere atlas
      look for opportunities to repurpose tools online

  techniques
    google queries
      site:foo.com
      find results from subdomains not on list yet
    brute forcing
      try common subdomains
      bonus points for expanding with own wordlist from crawling own targets
    own scripts
      automate this + anything else you can
    dns tools
      dig, host
      dnsrecon
      dnsenum
      dnsmap
    recon-ng
      more framework than a script, like metasploit for recon
    altdns (shubs)
      read shubs blog: high frequency bug hunting
    https://github.com/jhaddix/domain
      Setup script for Regon-ng/altdns

Recording results
  CSV file, SQL database
  get creative
  choose what to catalog
    domain
    type
    think about what you'd like to know when choosing the next target you want to work on
  Find, Fix, Finish, Exploit, Analyze (F3EA) cycle
  https://github.com/infosec-au/assetnote-poc
    push notifications for passive DNS data
  cleaning up data
    write some scripts to run against hosts
    screenshots
   validating possible targets
    SSL certificates used by that host
    common cookie names across hosts
    distinctive HTTP headers, fragments, etc
    logo images
    copyright lines
    privacy policy links
    contact information
    google analytics tracking codes

Using target data
  understanding ownership
    some sites give subdomains out to customers
    just because it's on a subdomain of that company, may not be an app they control
      eg company.github.io
    subdomains that point to external services
      eg. blog.company.com
    find out who owns the host before you hack it
  consider scope
    may be explicitly in/out of scope
    sometimes may be implicitly in scope based on rules of engagement
  what now
    enumerate services
    look for vulnerabilities

Summary
  find out everything you can, keep good notes
  Respect program scope, remember pitfalls
  Automate as much as you can
</pre>
{% endraw %}

### How does unicode affect our Security? (Christopher Bleckmann-Dreher, @schniggie)

{% raw %}
<pre>
https://twitter.com/schniggie?lang=en
Pentester, german car manufacturer
Retired bughunter

ASCII
  7-bit, 128 characters

ISO-8859-?
  ASCII compatible
  8-bit, 256 characters
  Multiple standards

Unicode
  multibyte character set
  fully ASCII/ISO-8859 compatible
  Different encodings (UTF-8, UTF-16, UTF-32, UTF-EBCDIC, ..)
  more like a database, links between copoint to character + some attributes
  Basic Multilingual Plan 65k chars
  Astral plans 1mil+ characters

Unicode Encodings
  different encodings use different bytes to store characters

Security implications - Length
  Length of UTF-8 string vs size of the string
  When allocating memory, etc

Security implications - JavaScript compare
  comparing 2 strings that look the same to the eye
  'ma\xF1ana' == 'man\u0303ana' -> false
  length of strings differ

Security implications - JavaScript regex
  /foo.bar/.test('fooPOOEMOJIbar')
  regex . should match 1 character
  \s\S matches whitespace, not whole of astral symbols
  multi-byte emoji
  current JS in most browsers is ECMScript5
    had trouble with chars in astral planes
    not completely supported by default
    some workarounds for it
  http://scriptular.com
    regex javascript application
    can test it

Security implications - MySQL vs UTF-8
  create table, charset set to utf8
  update table fooPOObar
    shows a warning, incorrect string value
  selecting back the entry, column name is only the prefix before poo emoji
  solution: set database to utf8mb4

Security implications - Internationalised Domain Names
  Stored as ascii strings using punycode
  eg. email spoofing using special characters
  UTF8 symbols that look identical
  Use punycode converter
  Register the converted domain
  real world attack scenarios
    an attack released earlier this year to spoof apple.com/etc
    not meant to be able to mix character sets in domain registrations
      google registrar seemed to allow it
    browsers realised that displaying UTF8 in the domain is bad
      now show the punycode instead

Unicode character - Right to left overide
  can rename the file using ruby File.rename \xe2\x80
  able to rename exe file to a file that looks like it has the extension .ppt
  old attack, known since Windows 98 or so, still works today..

Crashing every iOS and OSX device
  2013, vulnerable to an arabic string
  https://arstechnica.com/apple/2013/08/rendering-bug-crashes-os-x-and-ios-apps-with-string-of-arabic-characters/

Backend != Backend
  Frontend may allow UTF8
  Backend may not be expecting it
  exception from backend

Spotify account hijacking
  Allowed unicode usernames
  Register an account with a superscript word of an existing account user
  Trigger forget password function
  Password reset canonical'ises the username
  Sent him the password reset link
  Using that, used the canonicalised name again
  Was the victim user
  Reset password on that user

Phabricator bypass
  Facebook, like github
  Error, email at that domain not allowed
  MySQL
  add foo@attacker.comPOO@fb.com
  POO is the new %00  

Summary
  for developer
    verify methods, functions, frameworks handle unicode
    input validation should handle unicode
    verify all system and interconnection can handle unicode

POO is the new %00
</pre>
{% endraw %}

### Hacking Internet of Things for Bug Bounties (Aditya Gupta)

{% raw %}
<pre>
https://twitter.com/adi1391

https://twitter.com/_devalias/status/886339682958680064
  Run attify, pentesting IoT devices
  Author: "Learning Pentesting for Andorid Devices"
  Book: IoT hackers handbook, this month
  IoT pentesting guide to be released after this talk

Why
  if not, missing great stuff
  best to do in 2017
  easy targets
  higher barrier of entry
  enormous growth soon
  be prepared
  Examples
    IoT fridge that sends spam email
    Smart home compromised
    Hardcoded password in a medical device
    Shodan for scada things
    Controlling mining trucks

What
  what to look for during IoT big bounties

  When you look at a device
    figure out possible attack vectors
    look closely
    pentesting mindset
      components
      entrypoints
      communication
      protocols
      exposed ports

  Once you have a target
    compromise the whole target
    don't just look at one small part, whole thing
      micro and macro
    where would be most vulnerable?
      start there

How
  how to find vulns that companies will pay for
  "Hacking IoT is not a 'black magic' It can be learnt. Too less resources."

  How to start IoT bug bounty hunting
    attack surface mapping
    hacking the embedded device
    hacking firmware
      may not be available, but can dump from device
    hacking mobile/web/cloud components
    hacking radio communications

  Attack Surface Mapping - Step 1
    https://twitter.com/_devalias/status/886341534450307072
    Recon
      understanding device
      visible ports
      components
      communication mediums
    Available info
      google
      datasheets
      support groups
      community center
      social engineering
      FCC ID

    Attack Surface Mapping - Step 2
      https://twitter.com/_devalias/status/886341954404929536
      map attack surface (architecture diagram)
      entrypoints
      commuications
      additional web endpoints
      protocol/standard
      specifications

      Creating an architecture diagram

      Looking at a device
        FCC ID mentioned on the back of the device
          required for any radio communication device sold in US
        https://fccid.io/
          eg. EW780-8913-00
            https://fccid.io/EW780-8913-00
          gives you frequencies, internal/external pictures, etc
          can look for JTAG/etc ports

    What next?
      perform exploits
      be systematic
      often one component leads to another
      device -> dump firmware

    How to approach
      embedded -> firmware/web/mobile -> communication

    Hack the embedded device
      open device
      physical tamper protections, special screws, etc
        get a good screwdriver kit
      look at chipsets
        USB microscope
        phone flashlight
      identify things, label them
      dig deep
        look for exposed ports

    UART are easy to find/export
        multimeter to test Tx, Rx, GND
        connect to attify badg or USB-TTL
        identify baudrate
        run minicom for shell access
      screen can be used to connect to a TTY
        sudo screen /dev/ttyUSB0 ..

    JTAG
      can be harder than UART
      can be scattered across board
      JTAGulator or arduino nano flashed with JTAGEnum
      easily identify pinouts for JTAG
      https://twitter.com/_devalias/status/886344370944786432
        Hacking Embedded Devices - Debug JTAG

    Dump Flash
      look for flash chips
      read compoent sheet/datasheet
      may need to solder to adapter, pins are tiny
      then can dump flash

    NAND glitching
      generate fault scenario, have it behave in unexpected way
      drops to bootloader shell
      can set bootloader flags, eg single user mode

    Other attacks too

Firmware Hacking
  Easy to find basic vulns
  Good at RE -> lots of stuff to find
  Learn ARM and MIPS RE
  Sensitive hardcoded values, API keys, encryption mechanisms, etc

Firmware methodology
  binwalk
    extracts filesystem
  firmwalker
    identifies interesting things to look at
  Firmware-Mod-Kit
    allows filesystem modifications, then flash back to device
  Detect if device allows firmware modifications, security checks, etc

Encryption?
  XOR with empty space will give you the key itself

Hardcoded sensitive values
  eg. creds to ftp update server, etc
  Can find all sorts of things
    api keys, backdoors, SSL certs, staging URLs, etc
  Quick binary analysis in IDA
    can see harcoded creds
    command injection vulns
    ROP
    etc

Analysing mobile apps
  native libraries can store secrets
    file, readelf
    IDA demo version can dissass ARM binaries
    look at functions, eg. encryption
  understand the app code

Hacking communication
  look at mobile app -> device communication
  MQTT? CoAP?
  view resources unauthed?
  publish messages/subscribe topics?

  MQTT
    works on pub/sub topic
    might be able to subscribe to *

Hacking radio
  radio analysis/exploitation needs special hardware
  depends on protocol
  BLE/ZigBee most common

  Hacking Zigbee
    attify killerbee
      zbstumbler
      zbdump
      zbreplay
      etc

  Hacking BLE
    ubertooth, BLE sniffer
    sniff traggic
    see what handles being written
    rewrite handles using gatttool

Pentest methodology
  focus on 'attacker simulated exploitation' rather than pentest
  look at macro and micro
  95% success rate, critical vulns, devices compromised
  follow the guide

https://www.iotpentestingguide.com/
  https://twitter.com/_devalias/status/886350210724646912

https://twitter.com/_devalias/status/886350674266537984

https://twitter.com/_devalias/status/886350817741094912
</pre>
{% endraw %}

### Intro to Car Hacking (Alan Mond)

{% raw %}
<pre>
https://twitter.com/mondalan?lang=en
https://twitter.com/carloopio?lang=en
  Car hacking tool

Car Hacking 101
  How to get started
  vehicle networking basics
  demo
  build your own testing buck

What are the different attack surfaces?
  Tire pressure monitoring sensor
    sensor in each tire, connects to car, measures pressure
    communicates via low frequency radio signal
    can intercept that signal
  Bluetooth/wifi
    hotspot may be open
  ODBII port
    underneath steering wheel
    main entry point for access, but already inside car
  Infotainment system
    USB, root access possible, etc

How to get started
  Book: The Car Hacker's Handbook, Craig Smith
  Free download http://ebook-dl.com/book/5277
  Tools, protocols, references

What you'll need
  access to the OBD-II port
    mandated to be on 'CAN' since 2008
  CAN hardware tool
    USB2CAN
    microcontroller with CAN controller on it
  OBD-II to serial (RS-232) cable
  linux machine
    rasberry pi, virtual machine on osx
  OR
    Carloop basic ($55)
    open source
    wireless
  why not cheap ODB2 dongles from amazon?
    could.. just a lot of work to use them
    integrated circuit, converts raw CAN messages to values
    not getting raw messages

Most comprehensive list
  github.com/jaredthecoder/awesome-vehicle-security
  https://twitter.com/_devalias/status/886354216968609792

Vehicle networking basics
  CAN bus
    connects all modules through 2 wires
    dashboard, engine, control modules, infotainment system
    Controller Area Network (CAN)
    2 wires, high and low
    more than 1 CAN bus on vehicle

  Why focus on CAN?
    mandated since 2008
    well supported in linux
    more than just diagnostics..
    currently not encrypted at all..
    signals go from high to low

  Anatomy of a CAN message
    arbitration ID
    IDE: 0 (always for CAN)
    Data length: 1 byte
    Data: payload
    ID and data most important

Demo
  intall can-utils
  provision CarLoop with can-utils, flash over the air
    https://www.carloop.io/apps/app-scoketcan
  cansniffer
  identify by ID, see what changes in the data
    see what changes when you do something on the car
    no documentation out there
    manufacturers don't want you seeing it
    straightforward when you start to see it happen though

Build your own testing buck
  can build a test bench for less than $100
  Power supply
  engine control module
  CAN device
  adding more modules, can get more interesting data
  car-part.com

tools and resources on
  http://illmatics.com/carhacking.html
  https://community.rapid7.com/community/transpo-security/blog/2017/07/11/building-a-car-hacking-development-workbench-part-1

How to access proprietary parameter ID's?
  harder to decode
  query/response structure
  specific to ODB-II
  need to send specific PID to get it back
  most people use a scan tool for that brand, use a y-splitter
  then can capture the request/response

Replay of keyfobs from HackRF/similar devices?
  don't know much about it

Difference between tools mentioned and those dropped with jeep hacking research?
  that paper is a really good read
  goes through process of decoding each CAN message
  has some PID's you can look at (for same brand of car)
  each manufacturer has different 'data dictionaries' for these PIDS
  all tools very similar, can bus/receiver
  simple toolchain

bugcrowd running car hacking CTF, prize is a truck
  https://www.carhackingvillage.com/

https://store.carloop.io/
</pre>
{% endraw %}

## <a name="thanks"></a>Thanks!

Thanks for reading! Hope you found something useful.

Do you have any awesome resources, comments, or things to add? I'd love for you to share in the comments below! <3