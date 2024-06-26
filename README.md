# Adding-robots.txt-to-Your-Website
Learn how to add a robots.txt file to your website with this easy-to-follow guide. Control search engine bots' access and enhance your site's SEO performance effortlessly.

* Access your website's server using an FTP client or through your hosting provider's file manager.
* Navigate to the root folder of your website (often named www or public_html).
* Create a new file named robots.txt if it doesn't already exist.
* Open the robots.txt file for editing.
* Copy the content provided below for the robots.txt file.
* Paste the copied content into the robots.txt file.
* Save the changes to the robots.txt file.
* Ensure that the permissions of the file allow public access.
* Test the robots.txt file using Google's robots.txt Tester tool or a similar tool to ensure it's properly formatted and functioning as intended.

Remember to replace any existing **robots.txt** 

**Content:**

```sh

User-agent: *
Disallow: /wp-admin/
Disallow: /wp-content/
Disallow: /wp-includes

Allow: /wp-admin/admin-ajax.php
Allow: /wp-content/plugins/.js
Allow: /wp-content/themes/.js
Allow: /wp-content/themes/.css
Allow: /wp-content/cache/.js
Allow: /wp-content/cache/.css
Allow: /wp-includes/.js
Allow: /wp-includes/*.png

# Slow down bots
User-agent: *
Crawl-delay: 10

User-agent: Mediapartners-Google
Allow: /

User-agent: Adsbot-Google
Allow: /

User-agent: Googlebot-Image
Allow: /

User-agent: Googlebot-Mobile
Allow: /

User-agent: Google
Allow: /

User-agent: Googlebot
Allow: /

User-agent: Googlebot-news
Allow: /



# Disallow: Sistrix
User-agent: sistrix
Disallow: /

# Disallow: Sistrix
User-agent: SISTRIX Crawler
Disallow: /

# Disallow: Sistrix
User-agent: SISTRIX
Disallow: /

# Disallow: SEOkicks-Robot
User-agent: SEOkicks-Robot
Disallow: /

# Disallow: jobs.de-Robot
User-agent: jobs.de-Robot
Disallow: /

# Backlink Analysis
user-agent: AhrefsBot
disallow: /

# Bot der Leipziger Unister Holding GmbH
user-agent: UnisterBot
disallow: /

# http://www.opensiteexplorer.org/dotbot
User-agent: DotBot
Disallow: /
User-agent: dotbot
Disallow: /

# http://www.searchmetrics.com
User-agent: SearchmetricsBot
Disallow: /

# http://www.majestic12.co.uk/projects/dsearch/mj12bot.php
User-agent: MJ12bot
Disallow: /

# http://www.domaintools.com/webmasters/surveybot.php
User-agent: SurveyBot
Disallow: /

# http://www.seodiver.com/bot
user-agent: SEOdiver
disallow: /

# http://openlinkprofiler.org/bot
User-agent: spbot
Disallow: /

# http://www.wotbox.com/bot/
User-agent: wotbox
Disallow: /

# http://www.meanpath.com/meanpathbot.html
User-agent: meanpathbot
Disallow: /

# http://www.backlinktest.com/crawler.html
User-agent: BacklinkCrawler 
Disallow: /

# http://www.brandwatch.com/magpie-crawler/
User-agent: magpie-crawler
Disallow: /

# http://filterdb.iss.net/crawler/
User-agent: oBot
Disallow: /

User-agent: fr-crawler
Disallow: /

# http://webmeup-crawler.com
User-agent: BLEXBot
Disallow: /

# https://megaindex.com/crawler
User-agent: MegaIndex.ru
Disallow: /

User-agent: megaindex.com
Disallow: /

# http://www.cloudservermarket.com
User-Agent: CloudServerMarketSpider
Disallow: /

# http://www.trendiction.de/de/publisher/bot
User-Agent: trendictionbot 
Disallow: /

# http://www.exalead.com
User-agent: Exabot
Disallow: /

# http://www.career-x.de/bot.html
User-agent: careerbot
Disallow: /

# https://www.lipperhey.com/en/about/
User-agent: Lipperhey-Kaus-Australis
Disallow: /

User-agent: seoscanners.net
Disallow: /

User-agent: MetaJobBot
Disallow: /



User-agent: LinkStats
Disallow: /

User-agent: JobboerseBot
Disallow: /

User-agent: ICCrawler
Disallow: /

User-agent: Plista
Disallow: /

User-agent: Domain Re-Animator Bot
Disallow: /

# https://www.lipperhey.com/en/about/
User-agent: Lipperhey-Kaus-Australis
Disallow: /

# https://turnitin.com/robot/crawlerinfo.html
User-agent: turnitinbot
Disallow: /

# http://help.coccoc.com/
User-agent: coccoc
Disallow: /

# ubermetrics-technologies.com
User-agent: um-IC
Disallow: /

# datenbutler.de
User-agent: mindUpBot
Disallow: /

# http://searchgears.de/uber-uns/crawling-faq.html
User-agent: sg-Orbiter
Disallow: /

# http://commoncrawl.org/faq/
User-agent: CCBot
Disallow: /

# https://www.qwant.com/
User-agent: Qwantify
Disallow: /

# http://linkfluence.net/
User-agent: Kraken
Disallow: /

# http://www.botje.com/plukkie.htm
User-agent: plukkie 
Disallow: /

# https://www.safedns.com/searchbot
User-agent: SafeDNSBot
Disallow: /

# http://www.haosou.com/help/help_3_2.html
User-agent: 360Spider
Disallow: /

# http://www.haosou.com/help/help_3_2.html
User-agent: HaosouSpider
Disallow: /

# http://www.moz.com/dp/rogerbot
User-agent: rogerbot
Disallow: /

# http://www.openhose.org/bot.html
User-agent: OpenHoseBot
Disallow: /


# http://thumbsniper.com
User-agent: ThumbSniper
Disallow: /

# http://www.radian6.com/crawler
User-agent: R6_CommentReader
Disallow: /

User-agent: ImplisenseBot
Disallow: /

# http://cliqz.com/company/cliqzbot
User-agent: Cliqzbot
Disallow: /

# https://www.aihitdata.com/about
User-agent: aiHitBot
Disallow: /

# http://www.trendiction.com/en/publisher/bot
User-Agent: trendictionbot
Disallow: /

# http://seocompany.store
User-Agent: adscanner
Disallow: /

# https://github.com/yasserg/crawler4j/
User-Agent: crawler4j
Disallow: /

# http://warebay.com/bot.html
User-agent: WBSearchBot
Disallow: /

User-agent: Python/3.5 aiohttp
Disallow: /

User-agent: Toweya.com
Disallow: /

# http://www.website-datenbank.de/
User-agent: netEstate
Disallow: /

# http://law.di.unimi.it/BUbiNG.html
User-agent: BUbiNG
Disallow: /

# http://www.linguee.com/bot; bot@linguee.com
User-agent: Linguee
Disallow: /

# https://www.semrush.com/bot/
User-agent: SemrushBot
Disallow: /

User-agent: SemrushBot-SA
Disallow: /

# www.sentibot.eu
User-agent: sentibot
Disallow: /
User-agent: SentiBot
Disallow: /

# http://velen.io
User-agent: VelenPublicWebCrawler
Disallow: /

User-agent: DomainCrawler
Disallow: /

# https://moz.com/help/guides/moz-procedures/what-is-rogerbot
User-agent: rogerbot
Disallow: /

User-agent: IndeedBot
Disallow: /

# http://www.garlik.com
User-agent: GarlikCrawler
Disallow: /

# https://www.gosign.de/typo3-extension/typo3-sicherheitsmonitor/
User-agent: Gosign-Security-Crawler
Disallow: /

# http://www.siteliner.com/bot
User-agent: Siteliner
Disallow: /

# https://sabsim.com
User-agent: SabsimBot
Disallow: /

# http://ltx71.com/
User-agent: ltx71
Disallow: /


Sitemap: https://example.com/sitemap.xml
Sitemap: https://example.com/images_sitemap.xml

```
