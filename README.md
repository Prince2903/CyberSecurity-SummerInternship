# CyberSecurity(Web App Testing,DarkWeb,OSINT)

Hello Friends👋 

What is Web application penetration testing?

Web application penetration testing is the practice of simulating attacks on a system in an attempt to gain access to sensitive data, with the purpose of determining whether a system is secure. These attacks are performed either internally or externally on a system, and they help provide information about the target system, identify vulnerabilities within them, and uncover exploits that could actually compromise the system. It is an essential health check of a system that informs testers whether remediation and security measures are needed.

What are the benefits of web application penetration testing?

There are several key benefits to incorporating web application penetration testing into a security program.

- It helps you satisfy compliance requirements. Pen testing is explicitly required in some industries, and performing web application pen testing helps meet this requirement.
- It helps you assess your infrastructure. Infrastructure, like firewalls and DNS servers, is public-facing. Any changes made to the infrastructure can make a system vulnerable. Web application pen testing helps identify real-world attacks that could succeed at accessing these systems.
- It identifies vulnerabilities. Web application pen testing identifies loopholes in applications or vulnerable routes in infrastructure—before an attacker does.
- It helps confirm security policies. Web application pen testing assesses existing security policies for any weaknesses.

OWASP Top 10 Vulnerability:

- Cross Site Scripting(XSS)
- SQL Injection
- Insecure Direct Object Reference
- Command Injection
- XML External Entity Attack(XXE)
- File Inclusion
- Unrestricted File Upload
- Cross Site Request Forgery(CSRF)
- Insecure Deserialization
- Broken Authentication


**What Is The DarkWeb?**

The dark web refers to content on the internet that is intentionally hidden and requires special software, like Tor Browser, to access. The dark web is a subset of the deep web, which is all content on the internet that isn't indexed by search engines.

The dark web is part of the deep web but is built on darknets overlay networks that sit on the internet but which can’t be accessed without special tools or software like Tor. Tor is an anonymizing software tool that stands for The Onion Router — you can use the Tor network via Tor Browser.

**Dark Web Examples:**

- Sites requiring special tools to access
- Websites not found on search engines
- .onion domains
- Decentralized marketplaces

**How To Get On The Dark Web**

The quickest way to access the dark web is to download and install Tor Browser, which will route your traffic through the Tor network and let you access the dark web. On Tor, you can type in any URL you’d like to visit, including .onion domains on the dark web.

**How To Access The DarkWeb Securely And Safely?**

The best way to get on the dark web is encrypt your connection with a VPN like Avast SecureLine VPN and then connect through tor browser. This is called Tor-over-VPN.

- Connect to a reliable and safe VPN.
- Download and install Tor Browser.
- Browse the dark web with Tor Browser.
- Protect your identity.

**How To Visit Onion Websites?**

When you connect to Tor, your internet activity is sent through the Tor network, anonymizing your Internet activity so it can’t be snooped on, and so that you can access websites that may be blocked in your country.

So, when you access google.com through Tor, your request bounces from Tor relay to Tor relay before it reaches an exit node. That exit node then contacts Google.com for you, and it sends you back the data Google responded with. Google sees this as the exit node’s IP address contacting it instead of your IP address.

For example, Facebook maintains an official Tor hidden services address at “facebookwkhpilnemxj7asaniu7vnjjbiltxjqhye3mhbshg7kx5tfyd.onion”. This allows you to access Facebook through Tor, and your connection doesn’t ever leave Tor where it can be snooped on. This may be useful in countries that block Facebook.

You don’t necessarily want to use Tor all the time, as it’s slower than just browsing normally. But it’s a useful tool for anonymizing your Internet activity and bypassing censorship.


To access a .onion address, you’ll need to access it through the Tor Browser. It’s a modified version of Firefox that’s configured to connect to sites through the Tor network.

After launching the Tor browser, type the .onion address into its address bar. For example, to access Facebook’s hidden service, you’d enter the following address:

https://facebookwkhpilnemxj7asaniu7vnjjbiltxjqhye3mhbshg7kx5tfyd.onion

Or, to access the DuckDuckGo search engine’s hidden service, you’d enter:

https://duckduckgogg42xjoc72x3sjasowoarfbgcmvfimaftt6twagswzczad.onion/

You can also access .onion sites without running Tor through proxies that connect to Tor for you. The proxy connects to Tor for you and then forwards you the traffic over the regular Internet.

This, however, is a very bad idea! You’re losing the anonymity you normally have when you connect to a .onion site through the Tor browser. That’s the whole point of a .onion address, after all. The website you access maintains its anonymity, but someone monitoring your connection can see which website you’re connecting to. The service provider can also see what you’re connecting to and snoop on any passwords and other private information you provide over the connection.

Tor2web functions in this way, but you shouldn’t use it. For example, if you attempt to connect to Facebook’s hidden service using Tor2web, Facebook blocks the connection and tells you it’s a bad idea.


**Data Breaches That Are On Sell**

**HCA Healthcare patient data stolen and for sale by hackers:**

- HCA Healthcare patient data has been hacked and is now for sale, according to the company.
- The dataset has approximately 27 million rows and includes patients’ personal information and certain visit records.
- The hack affects patients in nearly two dozen states, including patients at dozens of facilities in Florida and Texas.

Personal information for potentially tens of millions of HCA Healthcare patients has been stolen and is now available for sale on a data breach forum as of earlier this week.

HCA, one of the largest companies in the U.S., first acknowledged the breach earlier today. In a release, it warned patients that critical personal information had been compromised, including their full name, city and when and where they last saw a provider.

The hack affects patients in nearly two dozen states, including patients at dozens of facilities in Florida and Texas. The data sale was flagged on Twitter by Brett Callow, an analyst at New Zealand-based Emsisoft.

This may be one of the biggest health care-related breaches of the year and one of the biggest of all time. That said, despite affecting millions of people, it may not be as harmful as other breaches as, based on HCA’s statement, it doesn’t seem to have impacted diagnoses or other medical information, Callow told CNBC.

**American Airlines Data Breach**: Hackers have reportedly stolen personal information relating to ‘thousands' of pilots that applied for roles at American Airlines and Southwest Airlines. Rather than being taken directly from either airline, the information was extracted from a database maintained by a recruiting company. Around 8,000 pilots are thought to have been affected, including 2,200 represented by the Allied Pilots Association.

**UPS Canada Data Breach**: United Parcel Service has strongly hinted to customers based in Canada via a letter that their personal data may have been exposed in a breach, after fraudulent messages demanding payment before delivery were spotted.

The strangely-worded letter sent out to customers suggested that “a person who searched for a particular package or misused a package lookup tool” could have uncovered personal information relating to customers, such as phone numbers.

**Bryan Cave/Mondelez Data Breach**: Snack and confectionary manufacturer Mondelez, the parent company that owns Oreo, Chips Ahoy!, Sour Patch Kids, Toblerone, Milka, Cadbury, and many other well-known brands, has notified employees that their personal information has been compromised in a breach at law firm Bryan Cave.

Bryan Cave provides Mondelez and a number of other large companies with legal services. According to the data breach notice filed to the Maine Attorney General's Office, 51110 employees are thought to have been affected. Although the data breach occurred in February of this year, it was only discovered three months later in May, the filing reveals.

**Reddit Data Breach**: Hackers purporting to be from the BlackCat ransomware gang have threatened Reddit with leaking 80GB of confidential data they stole from its servers in February. The gang is demanding a $4.5 million payout and also wants Reddit to renege on its new pricing policy that garnered widespread backlash.

**OSINT Tools**:

- Holehe - Email to Registered Accounts
- Octosuite - Advanced OSINT Framework
- Toutatis -  Extract Information From Instagrams Accounts
- OnionSearch - Search Engines
- Mr.Holmes - Gain Information About Domains, Username And Phone Numbers
- DaProfiler - tracing the digital identity of a target via social networks, emails, public information
- Seekr - OSINT-data with a sleek web interface
- Querytool - Based on Google Spreadsheets: Terms, people, email addresses, files and many more
- Yesitsme - Find Instagram profiles by name and e-mail/phone
- Hackerwasi - OSINT
- pywhat - The easiest way to identify anything
- theHarvester -  theHarvester is a very simple, yet effective tool designed to be used in the early stages of a penetration test. Use it for open source intelligence gathering and helping to determine a company's external threat landscape on the internet. The tool gathers emails, names, subdomains, IPs, and URLs using multiple public data sources
- Maltego
- Nmap
- Mitaka
- SpiderFoot
- Spyse
- BuiltWith
- Intelligence X
- DarkSearch.io
- Grep.app
- Recon-ng
- Shodan
- Metagoofil
- Searchcode
- SpiderFoot
- Babel X
- Email Hippo: MX Records Checks for Email Lookup
- PhoneInfoga: Python-Based Phone Lookup
- SpiderFoot: Cybersecurity Intelligence
- Spokeo: US Citizen Records Checks
- Have I Been Pwnd?: The Data Breach Go-To
- SEON: Best for Social and Digital Signals Checks
- Lampyre: Due Diligence and Cyberthreat Intelligence

**Snpachat OSINT:**

SnapScraper:

Snap Scraper is an open source intelligence tool which enables users to download media uploaded to Snapchat's Snap Map using a set of latitude and longitiude co-ordinates. This project is in no way affiliated with, authorized, maintained, sponsored or endorsed by Snap inc. or any of its affiliates or subsidiaries. This program is for education, forensic and bug reporting purposes only and is provided without warranty.

**Telegram Crawler Tool**:

This Tool is developed to automatically detect changes made to the official Telegram sites and beta clients. This is necessary for anticipating future updates and other things (new vacancies, API updates, etc).

**How it works**

1.Link crawling runs as often as possible. Starts crawling from the home page of the site. Detects relative and absolute sub links and recursively repeats the operation. Writes a list of unique links for future content comparison. Additionally, there is the ability to add links by hand to help the script find more hidden (links to which no one refers) links. To manage exceptions, there is a system of rules for the link crawler.
 
2.Content crawling is launched as often as possible and uses the existing list of links collected in step Going through the base it gets contains and builds a system of subfolders and files. Removes all dynamic content from files. It downloads beta version of Android Client, decompiles it and track resources also. Tracking of resources of Telegram for macOS presented too.
 
3.Using of GitHub Actions. Works without own servers. You can just fork this repository and own tracker system by yourself. Workflows launch scripts and commit changes. All file changes are tracked by GIT and beautifully displayed on GitHub. GitHub Actions should be built correctly only if there are changes on the Telegram website. Otherwise, the workflow should fail. If build was successful, we can send notifications to Telegram channel and so on.

**Example of link crawler rules configuration:**

CRAWL_RULES = {
   
    'translations.telegram.org': {
        'allow': {
            r'^[^/]*$',  # root
            r'org/[^/]*/$',  # 1 lvl sub
            r'/en/[a-z_]+/$'  # 1 lvl after /en/
        },
        'deny': {
            '',  # all
        }
    },
    'bugs.telegram.org': {
        'deny': {
            '',    # deny all sub domain
        },
    }, }

**Current hidden urls list:**

HIDDEN_URLS = {
    # 'corefork.telegram.org', # disabled

    'telegram.org/privacy/gmailbot',
    'telegram.org/tos',
    'telegram.org/tour',
    'telegram.org/evolution',

    'desktop.telegram.org/changelog',}

**Meta Data Search Tool:**

erwin:

erwin offers a unified software platform for combining data governance, enterprise architecture, business process, and data modeling. The product is delivered as a managed service that allows users to discover and harvest data, as well as structure and deploy data sources by connecting physical metadata to specific business terms and definitions. erwin imports metadata from data integration tools, as well as cloud-based platforms, and can evaluate complex lineages across systems and use cases.

IBM:

IBM’s InfoSphere Information Server features a metadata repository that stores metadata from suite tools and external tools and databases and enables sharing among them. Users can import metadata into the repository from multiple sources, export metadata by various methods, and transfer metadata between design, test, and production repositories. Changes that are made in the repository are automatically made throughout the suite, and uses standard relational database technology.

Infogix:

Infogix offers a suite of integrated data governance capabilities that include business glossaries, data cataloging, data lineage, and metadata management. The tool also provides customizable dashboards and zero-code workflows that adapt as each organizational data capability matures. Reference customers use Infogix for data governance and for risk, compliance and data value management. The product is also flexible and easy to use, and supports smaller data analysis jobs as well.

Informatica:

Informatica Metadata Management allows enterprises to tap into four major categories of data, including technical, database schemas, mappings and code, business (glossary terms, governance processes), operational and infrastructure (run-time stats and time stamps), and usage (user ratings and comments). Informatica creates a knowledge graph of an organization’s data assets and their relationships by applying AI and machine learning. Active metadata serves as the foundation for Informatica’s Intelligent Data Platform.

**Pastebin:**

Pastebin is a website where you can store any text online for easy sharing. The website is mainly used by programmers to store pieces of sources code or configuration information, but anyone is more than welcome to paste any type of text. The idea behind the site is to make it more convenient for people to share large amounts of text online. 

**What Is Pastebin?**

When you create an account you get your own Pastebin. This means you can now store pastes and have full control over them at any point in the future. Having your own Pastebin is also great for sharing your pastes with others. Your Pastebin is both public and private at the same time. Your public pastes are visible to everybody while the private ones are only visible to you. 

**Download Data From DarkWeb:**

Extracting data from the dark and deep web is different from collecting data from the open web.

While data on the open web is structured and searchable, data on the dark web is anonymous, unindexed, and unmonitored. As a place where cybercrime, white-collar cybercrime and violent crime are planned, it’s important to understand how to collect data from the darknets while protecting yourself from becoming a target of cybercrime.

Another main difference between open and dark web is that while data on the open web has a standard search engine and domains that remain fairly constant, content on the dark web is more dynamic and elusive. Criminals advertising plans of data leaks or cyber-attacks often transfer their advertisements between marketplaces and platforms to throw law enforcement off of their tracks. In addition, the darknets have their own terminology for communication, causing those who are unfamiliar with the correct search terms to have a harder time finding accurate data.

Webz.io’s dark web feeds data service delivers quality and accurate data that allows you to start mining and gathering relevant data immediately - with a simple RESTful API call. That means that instead of wasting precious time and resources on collecting and extracting data, you can focus your efforts on data analysis that catches criminals and fights crime.

**DarkWeb Engines:**

- Torch 
- Kilos
- AHMIA
- Tor66

**Torch:**

Torch prides itself on being the first-ever dark web search engine publicly available. The name is a play on the term TOR search.

**Pros:**

    - Response time of 3 seconds
    - 2 million indexed websites

**Cons:**

    - Popular forums and marketplaces don’t always appear in the first page of search results
    - Many of its indexed websites are no longer working

**Kilos:**

Kilos is one of the later dark web search engines to spring up. As its name suggests, the dark web search engine is focused mainly on the buying and selling of illegal drugs.

**Pros:**

    - Offers granular filtering which include searching for items according to price range, type of currency, shipping sources and destination and payment options
    - Returns searches from 10 marketplaces 
    - Includes content from sites blocked by login

**Cons:**

    - 30 second response time 
    - Only 16 indexed websites

**Ahmia:**

Ahmia is another open source clearnet search engine that was developed with support from the Tor Project. Ahmia’s advantage is that it delivers a deep and dark web search engine for those who don’t have access to Tor by integrating with Tor2Web and providing access to onion sites. Since it collects these public onion addresses and indexes them for easier navigation, onion site operators frequently register their site using Ahmia.

**Pros:**

    - Includes coverage of content from both marketplaces and forums
    - Response time of 3 seconds

**Cons:**

    - Only 3,000 indexed web pages

**Tor66:**

Tor66 is a dark web search engine with the goal of providing high-quality search results for onion websites. Submissions of onion websites are open to the public. The search engine makes money through different paid search ads and advertisements.

**Pros:**

    - Includes coverage of content from marketplaces

**Cons:**

    - Includes only 100,000 indexed webpages
    - Search response time of 4 seconds

**Email To Information:**

Have I Been Pwned:

With its secure method of searching and extensive database, Have I Been Pwned is a reliable and effective way for users to take control of their account security. The site collects information from public data breaches and stores the details in a searchable database.


New breach: Roblox hacking forum Vermillion was breached in Aug 2014 exposing 8k forum member records. Data included email and IP addresses, usernames, dates of birth and salted password hashes. 82% were already in 
 https://haveibeenpwned.com

**whoxy(Email To Website):**

https://www.whoxy.com/

**TheHarvester(Email finder):**

theHarvester is a simple to use, yet powerful tool designed to be used during the reconnaissance stage of a red team assessment or penetration test. It performs open source intelligence (OSINT) gathering to help determine a domain's external threat landscape. The tool gathers names, emails, IPs, subdomains, and URLs by using multiple public resources.

**X-osint:**

This is an osint tool which gathers useful and yet credible valid information about a phone number, user's email address and ip address and more to come in future updates

**Features:**

IP Address information gathering
Email Address information gathering
Phone number information gathering
Host finding
Ports finding
Subdomain Enumeration
CVE Exploits Finder
Email Finder
Exploit Open Source Vulnerability Database
DNS Lookup
DNS Reverse
Vin extractor
Protonmail OSINT 

**Email OSINT:**

How To Start And Download:

EMAIL OSINT is an OSINT Tool for emails. It helps you gather information about the target email.

- git clone https://github.com/KanekiX2/Email-Osint.git
- cd Email-Osint
- py EmailOsint.py -e <EMAIL>

**socialosint:**

A python osint tool for getting emails, from a target, published in social networks like Instagram, Linkedin and Twitter for finding the possible credential leaks in PwnDB.

**Over 100, 000 Snapchat Photos Have Leaked:**

New OCTOBER female celebrities on Fappening 4 /Snappening DOWNLOAD:http://www.mediafire.com/download/dmp12si3mw3wqv9/HOT_OCTOBER_Fappening_4_Pic_and_Video.rar
DOWNLOAD:http://www.mediafire.com/download/dmp12si3mw3wqv9/HOT_OCTOBER_Fappening_4_Pic_and_Video.rar
DOWNLOAD:http://www.mediafire.com/download/dmp12si3mw3wqv9/HOT_OCTOBER_Fappening_4_Pic_and_Video.rar
DOWNLOAD:http://www.mediafire.com/download/dmp12si3mw3wqv9/HOT_OCTOBER_Fappening_4_Pic_and_Video.rar
DOWNLOAD:http://www.mediafire.com/download/dmp12si3mw3wqv9/HOT_OCTOBER_Fappening_4_Pic_and_Video.rar
DOWNLOAD:http://www.mediafire.com/download/dmp12si3mw3wqv9/HOT_OCTOBER_Fappening_4_Pic_and_Video.rar

Hackers have warned that thousands of nude images sent via the mobile-messaging service Snapchat, many of which users believed self-destructed after being sent, are to be released online in a searchable database. Messaging boards on the notorious website 4chan have been filling up with news of the imminent leak, already being referred to as "The Snappening". Hackers have warned that thousands of nude images sent via the mobile-messaging service Snapchat, many of which users believed self-destructed after being sent, are to be released online in a searchable database. Messaging boards on the notorious website 4chan have been filling up with news of the imminent leak, already being referred to as "The Snappening". It comes just weeks after hundreds of celebrity nudes were leaked online through the same site, following a hack of Apple's iCloud that has come to be referred to as the Fappening. Earlier this week an anonymous 4chan user claimed to have hacked into Snapsave, an image-saving service that allows users of Snapchat to store pictures received before they self-destruct. By way of proof, the poster provided pictures allegedly from Snapsave. Given the nature of the Snapchat service, many of the images are expected to be of an explicit nature, while the young demographic of Snapchat's users could mean that some of the images released constitute child pornography. The 4chan thread, initially spotted by blogger and social media strategist Kenny Withers, warns that there are around 200,000 images set to be released.

**Snapchat - Geographic locations, Phone numbers, Usernames (Leaked Database):**

Link: https://mega.nz/file/CngyVJ7C#MQB5g0N2ufNhCVDKhB2_30u_5XWPmOHB1BZQlYh6Bm4

**Web-Check:**

All-in-one website OSINT Tool for analyzing any website. The Dashboard will show - IP info, SSL chain, DNS records, cookies, headers, domain info, page map, server location, open ports, traceroute.

Link: https://web-check.as93.net 


**Spiderfoot:**

SpiderFoot is an open source intelligence (OSINT) automation tool. It integrates with just about every data source available and utilises a range of methods for data analysis, making that data easy to navigate.

SpiderFoot has an embedded web-server for providing a clean and intuitive web-based interface but can also be used completely via the command-line. It's written in Python 3 and MIT-licensed.

You can target the following entities in a SpiderFoot scan:

- IP address
- Domain/sub-domain name
- Hostname
- Network subnet (CIDR)
- ASN
- E-mail address
- Phone number
- Username
- Person's name
- Bitcoin address


**Linkedln And Facebook Data Breach:**

Personal data for 700 million LinkedIn users—nearly 93% of the company’s members—has been put up for sale online.

-Hackers have already posted a sample of the data, which included information for 1 million users, according to a report on RestorePrivacy.

-The data appears to be recent, with samples from 2020 and 2021, according to the report. In a statement to Fortune, a LinkedIn spokesperson disputes this, saying, "We’ve investigated, and there is no evidence that this is new data or that the data is from 2020 and 2021."

-The price for that enormous collection of data? $5,000.

-🗣The data examined by the site did not include login credentials or financial information, but it did include a wealth of personal information that could be used to assume someone’s identity.

-Full names
-Phone numbers
-Physical addresses
-Email addresses
-Geolocation records
-LinkedIn usernames and profile URLs
-Personal and professional experiences and backgrounds
-Genders

**Links:**

http://scadonsak.com/48AT/LinkedIn_database_leaked_May_2016.rar
https://ddl.to/8xym9io07wad/LinkedIn_database_leaked_May_2016.rar
https://dropapk.to/7ft7n2hry3yy/LinkedIn_database_leaked_May_2016.rar
https://hugesharing.net/184vo3so2b0o/LinkedIn_database_leaked_May_2016.rar
https://uploadrar.com/gkcj5t41ffhy/LinkedIn_database_leaked_May_2016.rar

**Latest 2023 Linkedln:**

https://nitroflare.com/view/9A2680BB466B653/LinkedIn_Company_Pages_Data.zip
https://nitroflare.com/view/2EE8B62F23CE441/LinkedIn_Digital_Data.zip
https://nitroflare.com/view/4E96CBDFCB40492/LinkedIn_Influencer%27s_Data.zip
https://nitroflare.com/view/67B96C580EBD6C5/LinkedIn_Profile_Data.csv.zip
https://nitroflare.com/view/6B7690809ADAFC9/LinkedIn_Profiles_and_Jobs_Data.zip

**533 million Facebook users’ phone numbers leaked on hacker forum**

The mobile phone numbers and other personal information for approximately 533 million Facebook users worldwide has been leaked on a popular hacker forum for free.

The stolen data first surfaced on a hacking community in June 2020 when a member began selling the Facebook data to other members. What made this leak stand out was that it contained member information that can be scraped from public profiles and private mobile numbers associated with the accounts.

Included in the data leak are the phone numbers for three of Facebook's founders - Mark Zuckerberg, Chris Hughes, and Dustin Moskovitz, which are the 4th, 5th, and 6th members first registered on Facebook.

![image](uploads/854e4392021c854615f0931496d2a216/image.png)

**TheHarvester:**

TheHarvester is a simple to use, yet powerful tool designed to be used during the reconnaissance stage of a red team assessment or penetration test. It performs open source intelligence (OSINT) gathering to help determine a domain's external threat landscape. The tool gathers names, emails, IPs, subdomains, and URLs by using multiple public resources.

**Image Reverse Search Tools:**

**SmartImage:**

SmartImage is a powerful reverse image search tool for Windows. SmartImage will open the best match found returned from various image search engines (see the supported sites) right in your web browser. This behavior can be configured to the user's preferences.

**goris:**

This is a CLI tool to search for images with Google Reverse Image Search.

**TinEye:**

TinEye's computer vision, image recognition and reverse image search products power applications that make your images searchable.

**ambience:**

reverse image search and similarity search engine.

**iStonk:**

iStonk is tool that does a reverse image search on uploaded image/video files, and shows you results for a version without a watermark/other addon.

**How it works:**

If you are familiar with browsing images on the Internet, you are probably familiar with images that have watermarks (text/logos) covering the image (notably ShutterStock, iStock, and many others) some people still want to use the image, but don't want the watermark. Most of the time, there is a separate version of the exact same image without the watermark (most of the time, not even owned or created by those who add a watermark to it, and then sometimes charge money for the version without a watermark)

iStonk is simple. You simply upload/select an image or video file, and the program does a reverse image search, giving you a list of images that don't contain the watermark (when possible)

This is better than having to manually scrub the watermark out through editing, as that takes CPU, energy, skill, and time. If you still can't find a version without a watermark, you should try to scrub it out yourself and upload it, so that iStonk can be more powerful.

**Hash-hunt:**

Reverse image searching engine based on Perpetual image hashing technique.

**Searcher:**

A simple reverse image search engine, similar to Google Images or TinEye.

Can parse online HTML pages or local folders. Reverse image search is performed via CLI or a web-application.

Uses dhash as fingerprinting algorithm.

Probably won't scale well, but works fine for personal use.



  
