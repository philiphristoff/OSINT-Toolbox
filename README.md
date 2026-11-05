# OSINT-Toolbox
Personal collection of OSINT tools used in my day-to-day life

##1. Open-source browser tools, directories, and research workflow

CyberChef: https://gchq.github.io/CyberChef/: FOSS browser toolkit for decoding, transforming, parsing, hashing, and inspecting data such as URLs, timestamps, certificates, and logs. Source under Apache 2.0. Most processing runs locally in-browser; some operations contact external services. Source and license: https://github.com/gchq/CyberChef

Overpass Turbo: https://overpass-turbo.eu/: FOSS browser GUI for querying OpenStreetMap features by area and tag, then viewing or exporting results. Respect shared API capacity. Source: https://github.com/tyrasd/overpass-turbo

DNSViz: https://dnsviz.net/: FOSS browser-based DNS/DNSSEC visualization and diagnostic tool; configuration warnings are not proof of malicious activity. Source: https://github.com/dnsviz/dnsviz

OpenStreetMap: https://www.openstreetmap.org/: open map data and open-source project; browsing does not require an account. Map completeness and accuracy vary. Website source: https://github.com/openstreetmap/openstreetmap-website

Mermaid Live Editor: https://mermaid.live/: open-source browser editor for drafting timelines, process diagrams, and entity/organization relationship maps. Avoid placing sensitive data in shareable URLs. Source: https://github.com/mermaid-js/mermaid-live-editor

RAWGraphs: https://app.rawgraphs.io/: open-source browser data-visualization tool for exploring tables. Check current data-handling behavior before uploading anything sensitive. Source: https://github.com/rawgraphs/rawgraphs-app

OSINT Framework: https://osintframework.com/: broad tool/source directory. Many entries are commercial, installable, or account-gated, so check each one.

Awesome OSINT: https://github.com/jivoi/awesome-osint: community-maintained directory of tools and sources; not every entry is browser-based or suitable for sensitive investigations.

Tranco List: https://tranco-list.eu/: public research ranking of popular domains; a reference dataset, not a trust or safety verdict.

##2. Web archives, source discovery, and fact-checking

Internet Archive Wayback Machine: https://web.archive.org/: free public archive for historical page snapshots and preservation. A missing capture does not prove a page never existed.

Common Crawl URL Index: https://index.commoncrawl.org/: free, open web-crawl index accessed through a browser/API rather than a polished search UI. Coverage is incomplete and captures may not preserve every page element. Project overview: https://commoncrawl.org/

ArchiveWeb.page: https://archiveweb.page/: browser-based web-preservation tool from the open-source Webrecorder project; useful for capturing public pages locally. Source: https://github.com/webrecorder/archiveweb.page

Bellingcat Online Investigation Toolkit: https://bellingcat.gitbook.io/toolkit: free task-based directory with descriptions and limitations; individual entries have their own licenses, costs, and account requirements. About: https://www.bellingcat.com/resources/2024/09/24/bellingcat-online-investigations-toolkit/

Google Fact Check Explorer: https://toolbox.google.com/factcheck/explorer: search published fact-checks from participating publishers; not every topic or publisher is covered.

DuckDuckGo: https://duckduckgo.com/, Google: https://www.google.com/, Bing: https://www.bing.com/: free public search engines, generally not FOSS. Search results differ and indexing is incomplete; corroborate important claims.

##3. Public accounts and identity context, authorized and public-interest use only

This category is for accounts belonging to organizations, public officials acting in their role, public campaigns, or a person’s own/consented digital-footprint review. It is not for connecting a private person’s pseudonyms to their offline identity or finding their whereabouts.

Username-enumeration tools, including WhatsMyName: not included in the recommended list because the stated objective is tracking people/accounts from minimal identifiers. For a self-audit, use the platforms’ own account/privacy tools or obtain explicit consent.

Meta Ad Library: https://www.facebook.com/ads/library/: search public ads and advertisers on Meta services; useful for public campaign research, not private-account discovery.

Google Ads Transparency Center: https://adstransparency.google.com/: browse public advertisers and ads appearing across Google surfaces; platform coverage and search options vary.

TikTok Commercial Content Library: https://library.tiktok.com/: public search for eligible ads and other commercial content; use for campaign research, not private-user tracking.

FaceCheck ID and PimEyes: retained only as excluded items from the original list; facial-search services are not FOSS and are not recommended here for identifying or tracking private people. Face matches can be wrong and biometric search creates serious privacy and legal risks.

Probe Spider and Osintgram: the original list’s installable social-account enumeration projects are not included in the recommended workflow for tracking private people or bypassing platform access controls.

##4. Threat intelligence, vulnerability, and malware research

VirusTotal: https://www.virustotal.com/: multi-engine file/URL reputation checks; proprietary, with free-feature and account limits. Public submissions may be retained or shared; never upload confidential material without approval.

URLhaus: https://urlhaus.abuse.ch/: free community database of URLs reported distributing malware. Do not open listed URLs in an ordinary browser.

ThreatFox: https://threatfox.abuse.ch/: free community IOC search for malware-related indicators; check timestamps and corroborate.

Feodo Tracker: https://feodotracker.abuse.ch/ and SSLBL: https://sslbl.abuse.ch/: free abuse.ch feeds for botnet infrastructure and malicious certificates; indicators age out.

OpenPhish: https://openphish.com/: phishing-intelligence feed and public sample data; access options and coverage vary.

MalwareBazaar: https://bazaar.abuse.ch/: search malware samples by hash or metadata first; use isolated, authorized analysis environments for samples.

MalShare: https://malshare.com/ and VXVault: http://vxvault.net/: malware repositories from the original list; treat downloads as dangerous and verify current access and terms before use.

ANY.RUN: https://any.run/, Hybrid Analysis: https://www.hybrid-analysis.com/, Triage: https://tria.ge/, Joe Sandbox: https://www.joesandbox.com/#windows: hosted sandboxes from the original list. Proprietary; free/community features, accounts, and submission visibility vary. Never submit confidential samples unless approved.

GreyNoise: https://www.greynoise.io/: threat-intelligence service with limited community access; account/API availability may vary. Provides Internet-noise context, not individual attribution.

CISA Known Exploited Vulnerabilities Catalog: https://www.cisa.gov/known-exploited-vulnerabilities-catalog: official public catalog of vulnerabilities known to be exploited; not a complete vulnerability inventory.

NIST National Vulnerability Database: https://nvd.nist.gov/vuln/search: public CVE and vulnerability records; confirm technical details with vendor advisories.

FIRST EPSS: https://www.first.org/epss/: public exploit-likelihood data to help prioritize vulnerabilities; a score is not a prediction of a specific attack.

Dynamite Labs: https://lab.dynamite.ai/: commercial threat-intelligence/automation platform from the original list; not a strict FOSS/no-account match.

Malware-handling rule: search hashes and metadata first. Never download or execute samples on a normal workstation; use only an isolated environment and follow organizational policy.

##5. Geolocation, maps, and satellite context

Use these to verify locations and public events, not to infer or monitor a private person’s whereabouts.

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

##6. Companies, filings, sanctions, and public records

Use official registers first and note jurisdiction, filing date, and any data limitations. Do not use people-named records to expose a private individual’s home or contact details.

SEC EDGAR Search: https://www.sec.gov/edgar/search/: official US public-company filings and full-text search; not a universal registry.

UK Companies House: https://find-and-update.company-information.service.gov.uk/: official UK company search and filed documents; verify claims against original filings.

GLEIF LEI Search: https://search.gleif.org/: public Legal Entity Identifier and entity reference data; not a complete ownership graph.

EU Sanctions Map: https://www.sanctionsmap.eu/: public EU sanctions reference; confirm decisions against current official legal instruments and lists.

OpenSanctions: https://www.opensanctions.org/search/: searchable open-data project covering sanctions, watchlists, and public-office records. Treat results as candidates and verify against the issuing authority’s current source.

OpenCorporates: https://opencorporates.com/: broad company-record search; free access may be limited, and the primary registry remains the source of record.

##7. Domains, DNS, certificates, IPs, and routing

For authorized organization/domain research and defensive triage. Infrastructure records provide technical context; they do not identify a person or establish attribution.

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

##8. Image, video, and media verification

Use these to assess public media and verify context. Visual-analysis outputs are leads, not proof of manipulation or identity. Avoid using reverse-image services to identify private people by face.

FotoForensics: https://fotoforensics.com/: free web-based image analysis utility from the original list, but not FOSS. Compression artifacts are not proof of editing; review upload/privacy terms before submitting sensitive images.

Forensically: https://29a.ch/photo-forensics/: free browser suite for metadata, clone patterns, noise, and C2PA-related information. The site says images stay on the user’s device; its documentation cautions that outputs are only clues. Source-code licensing is not asserted here.

InVID-WeVerify Verification Plugin: https://weverify.eu/verification-plugin/: browser extension for checking public images/videos, extracting keyframes, and launching verification checks. Requires installation; obtain it from an official extension store and review permissions. Source/release repository: https://github.com/AFP-Medialab/verification-plugin

ExifTool: https://exiftool.org/: open-source local metadata tool for images, video, and other files. It requires installation, not a browser; metadata can be edited or forged, so corroborate it.

FFmpeg: https://ffmpeg.org/: open-source local media toolkit that can extract video frames for analysis. It requires installation; use it on public-interest or consent-based material.

Content Credentials Verify: https://contentcredentials.org/verify: free public verifier for C2PA credentials when present. A signed provenance record does not guarantee that a depicted scene is true; missing credentials do not prove fakery.

Google Lens: https://lens.google/, Bing Visual Search: https://www.bing.com/visualsearch, TinEye: https://tineye.com/: free or limited reverse-image services, not FOSS. Useful for finding earlier appearances or alternate contexts of an image; avoid face-based identification of private people.

WITNESS Media Lab Verification Resources: https://lab.witness.org/portfolio_page/verification/: training materials on verifying citizen media for journalism and human-rights documentation. Use the guidance as a process reference and verify each claim independently.

Bellingcat Advanced Guide on Verifying Video Content: https://www.bellingcat.com/resources/how-tos/2017/06/30/advanced-guide-verifying-video-content/: a guide to checking earlier appearances and context using video frames and reverse-image search. It is older, so individual tool details may have changed.

Reddit r/OSINT: https://www.reddit.com/r/OSINT/: community discussion, not a vetted reference. I attempted to review threads, but search returned no usable results and Reddit blocked direct access during this check. Treat posts as leads and verify recommendations against specialist guidance and primary sources.

##9. Public datasets, news, and structured research

Wikidata Query Service: https://query.wikidata.org/: browser-based queries over public structured data, including downloadable results. No account is required for ordinary queries; verify community-maintained statements against primary sources. Documentation: https://www.wikidata.org/wiki/Wikidata:SPARQL_query_service

GDELT Project: https://www.gdeltproject.org/: public global news/event data and research tools; coverage and language quality vary, and news mentions are not independently verified facts.

OpenAlex: https://openalex.org/: free open scholarly works, authors, institutions, and citation data; author-name matches can be ambiguous.

Crossref Search: https://search.crossref.org/: public scholarly publication metadata search; records can be incomplete or contain errors.

Common Crawl: https://commoncrawl.org/: see Section 2 for its public web-crawl index and historical URL records.

##10. Email headers and message authentication

These utilities inspect message metadata, not a person’s location or private account access. Do not paste confidential mail into third-party tools without organizational approval.

MXToolbox Email Header Analyzer: https://mxtoolbox.com/EmailHeaders.aspx: parse Received lines and authentication headers; proprietary service, and header paths can be forged or incomplete.

Google Admin Toolbox Messageheader: https://toolbox.googleapps.com/apps/messageheader/: another free header-analysis view; results are not proof of sender identity.

MXToolbox: https://mxtoolbox.com/: DNS, MX, SPF, DMARC, and blacklist lookups; free features are limited and the service is not FOSS.

##11. Digital footprint, privacy, and web-tracking audit

These are for auditing your own browser, a website, or an authorized organization, not for covertly tracking another person.

EFF Cover Your Tracks: https://coveryourtracks.eff.org/: free browser test for selected tracker-blocking and fingerprinting characteristics; not a security certification or proof of anonymity. Project source: https://github.com/EFForg/cover-your-tracks

BrowserLeaks: https://browserleaks.com/: free browser-based tests showing technical data a site may receive, such as WebRTC and fingerprinting signals; not FOSS and not an identity lookup.

Blacklight: https://themarkup.org/blacklight: website tracker-audit tool from The Markup; use to inspect a site’s tracking behavior, not infer who visited it.

Trackography: https://trackography.org/: original-list resource for visualizing third-party tracking on news sites; check that the site and dataset are still maintained before relying on it.

PrivacyTests.org: https://privacytests.org/: open test results comparing browser privacy behavior; informative, but not a guarantee that a browser is secure or anonymous.

##12. Browser testing utility

Browserling: https://www.browserling.com/: cross-browser testing service from the original list; not an OSINT source and not FOSS. Free use may be limited.

Browser.lol: https://browser.lol/en: disposable cloud-browser sessions for visiting unfamiliar sites away from your device, with no local browser installation. The service offers an ad-supported free tier and paid options.
