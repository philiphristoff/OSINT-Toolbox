# OSINT-Toolbox
Personal collection of OSINT tools used in my day-to-day life

## 1. Open-source browser tools, directories, and research workflow

CyberChef: https://gchq.github.io/CyberChef/: FOSS browser toolkit for decoding, transforming, parsing, hashing, and inspecting data such as URLs, timestamps, certificates, and logs. Source under Apache 2.0. Most processing runs locally in-browser; some operations contact external services. Source and license: https://github.com/gchq/CyberChef

Overpass Turbo: https://overpass-turbo.eu/: FOSS browser GUI for querying OpenStreetMap features by area and tag, then viewing or exporting results. Respect shared API capacity. Source: https://github.com/tyrasd/overpass-turbo

DNSViz: https://dnsviz.net/: FOSS browser-based DNS/DNSSEC visualization and diagnostic tool; configuration warnings are not proof of malicious activity. Source: https://github.com/dnsviz/dnsviz

OpenStreetMap: https://www.openstreetmap.org/: open map data and open-source project; browsing does not require an account. Map completeness and accuracy vary. Website source: https://github.com/openstreetmap/openstreetmap-website

Mermaid Live Editor: https://mermaid.live/: open-source browser editor for drafting timelines, process diagrams, and entity/organization relationship maps. Avoid placing sensitive data in shareable URLs. Source: https://github.com/mermaid-js/mermaid-live-editor

RAWGraphs: https://app.rawgraphs.io/: open-source browser data-visualization tool for exploring tables. Check current data-handling behavior before uploading anything sensitive. Source: https://github.com/rawgraphs/rawgraphs-app

OSINT Framework: https://osintframework.com/: broad tool/source directory. Many entries are commercial, installable, or account-gated, so check each one.

Awesome OSINT: https://github.com/jivoi/awesome-osint: community-maintained directory of tools and sources.

Tranco List: https://tranco-list.eu/: public research ranking of popular domains; a reference dataset, not a trust or safety verdict.

## 2. Web archives, source discovery, and fact-checking

Internet Archive Wayback Machine: https://web.archive.org/: free public archive for historical page snapshots and preservation. A missing capture does not prove a page never existed.

Common Crawl URL Index: https://index.commoncrawl.org/: free, open web-crawl index accessed through a browser/API rather than a polished search UI. Coverage is incomplete and captures may not preserve every page element. Project overview: https://commoncrawl.org/

ArchiveWeb.page: https://archiveweb.page/: browser-based web-preservation tool from the open-source Webrecorder project; useful for capturing public pages locally. Source: https://github.com/webrecorder/archiveweb.page

Bellingcat Online Investigation Toolkit: https://bellingcat.gitbook.io/toolkit: free task-based directory with descriptions and limitations; individual entries have their own licenses, costs, and account requirements. About: https://www.bellingcat.com/resources/2024/09/24/bellingcat-online-investigations-toolkit/

## 3. Public accounts, identity context, social media

Social Catfish: https://socialcatfish.com/: Social Catfish is an online investigation and people search platform built to verify identities, spot romance scams, and uncover fake profiles.

WhatsMyName: https://whatsmyname.io/: Search a username, nickname, or email across hundreds of public sites to find linked profiles. WhatsMyName.io returns public leads for manual review, not identity proof.

Blackbird: https://github.com/p1ngul1n0/blackbird: Search a username across over 600+ websites.

Cupidcr4wl: https://github.com/OSINTI4L/cupidcr4wl: Username and phone number search tool that crawls adult content platforms to see if a targeted account or person is present.

Digital Footprint Check: https://www.digitalfootprintcheck.com/free-checker.html: Check for registered username on 100s of sites for free.

Helix: https://github.com/thalha-a9/helix: Check a username on 8,000+ sites, re-verify every hit live against impossible usernames, and graph how the accounts connect.

IDCrawl: https://www.idcrawl.com/username: Search for a username in popular social networks.

Maigret: https://github.com/soxoj/maigret: Collect a dossier on a person by username.

Name Chk: https://www.namechk.com/: Check over 30 domains and more than 90 social media account platforms.

Name Checkup: https://namecheckup.com/: is a search tool that allows you to check the avilability of a givrn username from all over the social media. Inaddition it also sllows you to check the avilability of a given domain name.

NexFil: https://github.com/thewhiteh4t/nexfil: checks username from almost all social network sites.

Seekr: https://github.com/seekr-osint/seekr: A multi-purpose all in one toolkit for gathering and managing OSINT-Data with a neat web-interface. Can be used for note taking and username checking.

Sherlock: https://github.com/sherlock-project/sherlock: Search for a username in multiple platforms/websites.

SherlockEye: https://sherlockeye.io/: Search for publicly available information connected to a username, uncovering associated profiles and activities across the web.

Trace: https://trace.manus.space/: Real-time OSINT platform to search usernames, emails, phone numbers, and full names across 600+ platforms with breach detection and AI risk scoring.

TraceFind: https://tracefind.info/: Uncover the Truth Behind Any Username — Instantly. Scans thousands of sites for username presence.

Snoop: https://github.com/snooppr/snoop/blob/master/README.en.md: Search for a nickname on the web (OSINT world)

Social Analyzer: https://github.com/qeeqbox/social-analyzer: API, CLI, and Web App for analyzing and finding a person's profile in 1000 social media \ websites

Threat Actor Username Search: https://threatactorusernames.com/: Search through 3M+ threat actor usernames to find where criminals and baddies post online and operate.

user-scanner: https://github.com/kaifcodec/user-scanner.git: Check a username's presence across dev/social/gaming/creator site

User Search: https://www.usersearch.org/: Find someone by username, email, phone number or picture across Social Networks, Dating Sites, Forums, Crypto Forums, Chat Sites and Blogs, 3000+ sites Supported!

User Searcher: https://www.user-searcher.com/: User-Searcher is a powerful and free tool to help you search username in 2000+ websites.

FaceCheck ID: https://facecheck.id/: Upload a face of a person of interest and discover their social media profiles, appearances in blogs, video, and news websites.

PimEyes: https://pimeyes.com/en: PimEyes is an online face search engine available for everyone. Start by uploading a clear photo to perform a reverse image search and find pictures containing given faces across the Internet.

Osintgram: https://osintgram.com/: Osintgram is a specialized open-source intelligence tool designed to collect and analyze publicly available data from Instagram profiles in a structured and efficient way. Built for digital investigators, researchers, and analysts, it transforms scattered social media information into meaningful insights that support smarter decision-making.

InstagramPrivSniffer: https://github.com/obitouka/InstagramPrivSniffer: Views Instagram private accounts media without login.

Insto: https://github.com/subzeroid/insto: Interactive OSINT CLI / REPL with 35+ slash-commands: profile + media + followers + dossier + geo-fingerprint (/where), shared-followers intersection (/intersect), superfan ranking (/fans), location search (/place), URL→metadata resolution (/postinfo), posting-cadence histogram (/timeline), Maltego CSV export. Token-based (HikerAPI, no IG account needed → no ban risk) with optional logged-in aiograpi backend.

Osintgraph: https://github.com/XD-MHLOO/Osintgraph: Tool that maps your target’s Instagram data and relationships in Neo4j for social network analysis.

Toutatis: https://github.com/megadose/toutatis: a tool that allows you to extract information from instagrams accounts such as s, phone numbers and more

IG Detective: https://www.igdetective.com/: Public Instagram investigation with no login: anonymous story viewer, a follower tracker showing an account's recent follows/unfollows, and a profile viewer, plus optional continuous tracking with a permanent Story Archive (account required for tracking only).

Facebook Friend List Scraper: https://github.com/n0kovo/fb_friend_list_scraper: Tool for scraping large Facebook friend lists without being rate-limited.

Facebook Sleep Stats: https://github.com/sorenlouv/fb-sleep-stats: A small tool to show the potential privacy implications modern social media have. By tracking online/offline status of people on Facebook, it is possible to get an accurate image of their sleep pattern.

Have I been Zuckered: https://haveibeenzuckered.com/: A large dataset containing 533 million Facebook accounts was made available for download. The data was obtained by exploiting a vulnerability that was, according to Facebook, corrected in August 2019. Check if a telephone number is present within the Facebook data breach.

EinzzTools TiktTok Info Loader: https://einzzcookie.org/: Find out hidden info about TikTok users and more

The Endorser: https://github.com/eth0izzle/the-endorser: Tool that allows you to draw out relationships between people on LinkedIn via endorsements/skills.

## 4. Threat intelligence, vulnerability, and malware research

VirusTotal: https://www.virustotal.com/: multi-engine file/URL reputation checks; proprietary, with free-feature and account limits. Public submissions may be retained or shared; never upload confidential material without approval.

URLhaus: https://urlhaus.abuse.ch/: free community database of URLs reported distributing malware. Do not open listed URLs in an ordinary browser.

ThreatFox: https://threatfox.abuse.ch/: free community IOC search for malware-related indicators; check timestamps and corroborate.

Feodo Tracker: https://feodotracker.abuse.ch/ and SSLBL: https://sslbl.abuse.ch/: free abuse.ch feeds for botnet infrastructure and malicious certificates; indicators age out.

OpenPhish: https://openphish.com/: phishing-intelligence feed and public sample data; access options and coverage vary.

MalwareBazaar: https://bazaar.abuse.ch/: search malware samples by hash or metadata first; use isolated, authorized analysis environments for samples.

MalShare: https://malshare.com/ and VXVault: http://vxvault.net/: malware sample repositories. Treat downloads as dangerous and verify current access and terms.

ANY.RUN: https://any.run/, Hybrid Analysis: https://www.hybrid-analysis.com/, Triage: https://tria.ge/, Joe Sandbox: https://www.joesandbox.com/#windows: hosted malware-analysis sandboxes. Account requirements, free features, and submission visibility vary.

GreyNoise: https://www.greynoise.io/: threat-intelligence service with limited community access; account/API availability may vary. Provides Internet-noise context, not individual attribution.

CISA Known Exploited Vulnerabilities Catalog: https://www.cisa.gov/known-exploited-vulnerabilities-catalog: official public catalog of vulnerabilities known to be exploited; not a complete vulnerability inventory.

NIST National Vulnerability Database: https://nvd.nist.gov/vuln/search: public CVE and vulnerability records; confirm technical details with vendor advisories.

FIRST EPSS: https://www.first.org/epss/: public exploit-likelihood data to help prioritize vulnerabilities; a score is not a prediction of a specific attack.

SpiderFoot: https://spiderfoot.xyz/: SpiderFoot is an open source intelligence (OSINT) automation tool. It integrates with just about every data source available and utilises a range of methods for data analysis, making that data easy to navigate.

Dynamite Labs: https://lab.dynamite.ai/: commercial threat-intelligence and automation platform.

## 5. Geolocation, maps, and satellite context

NASA Worldview: https://worldview.earthdata.nasa.gov/: free viewer for Earth-observation imagery and layers over time; data access/download requirements may vary by layer.

NASA FIRMS Fire Map: https://firms.modaps.eosdis.nasa.gov/map/: public satellite fire-detection map for situational context; detections may be delayed or misclassified.

Zoom Earth: https://zoom.earth/: browser viewer for satellite and weather imagery, storms, and wildfires. Timestamps, resolution, and sources differ by layer; it is not continuous real-time coverage.

SunCalc: https://www.suncalc.org/: visualize daylight and sun direction for a place/date; only one clue in imagery verification.

Mapillary: https://www.mapillary.com/app/: public street-level imagery viewer for checking visible infrastructure and scene context; coverage varies and some features may require an account.

Wikimedia Commons: https://commons.wikimedia.org/: search public media, captions, and geotagged material; verify metadata and descriptions independently.

GeoHack: https://geohack.toolforge.org/: convert coordinates into map links and geographic context; it is not an authoritative gazetteer.

GeoNames: https://www.geonames.org/: search place names, alternate spellings, and coordinates in a community-maintained gazetteer. Verify results against official or independent mapping sources.

GeoHints: https://geohints.com/: visual reference for region-specific clues such as road signs, traffic lights, utility poles, bollards, and street furniture. Treat clues as hypotheses and verify against independent map imagery.

OpenAerialMap: https://openaerialmap.org/: browse openly licensed aerial imagery and map layers; coverage, dates, and resolution are uneven.

KartaView: https://kartaview.org/map/: community-contributed street-level imagery; coverage and image dates vary. Use for public scene verification, not personal surveillance.

Bellingcat, A Beginner’s Guide to Geolocating Videos: https://www.bellingcat.com/resources/how-tos/2014/07/09/a-beginners-guide-to-geolocation/: training on verifying the location of public-interest footage from visible scene details. Do not use to infer a private person’s current whereabouts.

OpenStreetMap: https://www.openstreetmap.org/ and Overpass Turbo: https://overpass-turbo.eu/: see Section 1 for the open map and feature-query tools.

## 6. Companies, filings, sanctions, and public records

SEC EDGAR Search: https://www.sec.gov/edgar/search/: official US public-company filings and full-text search; not a universal registry.

UK Companies House: https://find-and-update.company-information.service.gov.uk/: official UK company search and filed documents; verify claims against original filings.

GLEIF LEI Search: https://search.gleif.org/: public Legal Entity Identifier and entity reference data; not a complete ownership graph.

EU Sanctions Map: https://www.sanctionsmap.eu/: public EU sanctions reference; confirm decisions against current official legal instruments and lists.

OpenSanctions: https://www.opensanctions.org/search/: searchable open-data project covering sanctions, watchlists, and public-office records. Treat results as candidates and verify against the issuing authority’s current source.

OpenCorporates: https://opencorporates.com/: broad company-record search; free access may be limited, and the primary registry remains the source of record.

## 7. Domains, DNS, certificates, IPs, and routing

crt.sh: https://crt.sh/: search Certificate Transparency logs for certificates mentioning a domain; discovered hosts may be historical, inactive, or unrelated.

ICANN Lookup: https://lookup.icann.org/en: public RDAP lookup for domain registration data; privacy redactions and registry policies limit the record.

DNSViz: https://dnsviz.net/: see Section 1 for the open-source DNS/DNSSEC visualization tool.

Google Admin Toolbox Dig: https://toolbox.googleapps.com/apps/dig/: free DNS record lookup utility; not FOSS.

DNSDumpster: https://dnsdumpster.com/: free, limited domain/DNS discovery service; quotas and access rules may apply.

RIPEstat: https://stat.ripe.net/: public IP/ASN/routing information and visualizations.

BGP.tools: https://bgp.tools/ and Hurricane Electric BGP Toolkit: https://bgp.he.net/: public ASN, prefix, and routing lookups; these are context, not proof of ownership.

Shodan InternetDB: https://internetdb.shodan.io/: free limited public IP lookup endpoint, not the full Shodan service; results may be stale or incomplete.

urlscan.io: https://urlscan.io/: web-page scan and public scan search; submissions can be visible to others. Do not submit internal or confidential URLs without authorization.

Palo Alto URL Filtering: https://urlfiltering.paloaltonetworks.com/: free URL-category lookup from a proprietary service; a vendor category is not a verdict.

DomainTools: https://www.domaintools.com/: commercial domain-intelligence service; free access is limited and some features require an account.

## 8. Image, video, and media verification

FotoForensics: https://fotoforensics.com/: web-based image-analysis utility; compression artifacts alone do not prove editing. Check upload terms before submitting sensitive images.

Forensically: https://29a.ch/photo-forensics/: free browser suite for metadata, clone patterns, noise, and C2PA-related information. The site says images stay on the user’s device; its documentation cautions that outputs are only clues. Source-code licensing is not asserted here.

InVID-WeVerify Verification Plugin: https://weverify.eu/verification-plugin/: browser extension for checking public images/videos, extracting keyframes, and launching verification checks. Requires installation; obtain it from an official extension store and review permissions. Source/release repository: https://github.com/AFP-Medialab/verification-plugin

ExifTool: https://exiftool.org/: open-source local metadata tool for images, video, and other files. It requires installation, not a browser; metadata can be edited or forged, so corroborate it.

FFmpeg: https://ffmpeg.org/: open-source local media toolkit that can extract video frames for analysis. It requires installation; use it on public-interest or consent-based material.

Content Credentials Verify: https://contentcredentials.org/verify: free public verifier for C2PA credentials when present. A signed provenance record does not guarantee that a depicted scene is true; missing credentials do not prove fakery.

Google Lens: https://lens.google/, Bing Visual Search: https://www.bing.com/visualsearch, TinEye: https://tineye.com/: free or limited reverse-image services, not FOSS. Useful for finding earlier appearances or alternate contexts of an image.

WITNESS Media Lab Verification Resources: https://lab.witness.org/portfolio_page/verification/: training materials on verifying citizen media for journalism and human-rights documentation. Use the guidance as a process reference and verify each claim independently.

Bellingcat Advanced Guide on Verifying Video Content: https://www.bellingcat.com/resources/how-tos/2017/06/30/advanced-guide-verifying-video-content/: a guide to checking earlier appearances and context using video frames and reverse-image search. It is older, so individual tool details may have changed.

## 9. Public datasets, news, and structured research

Wikidata Query Service: https://query.wikidata.org/: browser-based queries over public structured data, including downloadable results. No account is required for ordinary queries; verify community-maintained statements against primary sources. Documentation: https://www.wikidata.org/wiki/Wikidata:SPARQL_query_service

GDELT Project: https://www.gdeltproject.org/: public global news/event data and research tools; coverage and language quality vary, and news mentions are not independently verified facts.

OpenAlex: https://openalex.org/: free open scholarly works, authors, institutions, and citation data; author-name matches can be ambiguous.

Crossref Search: https://search.crossref.org/: public scholarly publication metadata search; records can be incomplete or contain errors.

Common Crawl: https://commoncrawl.org/: see Section 2 for its public web-crawl index and historical URL records.

## 10. Email headers and message authentication

MXToolbox Email Header Analyzer: https://mxtoolbox.com/EmailHeaders.aspx: parse Received lines and authentication headers; proprietary service, and header paths can be forged or incomplete.

Google Admin Toolbox Messageheader: https://toolbox.googleapps.com/apps/messageheader/: another free header-analysis view; results are not proof of sender identity.

MXToolbox: https://mxtoolbox.com/: DNS, MX, SPF, DMARC, and blacklist lookups; free features are limited and the service is not FOSS.

## 11. Digital footprint, privacy, and web-tracking audit

EFF Cover Your Tracks: https://coveryourtracks.eff.org/: free browser test for selected tracker-blocking and fingerprinting characteristics; not a security certification or proof of anonymity. Project source: https://github.com/EFForg/cover-your-tracks

BrowserLeaks: https://browserleaks.com/: free browser-based tests showing technical data a site may receive, such as WebRTC and fingerprinting signals; not FOSS and not an identity lookup.

Blacklight: https://themarkup.org/blacklight: website tracker-audit tool from The Markup; use to inspect a site’s tracking behavior, not infer who visited it.

Trackography: https://trackography.org/: visualizes third-party tracking on news websites.

PrivacyTests.org: https://privacytests.org/: open test results comparing browser privacy behavior; informative, but not a guarantee that a browser is secure or anonymous.

## 12. Remote browsers

Browserling URL Sandbox: https://www.browserling.com/browser-sandbox: interactive browser sessions run remotely.

Browser.lol: https://browser.lol/en: isolated cloud-browser sessions for visiting pages away from your device.

MyBrowser: https://www.mybrowser.lol/online-browser: remote Chrome, Firefox, and other browser sessions streamed through your browser.

Kasm Workspaces: https://kasm.com/browser-isolation: container-based browser isolation with an in-browser demo and deployable workspaces.
