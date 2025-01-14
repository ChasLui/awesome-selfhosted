# Awesome-Selfhosted

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![](https://img.shields.io/travis/awesome-selfhosted/awesome-selfhosted/master?label=link%20checks)](https://github.com/awesome-selfhosted/awesome-selfhosted/issues/2266)

Self-hosting is the practice of locally hosting and managing applications instead of renting from [SaaSS](https://www.gnu.org/philosophy/who-does-that-server-really-serve.html) providers.

This is a list of [Free](https://en.wikipedia.org/wiki/Free_software) Software [network services](https://en.wikipedia.org/wiki/Network_service) and [web applications](https://en.wikipedia.org/wiki/Web_application) which can be hosted locally. Non-Free software is listed on the [Non-Free](non-free.md) page.

See [Contributing](.github/CONTRIBUTING.md).

--------------------


## 目录


- [Awesome-Selfhosted](#awesome-selfhosted)
  - [目录](#目录)
  - [Software](#software)
    - [Analytics](#analytics)
    - [Archiving and Digital Preservation (DP)](#archiving-and-digital-preservation-dp)
    - [Automation](#automation)
    - [Blogging Platforms](#blogging-platforms)
    - [Booking and Scheduling](#booking-and-scheduling)
    - [Bookmarks and Link Sharing](#bookmarks-and-link-sharing)
    - [Calendar & Contacts](#calendar--contacts)
    - [Calendar & Contacts - CalDAV or CardDAV Servers](#calendar--contacts---caldav-or-carddav-servers)
    - [Calendar & Contacts - CalDAV or CardDAV Web-based Clients](#calendar--contacts---caldav-or-carddav-web-based-clients)
    - [通信](#通信)
    - [通信 - 定制通信系统](#通信---定制通信系统)
    - [通信 - Email](#通信---email)
    - [通信 - 电子邮件 - 完整的解决方案](#通信---电子邮件---完整的解决方案)
    - [通讯 - Email - 邮件发送代理](#通讯---email---邮件发送代理)
    - [通讯 - Email - 邮件传输代理](#通讯---email---邮件传输代理)
    - [通讯 - Email - 邮件列表和新闻简报](#通讯---email---邮件列表和新闻简报)
    - [通讯 - Email - Web邮件客户端](#通讯---email---web邮件客户端)
    - [通讯 - IRC](#通讯---irc)
    - [通讯 - SIP](#通讯---sip)
    - [通讯 - 社交网络和论坛](#通讯---社交网络和论坛)
    - [Communication - XMPP](#communication---xmpp)
    - [Communication - XMPP - Servers](#communication---xmpp---servers)
    - [Communication - XMPP - Web Clients](#communication---xmpp---web-clients)
    - [Community-Supported Agriculture (CSA)](#community-supported-agriculture-csa)
    - [Conference Management](#conference-management)
    - [Content Management Systems (CMS)](#content-management-systems-cms)
    - [DNS](#dns)
    - [文档管理](#文档管理)
    - [文档管理 - E-books](#文档管理---e-books)
    - [文档管理 - Institutional Repository and Digital Library Software](#文档管理---institutional-repository-and-digital-library-software)
    - [Document Management - Integrated Library Systems (ILS)](#document-management---integrated-library-systems-ils)
    - [E-commerce](#e-commerce)
    - [Federated Identity & Authentication](#federated-identity--authentication)
    - [Feed Readers](#feed-readers)
    - [File Transfer & Synchronization](#file-transfer--synchronization)
    - [File Transfer - Distributed Filesystems](#file-transfer---distributed-filesystems)
    - [File Transfer - Object Storage & File Servers](#file-transfer---object-storage--file-servers)
    - [File Transfer - Peer-to-peer Filesharing](#file-transfer---peer-to-peer-filesharing)
    - [File Transfer - Single-click & Drag-n-drop Upload](#file-transfer---single-click--drag-n-drop-upload)
    - [File Transfer - Web-based File Managers](#file-transfer---web-based-file-managers)
    - [Games](#games)
    - [Gateways and Terminal Sharing](#gateways-and-terminal-sharing)
    - [Genealogy](#genealogy)
    - [Groupware](#groupware)
    - [Human Resources Management (HRM)](#human-resources-management-hrm)
    - [Internet of Things (IoT)](#internet-of-things-iot)
    - [Knowledge Management Tools](#knowledge-management-tools)
    - [Learning and Courses](#learning-and-courses)
    - [Maps and Global Positioning System (GPS)](#maps-and-global-positioning-system-gps)
    - [Media Streaming](#media-streaming)
    - [Media Streaming - Audio Streaming](#media-streaming---audio-streaming)
    - [Media Streaming - Multimedia Streaming](#media-streaming---multimedia-streaming)
    - [Media Streaming - Video Streaming](#media-streaming---video-streaming)
    - [Miscellaneous](#miscellaneous)
    - [Money, Budgeting & Management](#money-budgeting--management)
    - [Monitoring](#monitoring)
    - [Note-taking & Editors](#note-taking--editors)
    - [Office Suites](#office-suites)
    - [Password Managers](#password-managers)
    - [Pastebins](#pastebins)
    - [Personal Dashboards](#personal-dashboards)
    - [Photo and Video Galleries](#photo-and-video-galleries)
    - [Polls and Events](#polls-and-events)
    - [Proxy](#proxy)
    - [稍后读清单](#稍后读清单)
    - [食谱管理](#食谱管理)
    - [资源规划](#资源规划)
    - [资源规划 - 企业资源规划](#资源规划---企业资源规划)
    - [搜索引擎](#搜索引擎)
    - [自我托管解决方案](#自我托管解决方案)
    - [软件开发](#软件开发)
    - [软件开发 - API 管理](#软件开发---api-管理)
    - [软件开发 - Bug 追踪](#软件开发---bug-追踪)
    - [软件开发 - 持续集成和部署](#软件开发---持续集成和部署)
    - [软件开发 - 文档生成](#软件开发---文档生成)
    - [软件开发 - FaaS & Serverless](#软件开发---faas--serverless)
    - [软件开发 - IDE & Tools](#软件开发---ide--tools)
    - [软件开发 - 本地化](#软件开发---本地化)
    - [软件开发 - 项目管理](#软件开发---项目管理)
    - [软件开发 - UX 测试](#软件开发---ux-测试)
    - [静态站点生成](#静态站点生成)
    - [任务管理和待办清单](#任务管理和待办清单)
    - [追踪](#追踪)
    - [URL 短链](#url-短链)
    - [VPN](#vpn)
    - [Web Servers](#web-servers)
    - [Wikis](#wikis)
  - [List of Licenses](#list-of-licenses)
  - [External Links](#external-links)
  - [Contributing](#contributing)
  - [Authors](#authors)
  - [License](#license)

--------------------

## Software

<!-- BEGIN SOFTWARE LIST -->


### Analytics

**[`^        返回顶部        ^`](#)**

**请访问 [Awesome Analytics](https://github.com/0xnr/awesome-analytics)**

_关联: [Personal Dashboards](#personal-dashboards)_


### Archiving and Digital Preservation (DP)

**[`^        返回顶部        ^`](#)**

_关联: [Content Management Systems (CMS)](#content-management-systems-cms)_

- [Access to Memory (AtoM)](https://www.accesstomemory.org/) - Web-based, open source application for standards-based archival description and access in a multilingual, multi-repository environment. ([Demo](https://demo.accesstomemory.org/), [源码](https://github.com/artefactual/atom)) `AGPL-3.0-only` `PHP`
- [ArchiveBox](https://archivebox.io/) - Self-hosted _wayback machine_ that creates HTML & screenshot archives of sites from your bookmarks, browsing history, RSS feeds, or other sources. ([源码](https://github.com/ArchiveBox/ArchiveBox)) `MIT` `Python`
- [Archivematica](https://www.archivematica.org/) - Mature digital preservation system designed to maintain standards-based, long-term access to collections of digital objects. ([Demo](https://sandbox.archivematica.org/administration/accounts/login/), [源码](https://github.com/artefactual/archivematica)) `AGPL-3.0-only` `Python`
- [ArchivesSpace](https://archivesspace.org/) - Archives information management application for managing and providing Web access to archives, manuscripts and digital objects. ([Demo](https://archivesspace.org/application/demo/), [源码](https://github.com/archivesspace/archivesspace)) `ECL-2.0` `Ruby`
- [CKAN](https://ckan.org) - CKAN is a tool for making open data websites. ([源码](https://github.com/ckan/ckan)) `AGPL-3.0` `Python`
- [Collective Access - Providence](https://collectiveaccess.org/) - Highly configurable Web-based framework for management, description, and discovery of digital and physical collections supporting a variety of metadata standards, data types, and media formats. ([源码](https://github.com/collectiveaccess/providence)) `GPL-3.0-only` `PHP`
- [Horahora](https://github.com/horahoradev/horahora) - Video hosting website and video archival manager for Niconico, Bilibili, and Youtube. `MIT` `Go`


### Automation

**[`^        返回顶部        ^`](#)**

_关联: [Internet of Things (IoT)](#internet-of-things-iot)_

- [Accelerated Text](https://github.com/tokenmill/accelerated-text) - Automatically generate multiple natural language descriptions of your data varying in wording and structure. `Apache-2.0` `Java`
- [Actionsflow](https://github.com/actionsflow/actionsflow) `⚠` - The free Zapier/IFTTT alternative for developers to automate your workflows based on Github actions. `MIT` `Docker/Nodejs`
- [ActiveWorkflow](https://github.com/automaticmode/active_workflow) - An intelligent process and workflow automation platform based on software agents. `MIT` `Ruby`
- [Alltube](https://www.alltubedownload.net) - Web interface for [youtube-dl](https://github.com/ytdl-org/youtube-dl), a program to download videos and audio from [more than 100 websites](https://ytdl-org.github.io/youtube-dl/supportedsites.html). ([源码](https://github.com/Rudloff/alltube)) `GPL-3.0` `PHP`
- [AmIUnique](https://amiunique.org/) - Learn how identifiable you are on the Internet (browser fingerprinting tool). ([源码](https://github.com/DIVERSIFY-project/amiunique)) `MIT` `Java`
- [Baserow](https://baserow.io/) - Open source online database tool and Airtable alternative. Create your own database without technical experience. ([源码](https://gitlab.com/bramw/baserow)) `MIT` `Python/Nodejs`
- [Beehive](https://github.com/muesli/beehive) - Flexible event and agent system, which allows you to create your own agents that perform automated tasks triggered by events and filters. `AGPL-3.0` `Go`
- [betanin](https://github.com/sentriz/betanin/) - Music organization man-in-the-middle of your torrent client and music player. Based on beets.io, similar to Sonarr and Radarr. `GPL-3.0` `Python`
- [ChiefOnboarding](https://chiefonboarding.com) - Employee onboarding platform that allows you to provision user accounts and create sequences with todo items, resources, text/email/Slack messages, and more! Available as a web portal and Slack bot. ([源码](https://github.com/chiefonboarding/ChiefOnboarding)) `AGPL-3.0` `Python`
- [CouchPotato](https://couchpota.to/) - CouchPotato is an automatic Video Library Manager for Movies. Automatic torrent/nzb searching, downloading, and processing at the qualities you want. ([源码](https://github.com/CouchPotato/CouchPotatoServer)) `GPL-3.0` `Python`
- [Episodes](https://github.com/guptachetan1997/Episodes) `⚠` - Self Hosted TV show Episode tracker and recommender built using django, bootstrap4. `MIT` `Python`
- [Exadel CompreFace](https://exadel.com/solutions/compreface/) - face recognition system that provides REST API for face recognition, face detection, and other face services, and is easily deployed with docker. There are SDKs for Python and JavaScript languages. Can be used without prior machine learning skills. ([源码](https://github.com/exadel-inc/CompreFace)) `Apache-2.0` `Docker/Java/Nodejs`
- [feed2toot](https://feed2toot.readthedocs.io/) - Feed2toot parses a RSS feed, extracts the last entries and sends them to Mastodon. ([源码](https://gitlab.com/chaica/feed2toot)) `GPL-3.0` `Python`
- [feedmixer](https://github.com/cristoper/feedmixer) - FeedMixer is a WSGI (Python3) micro web service which takes a list of feed URLs and returns a new feed consisting of the most recent n entries from each given feed(Returns Atom, RSS, or JSON). ([Demo](https://mretc.net/feedmixer/json?f=https://hnrss.org/newest&f=https://americancynic.net/atom.xml&n=1)) `WTFPL` `Python`
- [Headphones](https://github.com/rembo10/headphones) - Automated music downloader for NZB and Torrent, written in Python. It supports SABnzbd, NZBget, Transmission, µTorrent, Deluge and Blackhole. `GPL-3.0` `Python`
- [Healthchecks](https://healthchecks.io/) - Django app which listens for pings and sends alerts when pings are late. ([源码](https://github.com/healthchecks/healthchecks)) `BSD-3-Clause` `Python`
- [homebank-converter](https://github.com/Binnette/homebank-converter) - Web app to convert an export bank file to compatible Homebank csv. ([Demo](https://binnette.github.io/homebank-converter/)) `AGPL-3.0` `HTML5`
- [HRConvert2](https://github.com/zelon88/HRConvert2) - Drag-and-drop file conversion server with session based authentication, automatic temporary file maintenance, and logging capability. `GPL-3.0` `PHP`
- [Huginn](https://github.com/huginn/huginn) - Allows you to build agents that monitor and act on your behalf. `MIT` `Ruby`
- [Kibitzr](https://kibitzr.github.io) - Lightweight personal web assistant with powerful integrations. ([源码](https://github.com/kibitzr/kibitzr)) `MIT` `Python`
- [Krayin](https://krayincrm.com/) - Free and Opensource Laravel CRM Application. ([源码](https://github.com/krayin/laravel-crm)) `MIT` `PHP`
- [LazyLibrarian](https://gitlab.com/LazyLibrarian/LazyLibrarian) `⚠` - LazyLibrarian is a program to follow authors and grab metadata for all your digital reading needs. It uses a combination of Goodreads Librarything and optionally GoogleBooks as sources for author info and book info. `GPL-3.0` `Python`
- [Leon](https://getleon.ai) - Open-source personal assistant who can live on your server. ([源码](https://github.com/leon-ai/leon)) `MIT` `Nodejs`
- [Lidarr](https://lidarr.audio/) - Lidarr is a music collection manager for Usenet and BitTorrent users. ([源码](https://github.com/Lidarr/Lidarr)) `GPL-3.0` `C#`
- [Medusa](https://pymedusa.com/) - Automatic Video Library Manager for TV Shows. It watches for new episodes of your favorite shows, and when they are posted it does its magic. ([源码](https://github.com/pymedusa/Medusa)) `GPL-3.0` `Python`
- [MeTube](https://github.com/alexta69/metube) - Web GUI for youtube-dl, with playlist support. Allows downloading videos from dozens of websites. `AGPL-3.0` `Python/Nodejs/Docker`
- [n8n](https://n8n.io/) - Free node based Workflow Automation Tool. Easily automate tasks across different services. ([源码](https://github.com/n8n-io/n8n)) `Apache-2.0` `Nodejs`
- [nefarious](https://github.com/lardbit/nefarious) - Web application that automates downloading Movies and TV Shows. `GPL-3.0` `Python`
- [NocoDB](https://www.nocodb.com/) - No-code platform that turns any database into a smart spreadsheet. It can be considered as an Airtable or Smartsheet alternative. ([源码](https://github.com/nocodb/nocodb)) `GPL-3.0` `Nodejs`
- [OliveTin](https://github.com/OliveTin/OliveTin) - OliveTin is a web interface for running Linux shell commands. `AGPL-3.0` `Go`
- [Patrowl](https://github.com/Patrowl/PatrowlManager) - Open Source, Smart and Scalable Security Operations Orchestration Platform. `AGPL-3.0` `Python`
- [Podgrab](https://github.com/akhilrex/podgrab) - Lightweight podcast manager and automatic podcast episode downloader. It will monitor podcasts for your and download them automatically whenever a new episode goes live. `GPL-3.0` `Docker/Go`
- [pyLoad](https://pyload.net/) - Lightweight, customizable and remotely manageable downloader for 1-click-hosting sites like rapidshare.com or uploaded.to. ([源码](https://github.com/pyload/pyload)) `GPL-3.0` `Python`
- [Radarr](https://radarr.video/) - Radarr is an independent fork of Sonarr reworked for automatically downloading movies via Usenet and BitTorrent, à la Couchpotato. ([源码](https://github.com/Radarr/Radarr)) `GPL-3.0` `C#`
- [SickRage](https://www.sickrage.ca) - SickRage is an automatic Video Library Manager for TV Shows. Automatic torrent/nzb searching, downloading, and processing at the qualities you want. ([源码](https://github.com/SickRage/SickRage)) `GPL-3.0` `Python`
- [SiteInspector](https://www.getsiteinspector.com/) - Web-based tool for catching spelling errors, grammatical errors, broken links, and other errors on websites. ([Demo](https://demo.getsiteinspector.com/reports), [源码](https://github.com/siteinspector/siteinspector)) `AGPL-3.0` `Ruby`
- [Sonarr](https://sonarr.tv/) - Automatic TV Shows downloader and manager for Usenet and BitTorrent. It can grab, sort and rename new episodes and automatically upgrade the quality of files already downloaded when a better quality format becomes available. ([源码](https://github.com/Sonarr/Sonarr)) `GPL-3.0` `C#`
- [StackStorm](https://stackstorm.com) - StackStorm (aka _IFTTT for Ops_) is event-driven automation for auto-remediation, security responses, troubleshooting, deployments, and more. Includes rules engine, workflow, 160 integration packs with 6000+ actions and ChatOps. ([源码](https://github.com/StackStorm/st2)) `Apache-2.0` `Python`
- [WebUI-aria2](https://github.com/ziahamza/webui-aria2) - Interface to interact with the aria2 downloader. Very simple to use, just download and open index.html in any web browser. ([Demo](https://ziahamza.github.io/webui-aria2/)) `MIT` `HTML5`
- [ydl_api](https://github.com/Totonyus/ydl_api) - Simple youtube-dl REST API to launch downloads on a distant server. `Unlicense` `Python`
- [YoutubeDL-Material](https://github.com/Tzahi12345/YoutubeDL-Material) - Material Design inspired YouTube downloader, based on youtube-dl. Supports playlists, quality select, search, dark mode and much more, all with a clean and modern design. `MIT` `Nodejs`
- [Zenbot](https://github.com/DeviaVir/zenbot) - Zenbot is a lightweight, extendable, artificially intelligent trading bot for Bitcoin, Ether, Litecoin, and more. `MIT` `Nodejs`
- [ZeroQueue](https://github.com/thezeroqueue/zeroqueue) - A low-code queue management system that lets you run scheduled jobs for anything. `GPL-3.0` `Nodejs`
- [µTask](https://github.com/ovh/utask) - µTask is an automation engine that models and executes business processes declared in yaml. `BSD-3-Clause` `Go`


### Blogging Platforms

**[`^        返回顶部        ^`](#)**

_关联: [Static Site Generators](#static-site-generators), [Content Management Systems (CMS)](#content-management-systems-cms)_

_See also: [WeblogMatrix](https://www.weblogmatrix.org/)_

- [Antville](https://antville.org) - Free, open source project aimed at the development of a high performance, feature rich weblog hosting software. ([源码](https://github.com/antville/antville)) `Apache-2.0` `Javascript`
- [Blog](https://github.com/m1k1o/blog) - Facebook-styled blog. Free, extremely lightweight, single-user and easy to install. ([Demo](https://blog.m1k1o.net/)) `GPL-3.0` `PHP`
- [Blogotext](https://github.com/BlogoText/blogotext) - Free blog-engine written in PHP and using SQLite. This offers you both an unmatched simplicity during installation and great performances. `MIT` `PHP`
- [Bludit](https://www.bludit.com/) `⚠` - Simple application to build a site or blog in seconds. Bludit uses flat-files (text files in JSON format) to store posts and pages. ([Demo](https://demo.bludit.com/), [源码](https://github.com/bludit/bludit)) `MIT` `PHP`
- [Cadmus](https://github.com/ldemafelix/cadmus) - Cadmus is an extremely lightweight, flat-file blogging platform powered by Markdown. `MIT` `PHP`
- [Canvas](https://trycanvas.app/) - A Laravel publishing platform. ([源码](https://github.com/austintoddj/canvas)) `MIT` `PHP`
- [Chyrp Lite](https://chyrplite.net) - Extra-awesome, extra-lightweight blog engine. ([源码](https://github.com/xenocrat/chyrp-lite)) `BSD-3-Clause` `PHP`
- [Dante Stories](https://dante-stories.herokuapp.com/) - Self hosted Medium platform built with Ruby on Rails. ([源码](https://github.com/michelson/dante-stories)) `MIT` `Ruby`
- [Dotclear](https://dotclear.org/) - Take control over your blog. ([源码](https://hg.dotclear.org/dotclear)) `GPL-2.0` `PHP`
- [Formtools](https://formtools.org/) - Powerful, flexible, free and open source PHP/MySQL script to manage your forms and data. ([源码](https://github.com/formtools)) `GPL-2.0` `PHP`
- [Ghost](https://ghost.org/) - Just a blogging platform. ([源码](https://github.com/TryGhost/Ghost)) `MIT` `Nodejs`
- [Haven](https://havenweb.org/) - Private blogging system with markdown editing and built in RSS reader. ([Demo](https://havenweb.org/demo.html), [源码](https://github.com/havenweb/haven)) `MIT` `Ruby`
- [Hotglue](https://hotglue.me/) - Freehand CMS which allows to construct websites directly in a web-browser. It uses flat files for storage and provides an intuitive GUI. ([Demo](https://hotglue.me/demo/), [源码](https://github.com/k0a1a/hotglue2)) `GPL-3.0` `PHP`
- [htmly](https://www.htmly.com/) - Databaseless Blogging Platform (Flat-File Blog). ([Demo](https://demo.htmly.com/), [源码](https://github.com/danpros/htmly)) `GPL-2.0` `PHP`
- [Known](https://withknown.com/) - A collaborative social publishing platform. ([源码](https://github.com/idno/known)) `Apache-2.0` `PHP`
- [Plume](https://joinplu.me/) - Federated blogging engine, based on ActivityPub. ([源码](https://github.com/Plume-org/Plume)) `AGPL-3.0` `Rust`
- [PluXml](https://pluxml.org) - XML-based blog/CMS platform. ([源码](https://github.com/pluxml/PluXml)) `GPL-1.0` `PHP`
- [Serendipity](https://docs.s9y.org/) - Serendipity (s9y) is a highly extensible and customizable PHP blog engine using Smarty templating. ([源码](https://github.com/s9y/serendipity)) `BSD-3-Clause` `PHP`


### Booking and Scheduling

**[`^        返回顶部        ^`](#)**

_关联: [Polls and Events](#polls-and-events)_

- [Alf.io](https://alf.io/) - The open source ticket reservation system. ([Demo](https://demo.alf.io/authentication), [源码](https://github.com/alfio-event/alf.io)) `GPL-3.0` `Java`
- [Calendso](https://calendso.com/) - The open-source online appointment scheduling system. ([Demo](https://app.calendso.com/bailey), [源码](https://github.com/calendso/calendso)) `MIT` `Nodejs`
- [Easy!Appointments](https://easyappointments.org/) - A highly customizable web application that allows your customers to book appointments with you via the web. ([Demo](https://easyappointments.org/demo/), [源码](https://github.com/alextselegidis/easyappointments)) `GPL-3.0` `PHP`


### Bookmarks and Link Sharing

**[`^        返回顶部        ^`](#)**

- [dyu bookmarks](https://github.com/dyu/bookmarks) - Single-threaded/process bookmark app powered by leveldb and uWebSockets. Supports importing from Delicious and Chrome. ([Demo](https://dyuproject.com/bookmarks/)) `Apache-2.0` `Java`
- [Espial](https://github.com/jonschoning/espial) - An open-source, web-based bookmarking server. `AGPL-3.0` `Haskell`
- [Firefox Account Server](https://mozilla-services.readthedocs.io/en/latest/howtos/run-fxa.html) - This allows you to host your own Firefox accounts server. ([源码](https://github.com/mozilla/fxa)) `MPL-2.0` `Nodejs, Java`
- [Firefox Sync Server](https://github.com/mozilla-services/syncserver) - Sync Firefox bookmarks, passwords, history, tabs, preferences. `MPL-2.0` `Python`
- [Geekmarks](https://geekmarks.dmitryfrank.com/) - Personal bookmarking service focused on speed and organization using hierarchical tags. ([源码](https://github.com/dimonomid/geekmarks)) `BSD-2-Clause` `Go`
- [golinks](https://git.mills.io/prologic/golinks) - Web application that allows you to create smart bookmarks, commands and aliases by pointing your web browser's default search engine at a running instance. Similar to bunny1 or yubnub. ([Demo](https://search.mills.io)) `MIT` `Go`
- [Hackershare](https://github.com/hackershare/hackershare) - Social bookmarks website for hackers. ([Demo](https://hackershare.dev)) `MIT` `Ruby`
- [LinkAce](https://www.linkace.org/) - A bookmark archive with automatic backups to the Internet Archive, link monitoring, and a full REST API. Installation is done via Docker, or as a simple PHP application. ([Demo](https://demo.linkace.org/), [源码](https://github.com/Kovah/LinkAce/)) `GPL-3.0` `PHP`
- [linkding](https://github.com/sissbruecker/linkding) - Minimal bookmark management with a fast and clean UI. Simple installation through Docker and can run on your Raspberry Pi. ([Demo](https://demo.linkding.link/)) `MIT` `Docker/Python/Nodejs`
- [Lobsters](https://lobste.rs) - Run your own link aggregation site. ([源码](https://github.com/jcs/lobsters)) `BSD-3-Clause` `Ruby`
- [No Fuss Bookmarks](https://nofussbm.herokuapp.com/signup.html) - Very simple software and service to store bookmarks especially designed for hackers (that don't need fancy interfaces, but nice API). ([源码](https://github.com/mapio/nofussbm)) `GPL-3.0` `Python`
- [Pinry](https://getpinry.com/) - The tiling image board system for people who want to save, tag, and share images, videos, and webpages. ([源码](https://github.com/pinry/pinry)) `BSD-2-Clause` `Python`
- [Reminiscence](https://github.com/kanishka-linux/reminiscence) - Self-Hosted Bookmark And Archive Manager. `AGPL-3.0` `Python`
- [Shaarli](https://github.com/shaarli/Shaarli) - Personal, minimalist, super-fast, no-database bookmarking and link sharing platform. ([Demo](https://demo.shaarli.org)) `Zlib` `PHP`
- [Shiori](https://github.com/go-shiori/shiori) - Simple bookmark manager built with Go. `MIT` `Go`
- [ubookmark](https://ungleich.ch/u/projects/ubookmark/) - LDAP enabled bookmarking service. ([Demo](https://ipv6.blog), [源码](https://code.ungleich.ch/ungleich-public/ubookmark/)) `GPL-2.0` `Python`
- [unmark](https://unmark.it/) - Open source to do app for links. ([源码](https://github.com/cdevroe/unmark)) `MIT` `PHP`
- [xBrowserSync](https://www.xbrowsersync.org) - Open source tool for syncing browser data between browsers and devices. ([源码](https://github.com/xBrowserSync)) `MIT` `Nodejs`

### Calendar & Contacts

**[`^        返回顶部        ^`](#)**

_关联: [Groupware](#groupware)_

_See also: [Comparison of CalDAV and CardDAV implementations - Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_CalDAV_and_CardDAV_implementations)_


### Calendar & Contacts - CalDAV or CardDAV Servers

**[`^        返回顶部        ^`](#)**

- [Baïkal](https://sabre.io/baikal/) - Lightweight CalDAV and CardDAV server based on sabre/dav. ([源码](https://github.com/sabre-io/Baikal)) `GPL-3.0` `PHP`
- [calypso](https://keithp.com/calypso/) - Python-based CalDAV and CardDAV server, forked from Radicale. ([源码](https://keithp.com/git/calypso.git)) `GPL-3.0` `Python`
- [DAViCal](https://www.davical.org/) - Server for calendar sharing (CalDAV) that uses a PostgreSQL database as a data store. ([源码](https://gitlab.com/davical-project/davical)) `GPL-2.0` `PHP`
- [Davis](https://github.com/tchapi/davis/) - A simple, dockerizable and fully translatable admin interface for sabre/dav based on Symfony 5 and Bootstrap 4, largely inspired by Baïkal. `MIT` `PHP`
- [DecSync CC](https://f-droid.org/packages/org.decsync.cc/) - Serverless contacts, calendar synchronization using your own file syncing method i.e Syncthing, Nextcloud etc. ([源码](https://github.com/39aldo39/DecSyncCC)) `GPL-3.0` `Kotlin`
- [Etebase (EteSync)](https://www.etebase.com/) - End-to-end encrypted and journaled personal information server supporting calendar and contact data, offering its own clients. ([源码](https://github.com/etesync/server)) `AGPL-3.0` `Python/Django`
- [Radicale](https://radicale.org/) - Simple calendar and contact server with extremely low administrative overhead. ([源码](https://github.com/Kozea/Radicale)) `GPL-3.0` `Python`
- [SabreDAV](https://sabre.io/) - Open source CardDAV, CalDAV, and WebDAV framework and server. ([源码](https://github.com/sabre-io/dav)) `MIT` `PHP`
- [Xandikos](https://www.xandikos.org/) - Open source CardDAV and CalDAV server with minimal administrative overhead, backed by a Git repository. ([源码](https://github.com/jelmer/xandikos)) `GPL-3.0` `Python`


### Calendar & Contacts - CalDAV or CardDAV Web-based Clients

**[`^        返回顶部        ^`](#)**

- [AgenDAV](https://agendav.org/) - Multilanguage CalDAV web client with a rich AJAX interface and shared calendars support. ([源码](https://github.com/agendav/agendav)) `GPL-3.0` `PHP`
- [EteSync Web](https://www.etesync.com/faq/#web-client) - EteSync's official Web-based client (i.e., their Web app). ([Demo](https://client.etesync.com/), [源码](https://github.com/etesync/etesync-web)) `AGPL-3.0` `Javascript`
- [InfCloud](https://www.inf-it.com/open-source/clients/infcloud/) - Open source CalDAV/CardDAV web client implementation. ([Demo](https://www.inf-it.com/infcloud/), [源码](https://www.inf-it.com/InfCloud_0.13.1.zip)) `AGPL-3.0` `Javascript`

### 通信

**[`^        返回顶部        ^`](#)**


### 通信 - 定制通信系统

**[`^        返回顶部        ^`](#)**

- [BluetoothCommunicatorExample](https://github.com/niedev/BluetoothCommunicatorExample) - Bluetooth LE chat app to communicate between android devices with P2P architecture. ([Clients](https://github.com/niedev/RTranslator)) `Apache-2.0` `Java`
- [Centrifugo](https://github.com/centrifugal/centrifugo) - Language-agnostic real-time messaging (Websocket or SockJS) server. ([Demo](https://github.com/centrifugal/centrifugo#demo)) `MIT` `Go`
- [Chaskiq](https://chaskiq.io) - Full featured livechat, helpcenter and CRM as an alternative to Intercom & Drift, Crisp and others. ([源码](https://github.com/chaskiq/chaskiq)) `AGPL-3.0` `Ruby`
- [Chatwoot](https://www.chatwoot.com) - Self-hosted customer communication platform, an alternative to Intercom & Zendesk. ([源码](https://github.com/chatwoot/chatwoot)) `MIT` `Ruby`
- [Cherry](https://github.com/rafael-santiago/cherry) - Tiny webchat server. `GPL-2.0` `Go`
- [Conduit](https://conduit.rs/) - A simple, fast, and reliable chat server powered by Matrix. ([源码](https://gitlab.com/famedly/conduit)) `Apache-2.0` `Rust`
- [Darkwire.io](https://github.com/darkwire/darkwire.io) - End-to-end encrypted instant web chat. `MIT` `Nodejs`
- [Element](https://element.io) - Fully-featured Matrix client for Web, iOS & Android. ([源码](https://github.com/vector-im/element-web)) `Apache-2.0` `Javascript`
- [Enigma Reloaded](https://github.com/enigma-reloaded/enigma-reloaded) - DIY Message and file encryption for any platform. `GPL-3.0` `Javascript`
- [Freenet](https://freenetproject.org/index.html) - Anonymously share files, browse and publish _freesites_ (web sites accessible only through Freenet) and chat on forums. ([源码](https://github.com/freenet/fred)) `GPL-2.0` `Java`
- [Galene](https://galene.org/) - Galène (or Galene) is a videoconference server (an “SFU”) that is easy to deploy and that requires moderate server resources. ([源码](https://github.com/jech/galene)) `MIT` `Go`
- [GNUnet](https://gnunet.org/) - Free software framework for decentralized, peer-to-peer networking. ([源码](https://gnunet.org/git/)) `GPL-3.0` `C`
- [Gotify](https://gotify.net/) - Self-hosted notification server with Android and CLI clients, similar to PushBullet. ([源码](https://github.com/gotify/server), [Clients](https://github.com/gotify/android)) `MIT` `Go`
- [Hawkpost](https://hawkpost.co) - HawkPost is a web app that lets you create unique links that you can share with a person that desires to send you important information but doesn't know how to encrypt it. The message is encrypted in their browser and sent to your email address. ([源码](https://github.com/whitesmith/hawkpost)) `MIT` `Python`
- [Jami](https://jami.net/) - Free and universal communication platform which preserves the user's privacy and freedoms (formerly GNU Ring). ([源码](https://git.ring.cx/savoirfairelinux/ring-project)) `GPL-3.0` `C++`
- [Jitsi Meet](https://jitsi.org/Projects/JitsiMeet) - Jitsi Meet is an OpenSource (MIT) WebRTC Javascript application that uses Jitsi Videobridge to provide high quality, scalable video conferences. ([源码](https://github.com/jitsi/jitsi-meet)) `MIT` `Javascript`
- [Jitsi Video Bridge](https://jitsi.org/Projects/JitsiVideobridge) - WebRTC compatible Selective Forwarding Unit (SFU) that allows for multiuser video communication. ([源码](https://github.com/jitsi/jitsi-videobridge)) `Apache-2.0` `Java`
- [KChat](https://github.com/php-kchat/kchat) - PHP Based Live Chat Application. `Apache-2.0` `PHP`
- [LeapChat](https://github.com/cryptag/leapchat) - Ephemeral, encrypted, in-browser chat rooms. `AGPL-3.0` `Javascript`
- [Lets-Chat](https://sdelements.github.io/lets-chat/) - Self hosted chat suite written in Node. ([源码](https://github.com/sdelements/lets-chat)) `MIT` `Nodejs`
- [LibreNews](https://librenews.io/) - Decentralized and secure breaking news notification system. ([源码](https://github.com/milesmcc/LibreNews-Server/)) `GPL-3.0` `Python`
- [Live Helper Chat](https://livehelperchat.com/) - Live Support chat for your website. ([源码](https://github.com/LiveHelperChat/livehelperchat)) `Apache-2.0` `PHP`
- [LiveKit](https://livekit.io/) - Modern, scalable WebRTC conferencing platform with client SDKs. ([Demo](https://livekit.io/playground), [源码](https://github.com/livekit/livekit-server)) `Apache-2.0` `Go`
- [Matrix Console Web](https://matrix.org/docs/projects/client/matrix-console-web) - Web client meant to be a showcase of Matrix capabilities, and reference implementation of the Matrix standard. ([源码](https://github.com/matrix-org/matrix-angular-sdk)) `Apache-2.0` `Javascript`
- [Mattermost](https://mattermost.org/) - Open-source, on-prem Slack-alternative. It can be integrated with Gitlab. ([源码](https://github.com/mattermost/mattermost-server)) `AGPL-3.0/Apache-2.0` `Go`
- [MiAOU](https://miaou.dystroy.org/login) - Multi-room persistent chat server. ([源码](https://github.com/Canop/miaou)) `MIT` `Nodejs`
- [Mibew](https://mibew.org) - Mibew Messenger is an open-source live support application written in PHP and MySQL. It enables one-on-one chat assistance in real-time directly from your website. ([Demo](https://mibew.org/demo2), [源码](https://github.com/Mibew/mibew)) `Apache-2.0` `PHP`
- [Mumble](https://wiki.mumble.info/wiki/Main_Page) - Low-latency, high quality voice/text chat software. ([源码](https://github.com/mumble-voip/mumble), [Clients](https://wiki.mumble.info/wiki/3rd_Party_Applications)) `BSD-3-Clause` `C++`
- [OTS](https://ots.fyi/) - One-Time-Secret sharing platform with a symmetric 256bit AES encryption in the browser. ([源码](https://github.com/Luzifer/ots)) `Apache-2.0` `Go`
- [Papercups](https://papercups.io/) - An open source live customer chat web app written in Elixir. ([Demo](https://app.papercups.io/demo), [源码](https://github.com/papercups-io/papercups)) `MIT` `Elixir`
- [PushBits](https://github.com/pushbits/server) - Self-hosted notification server for relaying push notifications via Matrix, similar to PushBullet and Gotify. `ISC` `Go`
- [pWS](https://github.com/soketi/pws) - pWS is a free, open-source Pusher drop-in alternative. `MIT` `Nodejs`
- [Rallly](https://rallly.co) - Rallly is a free collaborative scheduling service. ([源码](https://github.com/lukevella/Rallly)) `CC-BY-SA-4.0` `Nodejs`
- [RetroShare](https://retroshare.cc) - Secured and decentralized communication system. Offers decentralized chat, forums, messaging, file transfer. ([源码](https://github.com/RetroShare/RetroShare)) `GPL-2.0` `C++`
- [Revolt](https://revolt.chat/) - Revolt is a user-first chat platform built with modern web technologies. ([源码](https://github.com/revoltchat)) `AGPL-3.0` `Rust`
- [Rocket.Chat](https://rocket.chat/) - Teamchat solution similar to Gitter.im or Slack. ([源码](https://github.com/RocketChat/Rocket.Chat)) `MIT` `Nodejs`
- [Shhh](https://github.com/smallwat3r/shhh) - Keep secrets out of emails or chat logs, share them using secure links with passphrase and expiration dates. `MIT` `Python`
- [Spectrum 2](https://spectrum.im/) - Spectrum 2 is an open source instant messaging transport.  It allows users to chat together even when they are using different IM networks. ([源码](https://github.com/SpectrumIM/spectrum2)) `GPL-3.0` `C++`
- [Spreed](https://www.spreed.me/) - WebRTC audio/video calls, conferencing server, and web client. ([源码](https://github.com/strukturag/spreed-webrtc)) `AGPL-3.0` `Go`
- [StoneAge Messenger](https://cweb.gitlab.io/StoneAge.html) - A self-hosted Android messenger, S3-compatible storage is the only backend needed. ([源码](https://gitlab.com/cweb-repos/cweb-conversations), [Clients](https://f-droid.org/en/packages/com.cweb.messenger/)) `GPL-3.0` `Java`
- [Synapse](https://matrix.org/docs/projects/server/synapse) - Server for [Matrix](https://matrix.org/), an open standard for decentralized persistent communication. ([源码](https://github.com/matrix-org/synapse)) `Apache-2.0` `Python`
- [Syndie](https://syndie.de) - Syndie is a libre system for operating distributed forums. `CC0-1.0` `Java`
- [TextBelt](https://github.com/typpo/textbelt) `⚠` - Outgoing SMS API that uses carrier-specific gateways to deliver your text messages for free, and without ads. `MIT` `Javascript`
- [Tinode](https://github.com/tinode) - Instant messaging platform. Backend in Go. Clients: Swift iOS, Java Android, JS webapp, scriptable command line; chatbots. ([Demo](https://sandbox.tinode.co/), [源码](https://github.com/tinode/chat), [Clients](https://github.com/tinode/webapp)) `GPL-3.0` `Go`
- [Tox](https://tox.chat/) - Distributed, secure messenger with audio and video chat capabilities. ([源码](https://github.com/TokTok/c-toxcore)) `GPL-3.0` `C`
- [Tuber](https://blog.trailofbits.com/2015/12/15/self-hosted-video-chat-with-tuber/) - Peer-to-peer video chat that works. ([源码](https://github.com/trailofbits/tubertc)) `MIT` `Javascript`
- [WBO](https://github.com/lovasoa/whitebophir#wbo) -  A web Whiteboard to collaborate in real-time on schemas, drawings, and notes. ([Demo](https://wbo.ophir.dev/)) `AGPL-3.0` `Nodejs/Docker`
- [ZeroNet](https://zeronet.io/) `⚠` - Open, free, and uncensorable websites, using Bitcoin cryptography and BitTorrent network. ([源码](https://github.com/HelloZeroNet/ZeroNet)) `GPL-2.0` `Python`
- [Zulip](https://zulip.org) - Zulip is a powerful, open source group chat application. ([源码](https://github.com/zulip/zulip)) `Apache-2.0/Other` `Python`


### 通信 - Email

**[`^        返回顶部        ^`](#)**


### 通信 - 电子邮件 - 完整的解决方案

**[`^        返回顶部        ^`](#)**

邮件服务器的简单部署，例如为没有经验或没有耐心的管理员。

- [AnonAddy](https://anonaddy.com) - 开源的电子邮件转发服务，用于创建别名。 ([源码](https://github.com/anonaddy/anonaddy)) `MIT` `PHP`
- [DebOps](https://docs.debops.org/) - 你的基于Debian的数据中心在一个盒子里。一组通用的 Ansible 角色，可以用来管理 Debian 或 Ubuntu 主机。 ([源码](https://github.com/debops/debops)) `GPL-3.0-only` `YAML/Ansible/Python`
- [docker-mailserver](https://docker-mailserver.github.io/docker-mailserver/edge/) - 生产就绪的全栈但简单的邮件服务器（SMTP、IMAP、LDAP、反垃圾邮件、防病毒等）在一个容器内运行。只有配置文件，没有SQL数据库。 ([源码](https://github.com/docker-mailserver/docker-mailserver)) `MIT` `Docker`
- [emailwiz](https://github.com/LukeSmithxyz/emailwiz) - Luke Smith的bash脚本可以完全自动化地在debian上设置Postfix/Dovecot/SpamAssassin/OpenDKIM服务器。 `GPL-3.0` `Bash`
- [Excision Mail](https://github.com/Excision-Mail/Excision-Mail) - 基于OpenSMTPD的全栈式安全邮件服务器，适用于OpenBSD，使用ansible。 `ISC` `Shell/Ansible`
- [homebox](https://github.com/progmaticltd/homebox) - 一套Ansible脚本，用于在Debian上部署一个功能齐全的邮件服务器。尽可能的不引人注目和自动，注重稳定性和安全性。 `GPL-3.0` `Shell`
- [Inboxen](https://inboxen.org) - Inboxen是一项为你提供无限数量的独特收件箱的服务。 ([源码](https://github.com/Inboxen/Inboxen)) `GPL-3.0` `Python`
- [iRedMail](https://www.iredmail.org/) - 基于Postfix和Dovecot的全功能邮件服务器解决方案。 ([源码](https://github.com/iredmail/iRedMail)) `GPL-3.0` `Shell`
- [Maddy Mail Server](https://github.com/foxcpp/maddy) - 一体化的邮件服务器，实现SMTP（MTA和MX）和IMAP。用单个守护程序取代Postfix、Dovecot、OpenDKIM、OpenSPF、OpenDMARC。 `GPL-3.0` `Go`
- [Mail-in-a-Box](https://mailinabox.email/) - 通过一个命令将任何Ubuntu服务器变成一个功能齐全的邮件服务器。 ([源码](https://github.com/mail-in-a-box/mailinabox)) `CC0-1.0` `Shell`
- [Mailcow](https://mailcow.email/) - 基于Dovecot、Postfix和其他开源软件的邮件服务器套件，提供了一个现代化的Web UI进行管理。 ([源码](https://github.com/mailcow/mailcow-dockerized)) `GPL-2.0` `Docker/PHP`
- [Mailu](https://mailu.io/) - Mailu是一个简单但功能齐全的邮件服务器，是一套Docker镜像。 ([源码](https://github.com/Mailu/Mailu)) `MIT` `Docker/Python`
- [Modoboa](https://modoboa.org/en/) - Modoboa是一个邮件托管和管理平台，包括一个现代和简化的网络用户界面。 ([源码](https://github.com/modoboa/modoboa)) `ISC` `Python`
- [Ptorx](https://github.com/xyfir/ptorx) - 电子邮件隐私。用别名转发匿名发送和接收。 `GPL-3.0` `Nodejs`
- [Simple NixOS Mailserver](https://gitlab.com/simple-nixos-mailserver/nixos-mailserver) - 利用Nix生态系统的完整邮件服务器解决方案。 `GPL-3.0` `Nix`
- [SimpleLogin](https://simplelogin.io) - 开源的电子邮件别名解决方案，保护你的电子邮件地址。配有浏览器扩展和移动应用程序。 ([源码](https://github.com/simple-login/app)) `MIT` `Docker/Python`
- [wildduck](https://wildduck.email/) - 可扩展的无SPOF IMAP/POP3邮件服务器。 ([源码](https://github.com/nodemailer/wildduck)) `EUPL-1.2` `Nodejs`


### 通讯 - Email - 邮件发送代理

**[`^        返回顶部        ^`](#)**

MDAs - IMAP/POP3 软件

- [Cyrus IMAP](https://www.cyrusimap.org/) - 电子邮件（IMAP/POP3）、联系人和日历服务器。 ([源码](https://github.com/cyrusimap/cyrus-imapd )) `BSD-3-Clause-Attribution` `C`
- [Dovecot](https://www.dovecot.org/) - IMAP 和 POP3 服务器的编写主要考虑到了安全问题。 ([源码](https://github.com/dovecot/core)) `MIT/LGPL-2.1` `C`
- [MailForm](https://github.com/Feuerhamster/mailform) - Formspree和SendGrid的轻量级自我托管的开源替代品。 `Apache-2.0` `Nodejs`
- [Piler](https://www.mailpiler.org/wiki/start) - 功能丰富的开源电子邮件归档解决方案。 ([源码](https://bitbucket.org/jsuto/piler)) `GPL-3.0` `C`


### 通讯 - Email - 邮件传输代理

**[`^        返回顶部        ^`](#)**

MTAs / SMTP servers

- [chasquid](https://blitiri.com.ar/p/chasquid/) - SMTP（电子邮件）服务器，注重简单性、安全性和易操作性。 ([源码](https://blitiri.com.ar/git/r/chasquid/)) `Apache-2.0` `Go`
- [Courier MTA](https://www.courier-mta.org/) - 快速、可扩展的企业邮件/群件服务器，提供ESMTP、IMAP、POP3、网络邮件、邮件列表、基于网络的基本日历和日程安排服务。 ([源码](https://www.courier-mta.org/repo.html)) `GPL-3.0` `C`
- [Exim](https://www.exim.org/) - 剑桥大学开发的消息传输代理（MTA）。 ([源码](https://git.exim.org/exim.git)) `GPL-3.0` `C`
- [Haraka](https://haraka.github.io/) - 用 Javascript 编写的高性能、可插件的SMTP服务器。 ([源码](https://github.com/haraka/Haraka)) `MIT` `Javascript`
- [MailCatcher](https://mailcatcher.me/) - Ruby gem部署了一个简单的SMTP MTA网关，接受所有邮件并显示在Web界面。对调试或开发很有用。 ([源码](https://github.com/sj26/mailcatcher)) `MIT` `Ruby`
- [Maildrop](https://gitlab.com/markbeeson/maildrop) - 一次性的电子邮件SMTP服务器，对开发也很有用。 `MIT` `Scala`
- [MailHog](https://github.com/mailhog/MailHog) - 小型Golang可执行文件，运行一个SMTP MTA网关，接受所有邮件并显示在Web界面。对调试或开发有用。 `MIT` `Go`
- [OpenSMTPD](https://opensmtpd.org/) - 来自OpenBSD项目的安全SMTP服务器实现。 ([源码](https://cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.sbin/smtpd/)) `ISC` `C`
- [Postfix](http://www.postfix.org/) - 快速、易于管理和安全的Sendmail替代品。 `IPL-1.0` `C`
- [Qmail](https://cr.yp.to/qmail.html) - 安全的Sendmail替代品。 ([源码](https://sources.debian.net/src/netqmail/1.06-5/)) `CC0-1.0` `C`
- [Sendmail](https://www.proofpoint.com/us/products/email-protection/open-source-email-solution) - 信息传输代理（MTA）。 `Sendmail` `C`
- [Slimta](https://www.slimta.org) - 建立在Python上的邮件传输库。 ([源码](https://github.com/slimta/python-slimta)) `MIT` `Python`


### 通讯 - Email - 邮件列表和新闻简报

**[`^        返回顶部        ^`](#)**

邮件列表服务器和群发软件 - 一条信息给许多收件人。

- [Dada Mail](https://dadamailproject.com/) - 基于 Web 的列表管理系统，可用于公告列表和/或讨论列表。 ([源码](https://github.com/justingit/dada-mail)) `GPL-2.0` `Perl`
- [HyperKitty](https://wiki.list.org/HyperKitty) - 开源的Django应用程序，提供一个访问GNU Mailman v3档案的网络接口。 ([Demo](https://lists.mailman3.org/), [源码](https://gitlab.com/mailman/hyperkitty)) `GPL-3.0` `Python`
- [Listmonk](https://listmonk.app/) - 高性能、自我托管的通讯和邮件列表管理器，具有现代仪表板。 ([源码](https://github.com/knadh/listmonk)) `AGPL-3.0` `Go`
- [Mailman](https://www.gnu.org/software/mailman/) - Gnu邮件列表服务器。`GPL-3.0` `Python`
- [Mailtrain](https://mailtrain.org/) - 自我托管的通讯应用。 ([源码](https://github.com/Mailtrain-org/mailtrain)) `GPL-3.0` `Nodejs`
- [MailyHerald](https://mailyherald.org/) - 自我托管的Mailchimp替代品，你可以轻松地与你的网站整合。帮助你发送和管理你的应用程序邮件。它支持电子邮件营销和进行你发送给用户的日常通知流。 ([源码](https://github.com/Sology/maily_herald)) `LGPL-3.0` `Ruby`
- [Mautic](https://www.mautic.org/) - Mautic是营销自动化软件（电子邮件、社交和其他）。 ([源码](https://github.com/mautic/mautic)) `GPL-3.0` `PHP`
- [phpList](https://phplist.org) - 通讯和电子邮件营销，对订阅者、退件和插件进行高级管理。 ([源码](https://github.com/phpList/)) `AGPL-3.0` `PHP`
- [Postal](https://postal.atech.media/) - 功能齐全的开源邮件发送平台，用于接收和发送电子邮件。 ([源码](https://github.com/postalhq/postal)) `MIT` `Ruby`
- [Postorius](https://docs.mailman3.org/projects/postorius/en/latest/) - 访问GNU Mailman的网络用户接口。 ([源码](https://gitlab.com/mailman/postorius/)) `GPL-3.0` `Python`
- [Schleuder](https://schleuder.nadir.org/) - 支持GPG的邮件列表管理器，具有重发功能。 ([源码](https://0xacab.org/schleuder/schleuder/tree/master)) `GPL-3.0` `Ruby`
- [Sympa](https://www.sympa.org/) - 邮件列表管理员。 `GPL-2.0` `Perl`


### 通讯 - Email - Web邮件客户端

**[`^        返回顶部        ^`](#)**

- [Afterlogic WebMail Lite](https://afterlogic.org/webmail-lite) - 为您现有的IMAP邮件服务器、Plesk或cPanel提供快速和易于使用的网络邮件前端。 ([Demo](https://lite.afterlogic.com/), [源码](https://github.com/afterlogic/webmail-lite)) `AGPL-3.0` `PHP`
- [Cypht](https://cypht.org) - 为你的电子邮件账户提供饲料阅读器。 ([源码](https://github.com/jasonmunro/cypht)) `LGPL-2.1` `PHP`
- [IMP](https://www.horde.org/apps/imp/) - HORDE 应用程序，提供对IMAP和POP3账户的网络邮件访问。 ([Demo](http://demo.horde.org/), [源码](https://www.horde.org/download/imp)) `GPL-2.0` `PHP`
- [Isotope Mail](https://blog.marcnuri.com/isotope-mail-client-introduction/) - 用ReactJS和Spring构建的基于微服务的网络邮件客户端。 ([源码](https://github.com/manusa/isotope-mail)) `Apache-2.0` `Docker/Java`
- [MailCare](https://mailcare.io) - 开源的一次性电子邮件地址服务。 ([源码](https://github.com/mailcare/mailcare)) `MIT` `PHP`
- [Mailpile](https://www.mailpile.is/) - 具有搜索、过滤、加密功能等功能的网络邮件客户端。 ([源码](https://github.com/mailpile/Mailpile)) `AGPL-3.0` `Python`
- [RainLoop](https://www.rainloop.net/) - 简单、现代、快速的网络邮件，支持IMAP/SMTP和多账户。 ([Demo](https://mail.rainloop.net), [源码](https://github.com/RainLoop/rainloop-webmail)). `AGPL-3.0` `PHP`
- [Roundcube](https://roundcube.net) - 基于浏览器的IMAP客户端，有一个类似于应用程序的用户界面。 ([源码](https://github.com/roundcube/roundcubemail)) `GPL-3.0` `PHP`
- [SquirrelMail](https://squirrelmail.org) - 另一个基于浏览器的IMAP客户端。 ([源码](https://sourceforge.net/p/squirrelmail/code/HEAD/tree/)) `GPL-2.0` `PHP`


### 通讯 - IRC

**[`^        返回顶部        ^`](#)**

[IRC](https://en.wikipedia.org/wiki/Internet_Relay_Chat) 通讯软件

- [Convos](https://convos.chat/) - 始终在线的网络IRC客户端。 ([Demo](https://convos.chat/#instant-demo), [源码](https://github.com/nordaaker/convos)) `Artistic-2.0` `Perl`
- [Dispatch](https://github.com/khlieng/dispatch) - 用Go语言编写的自我托管的网络IRC客户端。 ([Demo](https://dispatch.khlieng.com/connect)) `MIT` `Go`
- [Ergo](https://ergo.chat/) - 用Go编写的现代IRCv3服务器，结合了ircd、服务框架和bouncer的功能。 ([源码](https://github.com/ergochat/ergo)) `MIT` `Go`
- [Glowing Bear](https://github.com/glowing-bear/glowing-bear/) - WeeChat的一个网络前端。 ([Demo](https://www.glowing-bear.org)) `GPL-3.0` `Javascript`
- [InspIRCd](https://www.inspircd.org/) - 用C++编写的模块化IRC服务器，适用于Linux、BSD、Windows和MacOS。 ([源码](https://github.com/inspircd/inspircd)) `GFDL-1.2-only` `C++`
- [Kiwi IRC](https://kiwiirc.com/) - 反应灵敏的网络IRC客户端，支持主题化。 ([Demo](https://kiwiirc.com/nextclient/), [源码](https://github.com/kiwiirc/kiwiirc)) `Apache-2.0` `Nodejs`
- [ngircd](https://ngircd.barton.de/) - 适用于小型或私人网络的免费、便携和轻量级的互联网中继聊天服务器。 ([源码](https://github.com/ngircd/ngircd)) `GPL-2.0` `C`
- [Quassel IRC](https://quassel-irc.org/) - 分布式IRC客户端，意味着一个（或多个）客户端可以附着在中央核心上，也可以从中央核心上分离出来。 ([源码](https://github.com/quassel/quassel)) `GPL-2.0` `C++`
- [Robust IRC](https://robustirc.net/) - RobustIRC是没有分网的IRC。分布式 IRC 服务器，基于 RobustSession 协议。 ([源码](https://github.com/robustirc/robustirc)) `BSD-3-Clause` `Go`
- [The Lounge](https://thelounge.chat/) - 自我托管的网络IRC客户端。 ([Demo](https://demo.thelounge.chat/), [源码](https://github.com/thelounge/thelounge)) `MIT` `Nodejs`
- [Tiny Tiny IRC](https://tt-rss.org/tt-irc/) - 一个开源的AJAX驱动的聊天平台，支持IRC ([源码](https://git.tt-rss.org/fox/tt-irc)). `GPL-3.0` `PHP/Java`
- [UnrealIRCd](https://www.unrealircd.org/) - 用C语言编写的模块化、高级和高度可配置的IRC服务器，适用于Linux、BSD、Windows和macOS。 ([源码](https://github.com/unrealircd/unrealircd)) `GPL-2.0` `C`
- [Weechat](https://weechat.org/) - 快速、轻便、可扩展的聊天客户端。 `GPL-3.0` `C`
- [ZNC](https://wiki.znc.in/ZNC) - 高级IRC保镖。 ([源码](https://github.com/znc/znc)) `Apache-2.0` `C++`


### 通讯 - SIP

**[`^        返回顶部        ^`](#)**

[SIP](https://en.wikipedia.org/wiki/Session_Initiation_Protocol)/[IPBX](https://en.wikipedia.org/wiki/IP_PBX) telephony software

- [Asterisk](https://www.asterisk.org/) - 易于使用但先进的IP PBX系统、VoIP网关和会议服务器。 `GPL-2.0` `C`
- [ASTPP](https://www.astppbilling.org/) - 是Freeswitch的一个开源VoIP计费解决方案。它支持预付费和后付费计费，具有呼叫评级和信用控制。它还提供许多其他功能。 ([源码](https://github.com/iNextrix/ASTPP)) `AGPL-3.0` `PHP`
- [Freepbx](https://www.freepbx.org) - 基于网络的开源GUI，控制和管理Asterisk。 ([源码](https://git.freepbx.org/projects/FREEPBX)) `GPL-2.0` `PHP`
- [FreeSWITCH](https://freeswitch.org/) - 可扩展的开源跨平台电话平台。 ([源码](https://freeswitch.org/stash/projects/FS/repos/freeswitch/browse)) `MPL-2.0` `C`
- [FusionPBX](https://www.fusionpbx.com/) - 开源项目，为称为FreeSWITCH的非常强大和高度可扩展的多平台语音交换机提供可定制和灵活的网络界面。 ([源码](https://github.com/fusionpbx/fusionpbx)) `MPL-1.1` `PHP`
- [Kamailio](https://www.kamailio.org/w/) - 模块化的SIP服务器（注册商/代理/路由器/等）。 ([源码](https://github.com/kamailio/kamailio)) `GPL-2.0` `C`
- [Kazoo](https://2600hz.org/) - KAZOO 是一个开源的、高度可扩展的软件平台，旨在提供电信级VoIP交换机的功能和特性。 ([源码](https://github.com/2600hz/KAZOO)) `MPL-1.1` `Erlang`
- [Ostel](https://dev.guardianproject.info/projects/ostel/wiki/Server_Documentation) - 使用ZRTP加密的安全SIP电话设置。 `GPL-3.0` `Ruby`
- [Routr](https://routr.io) - 一个轻量级的SIP代理、定位服务器和注册商，用于可靠和可扩展的SIP基础设施。 ([源码](https://github.com/fonoster/routr)) `MIT` `Javascript`
- [SIP3](https://sip3.io/) - VoIP故障排除和监控平台。 ([Demo](https://demo.sip3.io), [源码](https://github.com/sip3io/)) `Apache-2.0` `Kotlin`
- [SIPCAPTURE Homer](https://www.sipcapture.org/) - 排除故障和监测VoIP电话。 ([源码](https://github.com/sipcapture/homer)) `AGPL-3.0` `Angular/C`
- [SipXcom](https://sipxcom.org/) - 开源的统一通信系统。 ([源码](https://github.com/sipXcom/sipxecs)) `AGPL-3.0` `Java`
- [Wazo](https://wazo-platform.org/) - 全功能的IPBX解决方案，建立在Asterisk之上，具有集成的Web管理界面和REST-ful API。 ([源码](https://github.com/wazo-platform)) `GPL-3.0` `Python`
- [Yeti-Switch](https://yeti-switch.org/) - 带有集成计费和路由引擎以及REST API的4级软交换（SBC）。 ([Demo](https://yeti-switch.org/demo.html), [源码](https://github.com/yeti-switch)) `GPL-2.0` `C++/Ruby`


### 通讯 - 社交网络和论坛

**[`^        返回顶部        ^`](#)**

- [Abilian SBE](https://github.com/abilian/abilian-sbe) - 开源协作和社会网络框架和平台。 `LGPL-2.1` `Python`
- [Anahita](https://www.getanahita.com/) - 开源的社会网络框架和平台。 ([源码](https://github.com/anahitasocial)) `GPL-3.0` `PHP`
- [AsmBB](https://board.asm32.info) - 一个用 ASM 编写的快速的、由 SQLite 驱动的论坛引擎。 ([源码](https://asm32.info/fossil/asmbb/index)) `EUPL-1.2` `Assembly`
- [bbPress](https://bbpress.org/) - bbPress 是由 WordPress 的创建者开发的具有特色的论坛软件。在你的 WordPress.org 驱动的网站内轻松地设置讨论区。 ([源码](https://bbpress.trac.wordpress.org/browser/trunk)) `GPL-2.0` `PHP`
- [Bibliogram](https://bibliogram.art) `⚠` - Instagram的一个替代性前端。 ([源码](https://sr.ht/~cadence/bibliogram/)) `AGPL-3.0` `Nodejs`
- [Bootcamp](https://trybootcamp.vitorfs.com) - 企业社交网络。 ([源码](https://github.com/vitorfs/bootcamp)) `MIT` `Python`
- [Buddycloud](http://buddycloud.com/) - 工具、库、服务和社区，在你的应用中建立用户对用户、群组和社交信息。节省时间。扩大规模。支持你。 ([源码](https://github.com/buddycloud)) `Apache-2.0` `Java`
- [BuddyPress](https://buddypress.org/about/) - 强大的插件，使你的WordPress.org驱动的网站超越了博客，具有社交网络功能，如用户档案、活动流、用户组等。 ([源码](https://github.com/buddypress/BuddyPress)) `GPL-2.0` `PHP`
- [Cactus Comments](https://cactus.chat/) - Cactus Comments是一个建立在Matrix上的开放网络的联合评论系统。 ([Demo](https://cactus.chat/demo/), [源码](https://gitlab.com/cactus-comments/)) `GPL-3.0` `Python`
- [cartulary](https://github.com/daveajones/cartulary) - RSS阅读器、可读性工具、文章存档器、微博、社交图谱管理器和阅读列表管理器。 `CDDL-1.0` `PHP`
- [Commento](https://gitlab.com/commento/commento) - Commento是一个讨论平台，你可以将其嵌入你的博客、新闻文章和任何你希望读者添加评论的地方。 `MIT` `Go`
- [schnack](https://github.com/schn4ck/schnack) - Schnack是一个简单的自我托管的Node应用程序，用于在静态网站上进行类似Discuz的评论。 `Lil licence v1` `Node.js`
- [Coral](https://coralproject.net/) - Vox Media提供了更好的评论体验。 ([源码](https://github.com/coralproject/talk)) `Apache-2.0` `Nodejs`
- [diaspora*](https://diasporafoundation.org/) - 分布式社交网络服务器。 ([Demo](https://podupti.me/go.php), [源码](https://github.com/diaspora/diaspora)) `AGPL-3.0` `Ruby`
- [Discourse](https://www.discourse.org/) - 基于Ruby和JS的高级论坛/社区解决方案。 ([Demo](https://try.discourse.org/), [源码](https://github.com/discourse/discourse)) `GPL-2.0` `Ruby`
- [dyu comments](https://github.com/dyu/comments) - 由leveldb提供的实时的、支持markdown的评论引擎。 ([Demo](https://dyu.github.io/comments/real-time/)) `Apache-2.0` `Java`
- [Elgg](https://elgg.org/) - 强大的开源社交网络引擎。 ([源码](https://github.com/Elgg/Elgg)) `GPL-2.0` `PHP`
- [EpochTalk](https://github.com/epochtalk/epochtalk) - 下一代论坛软件。 `MIT` `Nodejs`
- [Flarum](https://flarum.org) - 令人愉悦的简单论坛。Flarum是新一代的论坛软件，使在线讨论再次变得有趣。 ([源码](https://github.com/flarum/flarum)) `MIT` `PHP`
- [FlaskBB](https://flaskbb.org/) - FlaskBB是用Python编写的论坛软件，使用微框架Flask。你可以轻松地创建新的主题、帖子和向其他用户发送私人信息。它还包括基本的管理和修改工具。 ([源码](https://github.com/flaskbb/flaskbb)) `BSD-3-Clause` `Python`
- [FluxBB](https://fluxbb.org/) - 为您的网站提供快速、轻便、用户友好的论坛软件。 ([源码](https://github.com/fluxbb/fluxbb)) `GPL-2.0` `PHP`
- [Friendica](https://friendi.ca/) - 社会通讯服务器。 ([源码](https://github.com/friendica/friendica)) `AGPL-3.0` `PHP`
- [Glosa](https://github.com/glosa/glosa-server) - 开源的评论系统，易于与静态页面整合。可以从Disqus导入。 `GPL-3.0` `Java`
- [GNU social](https://gnu.io/social/) - 用于公共和私人通信的社会通信软件。 ([源码](https://notabug.org/diogo/gnu-social)) `AGPL-3.0` `PHP`
- [Gosora](https://gosora-project.com/) - Gosora是一个用Go语言编写的超快速和安全的论坛软件，它兼顾了可用性和功能性。 ([源码](https://github.com/Azareal/Gosora)) `GPL-3.0` `Go`
- [Hubzilla](https://hubzilla.org) - 去中心化的身份、隐私、发布、共享、云存储和通信/社交平台。 ([源码](https://framagit.org/hubzilla/core)) `MIT` `PHP`
- [HumHub](https://www.humhub.org/) - 用于私人社交网络的灵活套件。 ([源码](https://github.com/humhub/humhub)) `AGPL-3.0` `PHP`
- [Isso](https://posativ.org/isso/) - 用Python和Javascript编写的轻量级评论服务器。它的目标是成为Disqus的直接替代品。 ([源码](https://github.com/posativ/isso)) `MIT` `Python`
- [Lemmy](https://join-lemmy.org/) - 一个用于aggregator的链接聚合器/Reddit克隆。在Rust中建立的Reddit替代品。 ([源码](https://github.com/LemmyNet/lemmy)) `AGPL-3.0` `Rust`
- [Libreddit](https://libredd.it/) `⚠` - 用Rust编写的Reddit的私人前端。 ([源码](https://github.com/spikecodes/libreddit)) `AGPL-3.0` `Rust`
- [Loomio](https://www.loomio.org/) - Loomio 是一个协作式决策工具，使任何人都能轻松参与影响他们的决策。 ([源码](https://github.com/loomio/loomio)) `AGPL-3.0` `Ruby`
- [Mastodon](https://joinmastodon.org/) - 联盟式微博服务器，是GNU social的替代方案。 ([源码](https://github.com/tootsuite/mastodon)) `AGPL-3.0` `Ruby`
- [Misago](https://misago-project.org/) - Misago 是功能齐全的现代论坛应用程序，具有快速、可扩展和响应性。 ([源码](https://github.com/rafalp/Misago)) `GPL-2.0` `Python`
- [Misskey](https://misskey.io/) - 为 Fediverse 提供的类似于应用程序的分散式微博服务器/SNS，使用GNU social和Mastodon等ActivityPub协议。 ([源码](https://github.com/misskey-dev/misskey)) `AGPL-3.0` `Nodejs`
- [Movim](https://movim.eu/) - 现代的、基于XMPP的联合社交网络，具有功能齐全的群聊、订阅和微博。 ([源码](https://github.com/movim/movim)) `AGPL-3.0` `PHP`
- [MyBB](https://mybb.com/) - 免费的、可扩展的论坛软件包。 ([源码](https://github.com/mybb/mybb)) `LGPL-3.0` `PHP`
- [Nitter](https://nitter.net) `⚠` - 一个替代twitter的前端。 ([源码](https://github.com/zedeus/nitter)) `AGPL-3.0` `Nimble`
- [NodeBB](https://nodebb.org/) - 为现代网络建立的论坛软件。 ([源码](https://github.com/NodeBB/NodeBB)) `GPL-3.0` `Nodejs`
- [Orange Forum](https://www.goodoldweb.com/) - 橙色论坛是一个易于部署的论坛，它具有最小的依赖性，并使用很少的JavaScript。 ([源码](https://github.com/s-gv/orangeforum)) `BSD-3-Clause` `Go`
- [OSSN](https://www.opensource-socialnetwork.org/) - 开源社交网络（OSSN）是一个用PHP编写的社会网络软件。它允许你做一个社交网站，并帮助你的成员建立社会关系，与那些有类似职业或个人兴趣的人。 ([源码](https://github.com/opensource-socialnetwork/opensource-socialnetwork)) `GPL-2.0` `PHP`
- [phpBB](https://www.phpbb.com/) - 扁平论坛的公告板软件解决方案，可以用来与一群人保持联系，也可以为你的整个网站提供动力。 ([源码](https://github.com/phpbb/phpbb)) `GPL-2.0` `PHP`
- [PixelFed](https://pixelfed.social) - Pixelfed是一个开源的、替代Instagram的联合平台。 ([源码](https://github.com/pixelfed/pixelfed)) `AGPL-3.0` `PHP`
- [Pleroma](https://pleroma.social) - 联合微博服务器，兼容Mastodon、GNU social和ActivityPub。 ([源码](https://git.pleroma.social/pleroma/pleroma)) `AGPL-3.0` `Elixir`
- [Pump.io](http://pump.io/) - 流媒体服务器，做了人们真正想从社交网络中得到的大部分东西。 ([源码](https://github.com/pump-io/pump.io)) `Apache-2.0` `Nodejs`
- [remark42](https://remark42.com/) - 流媒体服务器，做了人们真正想从社交网络中得到的大部分东西。 ([Demo](https://remark42.com/demo/), [源码](https://github.com/umputun/remark42)) `MIT` `Go`
- [rss2twtxt](https://github.com/jointwt/rss2twtxt) - 一个RSS/Atom feed聚合器的命令行工具和网络服务，消耗RSS/Atom并产生twtxt.net feeds供twtxt客户端使用。 ([Demo](https://feeds.twtxt.net)) `MIT` `Go`
- [Satellity](https://satellity.org/) - 然而，另一个用Golang、React和PostgreSQL编写的开源论坛。 ([源码](https://github.com/satellity/satellity)) `MIT` `Go`
- [Scoold](https://scoold.com) - JAR中的Stack Overflow。一个企业就绪的问答平台，具有全文搜索、SAML、LDAP集成和社交登录支持。 ([Demo](https://live.scoold.com), [源码](https://github.com/Erudika/scoold)) `Apache-2.0` `Java`
- [Simple Machines Forum](https://www.simplemachines.org/) - 免费的专业级软件包，允许你在几分钟内建立你自己的在线社区。 ([源码](https://github.com/SimpleMachines/SMF2.1)) `BSD-3-Clause` `PHP`
- [Socialhome](https://socialhome.network) - 联合和分散的个人资料建立者和社交网络引擎。 ([Demo](https://socialhome.network/), [源码](https://github.com/jaywink/socialhome)) `AGPL-3.0` `Python`
- [Talkyard](https://www.talkyard.io/) - 创建一个社区，你的用户可以在这里提出想法并得到问题的解答。并进行友好的开放式讨论和聊天（Slack/StackOverflow/Discourse/Reddit/Disqus混合）。 ([Demo](https://www.talkyard.io/forum/latest), [源码](https://github.com/debiki/talkyard)) `AGPL-3.0` `Scala`
- [Teddit](https://teddit.net) `⚠` - 注重隐私的替代性Reddit前端。 ([源码](https://codeberg.org/teddit/teddit)) `AGPL-3.0` `Nodejs`
- [Thredded](https://github.com/thredded/thredded) - 论坛，功能丰富且简单。 `MIT` `Ruby`
- [Tokumei](https://tokumei.co/) - 匿名的微博客平台。 ([源码](https://gitlab.com/tokumei/tokumei)) `ISC` `rc`
- [twister](http://twister.net.co/) - 完全去中心化的P2P微博平台，利用比特币和BitTorrent协议的自由软件实现。 ([源码](https://github.com/miguelfreitas/twister-core)) `MIT` `C++`
- [twtxt.net](https://twtxt.net) - 一个自我托管的、类似于Twitter™的分散式微日志平台。没有广告，没有跟踪，你的内容，你的数据。 ([源码](https://git.mills.io/yarnsocial/yarn)) `MIT` `Go`
- [Vanilla Forums](https://vanillaforums.org/) - 简单而灵活的论坛软件。 ([源码](https://github.com/vanilla/vanilla)) `GPL-2.0` `PHP`
- [Zusam](https://zusam.org) - 免费和开源的方式，为朋友或家人的团体自我主持私人论坛。 ([Demo](https://demo.zusam.org), [源码](https://github.com/zusam/zusam)) `AGPL-3.0` `PHP`


### Communication - XMPP

**[`^        返回顶部        ^`](#)**

[可扩展消息和存在协议](https://en.wikipedia.org/wiki/XMPP) software


### Communication - XMPP - Servers

**[`^        返回顶部        ^`](#)**

- [ejabberd](https://www.ejabberd.im/) - XMPP instant messaging server. ([源码](https://github.com/processone/ejabberd)) `GPL-2.0` `Erlang`
- [jackal](https://github.com/ortuman/jackal) - XMPP server with focus on stability, simple configuration and low resource consumption. `Apache-2.0` `Go`
- [Kontalk](https://www.kontalk.org) - Kontalk is an Open Source Messenger, similar to WhatsApp (app for android only currently), including end-to-end encryption, server is based on Tigase XMPP Server. ([源码](https://github.com/kontalk)) `GPL-3.0` `Java`
- [Metronome IM](https://metronome.im/) - Fork of Prosody IM. ([源码](https://github.com/maranda/metronome)) `MIT` `Lua`
- [MongooseIM](https://www.erlang-solutions.com/products/mongooseim.html) - Mobile messaging platform with a focus on performance and scalability. ([源码](https://github.com/esl/MongooseIM)) `GPL-2.0` `Erlang`
- [Openfire](https://www.igniterealtime.org/projects/openfire/) - Real time collaboration (RTC) server. ([源码](https://github.com/igniterealtime/Openfire)) `Apache-2.0` `Java`
- [Prosody IM](https://prosody.im/) - Feature-rich and easy to configure XMPP server. ([源码](https://hg.prosody.im/)) `MIT` `Lua`
- [Snikket](https://snikket.org/) - All-in-one Dockerized easy XMPP solution, including web admin and clients. ([源码](https://github.com/snikket-im/snikket-server), [Clients](https://snikket.org/app/)) `Apache-2.0` `Lua/Python`
- [Tigase](https://tigase.net/xmpp-server) - XMPP server implementation in Java. `GPL-3.0` `Java`


### Communication - XMPP - Web Clients

**[`^        返回顶部        ^`](#)**

- [Candy](https://candy-chat.github.io/candy/) - Multi user XMPP client written in Javascript. ([源码](https://github.com/candy-chat/candy)) `MIT` `Javascript`
- [Converse.js](https://conversejs.org/) - Free and open-source XMPP chat client in your browser. ([源码](https://github.com/conversejs/converse.js)) `MPL-2.0` `Javascript`
- [JSXC](https://jsxc.org) - Real-time XMPP web chat application with video calls, file transfer and encrypted communication. There are also versions for Nextcloud/Owncloud and SOGo. ([源码](https://github.com/jsxc/jsxc)) `MIT` `Javascript`
- [Libervia](https://wiki.goffi.org/wiki/Libervia/en) - Web frontend from Salut à Toi. ([源码](https://repos.goffi.org/libervia-web)) `AGPL-3.0` `Python`
- [Salut à Toi](https://www.salut-a-toi.org/) - Multipurpose, multi frontend, libre and decentralized communication tool. ([源码](https://repos.goffi.org/libervia-backend)) `AGPL-3.0` `Python`


### Community-Supported Agriculture (CSA)

**[`^        返回顶部        ^`](#)**

Management and administration tools for community supported agriculture and food cooperatives

_关联: [E-commerce](#e-commerce)_

- [ACP Admin](https://acp-admin.ch/) - CSA administration. Manage members, subscriptions, deliveries, drop-off locations, member participation, invoices and emails. ([源码](https://github.com/acp-admin/acp-admin/)) `MIT` `Ruby`
- [Cagette](https://cagette.net/) - Open source web app to help people build a better and sustainable food system. Some people call it a 'foodhub' - a mix between a groupware and a marketplace, helping consumers to order food from local farmers and producers. ([源码](https://github.com/CagetteNet/cagette)) `GPL-2.0` `Haxe`
- [FoodCoopShop](https://www.foodcoopshop.com/) - User-friendly open source software for food-coops. ([源码](https://github.com/foodcoopshop/foodcoopshop)) `MIT` `PHP`
- [Foodsoft](https://foodcoops.net/) - Web-based software to manage a non-profit food coop (product catalog, ordering, accounting, job scheduling). ([源码](https://github.com/foodcoops/foodsoft)) `AGPL-3.0` `Ruby`
- [juntagrico](https://juntagrico.org/) - Management platform for community gardens and vegetable cooperatives. ([源码](https://github.com/juntagrico/juntagrico)) `LGPL-3.0` `Python`
- [Local Food Nodes](https://localfoodnodes.org/) - Your open source platform for peoples driven local food markets and CSA. ([源码](https://gitlab.com/localfoodnodes/localfoodnodes)) `MIT` `PHP`
- [Open Food Network](https://www.openfoodnetwork.org/) - Online marketplace for local food. It enables a network of independent online food stores that connect farmers and food hubs with individuals and local businesses. ([源码](https://github.com/openfoodfoundation/openfoodnetwork)) `AGPL-3.0` `Ruby`
- [OpenOlitor](https://openolitor.org/) - Administration platform for Community Supported Agriculture groups. ([源码](https://github.com/OpenOlitor)) `AGPL-3.0` `Scala`
- [teikei](https://github.com/teikei/teikei) - A web application that maps out community-supported agriculture based on crowdsourced data. ([Demo](https://ernte-teilen.org/karte/#/)) `AGPL-3.0` `Nodejs`


### Conference Management

**[`^        返回顶部        ^`](#)**

- [BigBlueButton](https://bigbluebutton.org/) - Supports real-time sharing of audio, video, slides (with whiteboard controls), chat, and the screen. Instructors can engage remote students with polling, emojis, and breakout rooms. ([Demo](https://demo.bigbluebutton.org/gl), [源码](https://github.com/bigbluebutton/bigbluebutton)) `LGPL-3.0` `Java`
- [Conference Organizing Distribution (COD)](http://usecod.com/) - Create conference and event websites built on top of Drupal. ([源码](https://git.drupalcode.org/project/cod)) `GPL-1.0` `PHP`
- [frab](https://frab.github.io/frab/) - web-based conference planning and management system. It helps to collect submissions, to manage talks and speakers and to create a schedule. ([源码](https://github.com/frab/frab)) `MIT` `Ruby`
- [indico](https://getindico.io/) - A feature-rich event management system, made @ CERN, the place where the Web was born. ([Demo](https://sandbox.getindico.io/), [源码](https://github.com/indico/indico)) `MIT` `Python`
- [Open Conference Systems (OCS)](https://pkp.sfu.ca/ocs/) - is a free Web publishing tool that will create a complete Web presence for your scholarly conference. ([Demo](https://pkp.sfu.ca/ocs/ocs_demo/), [源码](https://github.com/pkp/ocs)) `GPL-1.0` `PHP`
- [OpenCFP](https://github.com/opencfp/opencfp) - OpenCFP is a PHP-based conference talk submission system. `MIT` `PHP`
- [osem](https://osem.io/) - Event management tailored to free Software conferences. ([Demo](https://demo.osem.io/), [源码](https://github.com/openSUSE/osem)) `MIT` `Ruby`
- [pretalx](https://pretalx.org) - Web-based event management, including running a Call for Papers, reviewing submissions, and scheduling talks. Exports and imports for various related tools. ([源码](https://github.com/pretalx/pretalx)) `Apache-2.0` `Python`


### Content Management Systems (CMS)

**[`^        返回顶部        ^`](#)**

CMS are a practical way to setup a website with many features. CMS often come with third party plugins, themes and functionality that is easy to add and customize to your needs.

_关联: [Blogging Platforms](#blogging-platforms), [Static Site Generators](#static-site-generators)_

- [Alfresco Community Edition](https://www.alfresco.com/products/community/download) - The open source Enterprise Content Management software that handles any type of content, allowing users to easily share and collaborate on content. ([源码](https://hub.alfresco.com/t5/alfresco-content-services-hub/project-overview-repository/ba-p/290502)) `LGPL-3.0` `Java`
- [Apostrophe](https://apostrophecms.org/) - CMS with a focus on extensible in-context editing tools. ([Demo](https://dashboard.apostrophecmsdemo.org), [源码](https://github.com/apostrophecms/apostrophe)) `MIT` `Nodejs`
- [b2evolution CMS](https://b2evolution.net/) - The most integrated CMS ever: b2evolution includes everything you need to build websites for publishing, sharing and interacting with your community. ([源码](https://github.com/b2evolution/b2evolution)) `GPL-2.0` `PHP`
- [Backdrop CMS](https://backdropcms.org/) - Comprehensive CMS for small to medium sized businesses and non-profits. ([源码](https://github.com/backdrop/backdrop)) `GPL-2.0` `PHP`
- [BigTree CMS](https://www.bigtreecms.org/) - Straightforward, well documented, and capable written with PHP and MySQL. ([源码](https://github.com/bigtreecms/BigTree-CMS)) `LGPL-2.1` `PHP`
- [Bolt CMS](https://bolt.cm/) - Open source Content Management Tool, which strives to be as simple and straightforward as possible. ([Demo](https://try.bolt.cm/), [源码](https://github.com/bolt/bolt)) `MIT` `PHP`
- [CMS Made Simple](https://www.cmsmadesimple.org/) - Open source content management system, faster and easier management of website contents, scalable for small businesses to large corporations. ([源码](http://svn.cmsmadesimple.org/svn/cmsmadesimple/trunk/)) `GPL-1.0` `PHP`
- [Cockpit](https://getcockpit.com) - Simple Content Platform to manage any structured content. ([源码](https://github.com/agentejo/cockpit)) `MIT` `PHP`
- [Concrete 5 CMS](https://www.concretecms.com) - Open source content management system. ([源码](https://github.com/concrete5/concrete5)) `MIT` `PHP`
- [Contao](https://contao.org/) - Contao is a powerful open source CMS that allows you to create professional websites and scalable web applications. ([源码](https://github.com/contao/contao/)) `LGPL-3.0` `PHP`
- [CouchCMS](https://www.couchcms.com/) - Simple Open-Source CMS for designers. ([源码](https://github.com/CouchCMS/CouchCMS)) `CPAL-1.0` `PHP`
- [Directus](https://directus.io/) - An Instant App & API for your SQL Database. Directus wraps your new or existing SQL database with a realtime GraphQL+REST API for developers, and an intuitive admin app for non-technical users. ([源码](https://github.com/directus/directus)) `GPL-3.0` `Nodejs`
- [Drupal](https://www.drupal.org/) - Advanced open source content management platform. ([源码](https://git.drupalcode.org/project/drupal)) `GPL-2.0` `PHP`
- [eLabFTW](https://www.elabftw.net) - Online lab notebook for research labs. Store experiments, use a database to find reagents or protocols, use trusted timestamping to legally timestamp an experiment, export as pdf or zip archive, share with collaborators…. ([Demo](https://demo.elabftw.net), [源码](https://github.com/elabftw/elabftw)) `AGPL-3.0` `PHP`
- [Expressa](https://github.com/thomas4019/expressa) - Content Management System for powering database driven websites using JSON schemas. Provides permission management and automatic REST APIs. `MIT` `Nodejs`
- [Flextype](https://flextype.org/) - Flextype is an open-source Hybrid Content Management System with the freedom of a headless CMS and with the full functionality of a traditional CMS. ([Demo](https://demo.flextype.org/), [源码](https://github.com/flextype/flextype)) `MIT` `PHP`
- [GetSimple CMS](http://get-simple.info/) - The Simplest Content Management System. Ever. ([源码](https://github.com/GetSimpleCMS/GetSimpleCMS)) `GPL-3.0` `PHP`
- [Joomla!](https://www.joomla.org/) - Advanced Content Management System (CMS). ([源码](https://github.com/joomla/joomla-cms)) `GPL-2.0` `PHP`
- [KeystoneJS](https://keystonejs.com/) - CMS and Web Application Platform. ([Demo](https://demo.keystonejs.com/), [源码](https://github.com/keystonejs/keystone)) `MIT` `Nodejs`
- [MODX](https://modx.com/) - MODX is an advanced content management and publishing platform. The current version is called 'Revolution'. ([源码](https://github.com/modxcms/revolution)) `GPL-2.0` `PHP`
- [Neos](https://www.neos.io) - Neos or TYPO3 Neos (for version 1) is a modern, open source CMS. ([源码](https://git.typo3.org/Packages/TYPO3.Neos.git)) `GPL-3.0` `PHP`
- [Noosfero](https://gitlab.com/noosfero/noosfero) - Noosfero is a web platform for social and solidarity economy networks with blog, e-Portfolios, CMS, RSS, thematic discussion, events agenda and collective intelligence for solidarity economy in the same system. `AGPL-3.0` `Ruby`
- [october](https://octobercms.com/) - Free, open-source, self-hosted CMS platform. ([源码](https://github.com/octobercms/october)) `MIT` `PHP`
- [Omeka](https://omeka.org) - Create complex narratives and share rich collections, adhering to Dublin Core standards with Omeka on your server, designed for scholars, museums, libraries, archives, and enthusiasts. ([Demo](https://omeka.org/classic/showcase/), [源码](https://github.com/omeka/Omeka)) `GPL-3.0` `PHP`
- [Pagekit](https://pagekit.com/) - New modern CMS to create and share. ([源码](https://github.com/pagekit/pagekit)) `MIT` `PHP`
- [Pico](https://picocms.org/) - Stupidly simple, blazing fast, flat file CMS. ([源码](https://github.com/picocms/Pico)) `MIT` `PHP`
- [Pimcore](https://www.pimcore.org/) - Multi-Channel Experience and Engagement Management Platform. ([源码](https://github.com/pimcore/pimcore)) `GPL-3.0-or-later` `PHP`
- [Plone](https://plone.org/) - Powerful open-source CMS system. ([源码](https://github.com/plone)) `ZPL-2.0` `Python`
- [ProcessWire](https://processwire.com/) - ProcessWire is an open source content management system (CMS) and web application framework aimed at the needs of designers, developers and their clients. ([源码](https://github.com/ryancramerdesign/ProcessWire)) `MPL-2.0` `PHP`
- [PropertyWebBuilder](https://propertywebbuilder.com) - Ultimate Ruby on Rails engine for creating real estate websites. ([Demo](https://propertywebbuilder.herokuapp.com), [源码](https://github.com/etewiah/property_web_builder)) `MIT` `Ruby`
- [Publify](https://publify.github.io/) - Simple but full featured web publishing software. ([源码](https://github.com/publify/publify)) `MIT` `Ruby`
- [REDAXO](https://www.redaxo.org) - Simple, flexible and useful content management system (documentation only available in German). ([源码](https://github.com/redaxo/redaxo)) `MIT` `PHP`
- [Redaxscript](https://redaxscript.com) - Ultra lightweight CMS for MySQL, SQLite and PostgreSQL. ([Demo](https://demo.redaxscript.com/login), [源码](https://github.com/redaxscript/redaxscript)) `GPL-3.0` `PHP`
- [Roadiz](https://www.roadiz.io/) -  Modern CMS based on a node system which can handle many types of services. ([源码](https://github.com/roadiz/roadiz)) `MIT` `PHP`
- [SilverStripe](https://www.silverstripe.org) - Easy to use CMS with powerful MVC framework underlying. ([Demo](https://demo.silverstripe.org/), [源码](https://github.com/silverstripe)) `BSD-3-Clause` `PHP`
- [SPIP](https://www.spip.net/fr) - Publication system for the Internet aimed at collaborative work, multilingual environments, and simplicity of use for web authors. ([源码](https://git.spip.net/)) `GPL-3.0` `PHP`
- [Squidex](https://squidex.io) - Headless CMS, based on MongoDB, CQRS and Event Sourcing. ([Demo](https://cloud.squidex.io), [源码](https://github.com/Squidex/squidex)) `MIT` `.NET`
- [Strapi](https://strapi.io/) - The most advanced open-source Content Management Framework (headless-CMS) to build powerful API with no effort. ([源码](https://github.com/strapi/strapi)) `MIT` `Nodejs`
- [Textpattern](https://textpattern.com/) - Flexible, elegant and easy-to-use CMS. ([Demo](https://textpattern.co/demo), [源码](https://github.com/textpattern/textpattern)) `GPL-2.0` `PHP`
- [Typemill](https://typemill.net/) - Author-friendly flat-file-cms with a visual markdown editor based on vue.js. ([源码](https://github.com/typemill/typemill)) `MIT` `PHP`
- [TYPO3](https://typo3.org/) - Powerful and advanced CMS with a large community. ([源码](https://github.com/TYPO3/TYPO3.CMS)) `GPL-2.0` `PHP`
- [Umbraco](https://umbraco.com/) - The friendly CMS. Free and open source with an amazing community. ([源码](https://github.com/umbraco/Umbraco-CMS)) `MIT` `.NET`
- [Wagtail](https://wagtail.io/) - Django content management system focused on flexibility and user experience. ([源码](https://github.com/wagtail/wagtail)) `BSD-3-Clause` `Python`
- [WonderCMS](https://www.wondercms.com) - WonderCMS is the smallest flat file CMS since 2008. ([Demo](https://www.wondercms.com/demo), [源码](https://github.com/robiso/wondercms)) `MIT` `PHP`
- [WordPress](https://wordpress.org/) - World's most-used blogging and CMS engine. ([源码](https://github.com/WordPress/WordPress)) `GPL-2.0` `PHP`
- [WriteFreely](https://writefreely.org) - Writing software for starting a minimalist, federated blog — or an entire community. ([源码](https://github.com/writefreely/writefreely)) `AGPL-3.0` `Go`


### DNS

**[`^        返回顶部        ^`](#)**

_See also: [awesome-sysadmin/DNS](https://github.com/awesome-foss/awesome-sysadmin#dns)_

- [blocky](https://github.com/0xERR0R/blocky) - Fast and lightweight DNS proxy (like Pi-hole) as ad-blocker for local network with many features. `Apache-2.0` `Go`
- [CoreDNS](https://coredns.io/) - Plugin driven DNS Server with support for proxying to Google's DNS-over-HTTPS. ([源码](https://github.com/coredns/coredns)) `Apache-2.0` `Go`
- [Maza ad blocking](https://maza-ad-blocking.andros.dev/) - Local ad blocker. Like Pi-hole but local and using your operating system. ([源码](https://github.com/tanrax/maza-ad-blocking)) `Apache-2.0` `Bash`
- [nsupdate.info](https://www.nsupdate.info/) - nsupdate.info is a dynamic DNS service. ([Demo](https://www.nsupdate.info/account/register/), [源码](https://github.com/nsupdate-info/nsupdate.info)) `BSD-3-Clause` `Python`
- [SPF Toolbox](https://spftoolbox.com) - Application to look up DNS records such as SPF, MX, Whois, and more. ([源码](https://github.com/charlesabarnes/SPFtoolbox)) `MIT` `PHP`


### 文档管理

**[`^        返回顶部        ^`](#)**

- [DOCAT](https://github.com/randombenj/docat) - Host your docs. Simple. Versioned. Fancy. `MIT` `Python/Docker`
- [Docspell](https://docspell.org) - Auto-tagging document organizer and archive. ([源码](https://github.com/eikek/docspell)) `GPL-3.0` `Scala/Java`
- [EveryDocs](https://github.com/jonashellmann/everydocs-core/) - A simple Document Management System for private use with basic functionality to organize your documents digitally. `GPL-3.0` `Ruby`
- [I, Librarian](https://i-librarian.net) - I, Librarian can organize PDF papers and office documents. It provides a lot of extra features for students and research groups both in industry and academia. ([Demo](https://i-librarian.net/demo/), [源码](https://github.com/mkucej/i-librarian-free)) `GPL-3.0` `PHP`
- [Mayan EDMS](https://www.mayan-edms.com) - Free Open Source Electronic Document Management System. An electronic vault for your documents with preview generation, OCR, and automatic categorization among other features. ([源码](https://gitlab.com/mayan-edms/mayan-edms)) `Apache-2.0` `Python`
- [Paperless-ng](https://github.com/jonaswinkler/paperless-ng) - A fork of paperless, adding a new interface and many other changes under the hood. Scan, index, and archive all of your paper documents. `GPL-3.0` `Python`
- [Papermerge](https://www.papermerge.com) - Open Source Document Management System focused on scanned documents (electronic archives). Features file browsing in similar way to dropbox/google drive. OCR, full text search, text overlay/selection. ([源码](https://github.com/ciur/papermerge)) `Apache-2.0` `Python`
- [paper{s}pace](https://dedicatedcode.com/projects/) - a small web application to manage all your offline documents. Provides a searchable storage for your documents and reminds you of upcoming tasks. ([源码](https://gitlab.com/dedicatedcode/paperspace)) `MIT` `Java`
- [Teedy](https://teedy.io/) - (Ex SismicsDocs) Lightweight document management system packed with all the features you can expect from big expensive solutions. ([源码](https://github.com/sismics/docs)) `GPL-2.0` `Java`


### 文档管理 - E-books

**[`^        返回顶部        ^`](#)**

- [BicBucStriim](https://projekte.textmulch.de/bicbucstriim/) - Provides web-based access to your Calibre Library's e-book collection. ([源码](https://github.com/rvolz/BicBucStriim)) `MIT` `PHP`
- [Calibre Web](https://github.com/janeczku/calibre-web) - Web app providing a clean interface for browsing, reading and downloading eBooks using an existing Calibre database. `GPL-3.0` `Python`
- [Calibre](https://calibre-ebook.com/) - E-book library manager that can view, convert, and catalog e-books in most of the major e-book formats and provides a built-in Web server for remote clients. ([Demo](https://calibre-ebook.com/demo), [源码](https://launchpad.net/calibre)) `GPL-3.0` `Python`
- [COPS](https://blog.slucas.fr/en/oss/calibre-opds-php-server) - Lightweight e-book server alternative to Calibre content server or Calibre2OPDS. ([Demo](http://cops-demo.slucas.fr/index.php), [源码](https://github.com/seblucas/cops)) `GPL-2.0` `PHP`
- [Kavita](https://www.kavitareader.com/) - Cross-platform e-book/manga/comic/pdf server and web reader with user management, ratings and reviews, and metatdata support. ([Demo](https://wiki.kavitareader.com/en/kavita-demo), [源码](https://github.com/Kareadita/Kavita)) `GPL-3.0` `.NET Core/Docker`
- [Komga](https://komga.org) - Media server for comics/mangas/BDs with API and OPDS support, a modern web interface for exploring your libraries, as well as a web reader. ([源码](https://github.com/gotson/komga)) `MIT` `Java/Docker`
- [Mango](https://github.com/hkalexling/Mango) - Manga server and web reader with a built-in MangaDex downloader. `MIT` `Crystal`
- [pyShelf](https://github.com/th3r00t/pyShelf) - Lightweight Ebook Server. `GPL-3.0` `Python`
- [Tanoshi](https://github.com/faldez/tanoshi) - Selfhosted web manga reader with extensions. `MIT` `Rust`
- [The Epube](https://tt-rss.org/the-epube) - Self-hosted web EPUB reader using EPUB.js, Bootstrap, and Calibre. ([源码](https://git.tt-rss.org/fox/the-epube)) `GPL-3.0` `PHP`


### 文档管理 - Institutional Repository and Digital Library Software

**[`^        返回顶部        ^`](#)**

- [DSpace](https://duraspace.org/dspace/) - Turnkey repository application providing durable access to digital resources. ([源码](https://github.com/DSpace/DSpace)) `BSD-3-Clause` `Java`
- [EPrints](https://www.eprints.org/) - Digital document management system with a flexible metadata and workflow model primarily aimed at academic institutions. ([Demo](http://tryme.demo.eprints-hosting.org/), [源码](https://github.com/eprints/eprints)) `GPL-3.0` `Perl`
- [Fedora Commons Repository](https://fedorarepository.org/) - Robust and modular repository system for the management and dissemination of digital content especially suited for digital libraries and archives, both for access and preservation. ([源码](https://github.com/fcrepo/fcrepo)) `Apache-2.0` `Java`
- [Islandora](https://islandora.ca/) - Drupal module for browsing and managing Fedora-based digital repositories. ([源码](https://github.com/Islandora/islandora)) `GPL-3.0` `PHP`
- [Samvera Hyrax](https://samvera.org/) - Front-end for the Samvera framework, which itself is a Ruby on Rails application for browsing and managing Fedora-based digital repositories. ([源码](https://github.com/samvera/hyrax)) `Apache-2.0` `Ruby`


### Document Management - Integrated Library Systems (ILS)

**[`^        返回顶部        ^`](#)**

_关联: [Content Management Systems (CMS)](#content-management-systems-cms), [Archiving and Digital Preservation (DP)](#archiving-and-digital-preservation-dp)_

- [Evergreen](https://evergreen-ils.org) - Highly-scalable software for libraries that helps library patrons find library materials, and helps libraries manage, catalog, and circulate those materials. ([源码](https://github.com/evergreen-library-system/Evergreen)) `GPL-2.0` `PL/pgSQL`
- [Koha](https://koha-community.org/) - Enterprise-class ILS with modules for acquisitions, circulation, cataloging, label printing, offline circulation for when Internet access is not available, and much more. ([Demo](https://koha-community.org/demo/), [源码](https://github.com/Koha-Community/Koha)) `GPL-3.0` `Perl`
- [RERO ILS](https://rero21.ch/) - Large-scale ILS that can be run as a service with consortial features, intended primarily for library networks. Includes most standard modules (circulation, acquisitions, cataloging,...) and a web-based public and professional interface. ([Demo](https://ils.test.rero.ch/), [源码](https://github.com/rero/rero-ils)) `AGPL-3.0` `Python/Other`


### E-commerce

**[`^        返回顶部        ^`](#)**

_关联: [Community-Supported Agriculture (CSA)](#community-supported-agriculture-csa)_

- [Aimeos](https://aimeos.org/) - Ultra fast, Open Source e-commerce framework for building custom online shops, market places and complex B2B applications scaling to billions of items with Laravel. ([Demo](https://demo.aimeos.org/), [源码](https://github.com/aimeos)) `LGPL-3.0/MIT` `PHP`
- [Attendize](https://www.attendize.com/) - Ticket selling and event management platform. ([源码](https://github.com/attendize/attendize)) `AAL` `PHP`
- [Bagisto](https://bagisto.com/en/) - Leading Laravel open source e-commerce framework with multi-inventory sources, taxation, localization, dropshipping and more exciting features. ([Demo](https://demo.bagisto.com/), [源码](https://github.com/bagisto/bagisto)) `MIT` `PHP`
- [CoreShop](https://www.coreshop.org) - CoreShop is a e-commerce plugin for Pimcore. ([源码](https://github.com/coreshop/CoreShop)) `GPL-3.0` `PHP`
- [Drupal Commerce](https://drupalcommerce.org) - Drupal Commerce is a popular e-commerce module for Drupal CMS, with support for dozens of payment, shipping, and shopping related modules. ([源码](https://github.com/drupalcommerce/commerce)) `GPL-2.0` `PHP`
- [Magento](https://magento.com/) - Leading provider of open omnichannel innovation. ([Demo](https://magento.com/schedule-a-demo), [源码](https://github.com/magento/magento2)) `OSL-3.0` `PHP`
- [Microweber](https://microweber.com/) - Drag and Drop CMS and online shop. ([Demo](https://demo.microweber.org/), [源码](https://github.com/microweber/microweber)) `Apache-2.0` `PHP`
- [Open Source POS](https://www.opensourcepos.org/) - Open Source Point of Sale is a web based point of sale system. ([源码](https://github.com/opensourcepos/opensourcepos)) `MIT` `PHP`
- [OpenBazaar](https://www.openbazaar.org) - Decentralized marketplace using cryptocurrency. ([源码](https://github.com/openbazaar/openbazaar-go)) `MIT` `Go`
- [OpenCart](https://www.opencart.com) - Free open source shopping cart solution. ([源码](https://github.com/opencart/opencart)) `GPL-3.0` `PHP`
- [OXID eShop](https://oxidforge.org) - OXID eShop is a flexible open source e-commerce software with a wide range of functionalities. ([Demo](https://demoshop.oxid-esales.com/community-edition/), [源码](https://github.com/OXID-eSales/oxideshop_ce)) `GPL-3.0` `PHP`
- [PrestaShop](https://www.prestashop.com/) - PrestaShop offers a free, open-source and fully scalable e-commerce solution. ([Demo](https://demo.prestashop.com/), [源码](https://github.com/PrestaShop/PrestaShop)) `OSL-3.0` `PHP`
- [Pretix](https://pretix.eu/) - Django based ticket sales platform for events. ([源码](https://github.com/pretix)) `Apache-2.0` `Python`
- [Reaction Commerce](https://reactioncommerce.com/) - Customizable, real-time reactive, Javascript commerce platform. ([源码](https://github.com/reactioncommerce/reaction)) `GPL-3.0` `Nodejs`
- [Saleor](https://saleor.io) - Django based open-sourced e-commerce storefront. ([Demo](https://demo.getsaleor.com/), [源码](https://github.com/mirumee/saleor)) `BSD-3-Clause` `Python`
- [Shopware Community Edition](https://shopware.com/community/) - PHP based open source e-commerce software made in Germany. ([Demo](https://www.shopware.com/en/test-demo/), [源码](https://github.com/shopware/platform)) `MIT` `PHP`
- [Shuup](https://www.shuup.com/) - Django powered fully customizable open source e-commerce framework for small and large sites. ([源码](https://github.com/shuup/shuup)) `AGPL-3.0` `Python`
- [Solidus](https://solidus.io/) - A free, open-source ecommerce platform that gives you complete control over your store. ([Demo](http://demo.solidus.io/), [源码](https://github.com/solidusio/solidus)) `BSD-3-Clause` `Ruby`
- [Spree Commerce](https://spreecommerce.org) - Spree is a complete, modular & API-driven open source e-commerce solution for Ruby on Rails. ([Demo](https://new-ux.spreecommerce.org/), [源码](https://github.com/spree/spree)) `BSD-3-Clause` `Ruby`
- [Sylius](https://sylius.com) - Symfony2 powered open source full-stack platform for eCommerce. ([Demo](https://sylius.com/try/), [源码](https://github.com/Sylius/Sylius)) `MIT` `PHP`
- [Thelia](https://thelia.net/) - Thelia is an open source and flexible e-commerce solution. ([Demo](https://demo.thelia.net/), [源码](https://github.com/thelia/thelia)) `LGPL-3.0` `PHP`
- [WooCommerce](https://woocommerce.com/) - WordPress based e-commerce solution. ([源码](https://github.com/woocommerce/woocommerce)) `GPL-3.0` `PHP`
- [Yclas](https://yclas.com/) - Free open-source, self-hosted CMS for classifieds sites. ([源码](https://github.com/yclas/yclas)) `GPL-3.0` `PHP`


### Federated Identity & Authentication

**[`^        返回顶部        ^`](#)**

**请访问 [awesome-sysadmin/Identity Management](https://github.com/awesome-foss/awesome-sysadmin#identity-management)**


### Feed Readers

**[`^        返回顶部        ^`](#)**

A [news aggregator](https://en.wikipedia.org/wiki/News_aggregator), also termed a feed aggregator, feed reader, news reader, [RSS](https://en.wikipedia.org/wiki/RSS) reader or simply an aggregator, is client software or a web application that aggregates syndicated web content such as online newspapers, blogs/vlogs, podcasts, and other updates in one location for easy viewing. This also section includes RSS/Atom automation tools.

- [CommaFeed](https://www.commafeed.com/) - Google Reader inspired self-hosted RSS reader. ([源码](https://github.com/Athou/commafeed)) `Apache-2.0` `Java`
- [FeedHQ](https://feedhq.org/) - FeedHQ is a web-based feed reader. ([源码](https://github.com/feedhq/feedhq)) `BSD-3-Clause` `Python`
- [Feedpushr](https://github.com/ncarlier/feedpushr) - Powerful RSS aggregator, able to transform and send articles to many outputs. Single binary, extensible with plugins. `GPL-3.0` `Go`
- [FreshRSS](https://freshrss.org/) - Self-hostable RSS feed aggregator. ([Demo](https://demo.freshrss.org/i/), [源码](https://github.com/FreshRSS/FreshRSS), [Clients](https://github.com/Alkarex/EasyRSS)) `AGPL-3.0` `PHP`
- [Full-Text RSS](https://fivefilters.org/content-only) - Extract article content from news sites and blogs and convert RSS feeds that contain only extracts of stories to full-text feeds. Developed by FiveFilters.org. ([源码](https://bitbucket.org/fivefilters/full-text-rss)) `GPL-3.0` `PHP`
- [Goeland](https://github.com/slurdge/goeland) - Reads RSS/Atom feeds and filter/digest them to create beautiful emails. `MIT` `Go`
- [gritttt-rss](http://gritttt-rss.nicolashoening.de/) - More features for Tiny Tiny RSS. ([源码](https://github.com/nhoening/gritttt-rss)) `BSD-2-Clause` `Python`
- [JARR](https://1pxsolidblack.pl/jarr-en.html) - JARR (Just Another RSS Reader) is a web-based news aggregator and reader (fork of Newspipe). ([Demo](https://jarr.info/login?next=%2F), [源码](https://github.com/jaesivsm/JARR)) `AGPL-3.0` `Python`
- [Kriss Feed](https://tontof.net/kriss/feed/) - Simple and smart (or stupid) feed reader. ([Demo](https://tontof.net/feed/), [源码](https://github.com/tontof/kriss_feed)) `CC0-1.0` `PHP`
- [Leed](https://github.com/LeedRSS/Leed) - Leed (for Light Feed) is a Free and minimalist RSS aggregator. `AGPL-3.0` `PHP`
- [Leselys](https://github.com/toxinu/leselys) - Your very elegant RSS reader. `AGPL-3.0` `Python`
- [Lite-Reader](https://github.com/cubny/lite-reader) - Read your feeds on your own machine with a simple and lite application. ([Demo](http://cubny.com/lite-reader/)) `BSD-3-Clause` `PHP`
- [Miniflux](https://miniflux.app/) - Miniflux is a minimalist and open source news reader, written in Go and PostgreSQL. ([源码](https://github.com/miniflux/v2)) `Apache-2.0` `Go`
- [Moonmoon](https://moonmoon.org/) - simple feed aggregator (planet like): it only aggregates feeds and spits them out in one single page. ([源码](https://github.com/moonmoon/moonmoon)) `BSD-3-Clause` `PHP`
- [NewsBlur](https://www.newsblur.com/) - NewsBlur is a personal news reader that brings people together to talk about the world. A new sound of an old instrument. ([源码](https://github.com/samuelclay/NewsBlur)) `MIT` `Python`
- [newsdash](https://github.com/buzz/newsdash) - A news dashboard inspired by iGoogle and Netvibes. `AGPL-3.0` `Nodejs`
- [Newspipe](https://git.sr.ht/~cedric/newspipe) - Newspipe is a web news reader. ([Demo](https://www.newspipe.org/signup)) `AGPL-3.0` `Python`
- [PolitePol](https://github.com/taroved/pol) - Online tool for creation of RSS feeds for any web page. ([Demo](https://politepol.com)) `MIT` `Python`
- [reader](https://github.com/lemon24/reader) - A Python feed reader web app and library (so you can use it to build your own), with only standard library and pure-Python dependencies. `BSD-3-Clause` `Python`
- [RSS-Bridge](https://github.com/RSS-Bridge/rss-bridge) - rss-bridge is a PHP project capable of generating ATOM feeds for websites which don't have one. `Unlicense` `PHP`
- [RSS Fulltext Proxy](https://github.com/Kombustor/rss-fulltext-proxy) - Mirrors RSS feeds to return the full content of the items, extracted from the website. `MIT` `Nodejs`
- [RSS Merger](https://github.com/taophp/rss-merger) - PHP script which will take multiple RSS / Atom feeds as input and merge them into a single RSS feed. `GPL-2.0` `PHP`
- [RSS Monster](https://github.com/pietheinstrengholt/rssmonster) - RSS Monster is an easy to use web-based RSS aggregator and reader compatible with the Fever API, created as an alternative for Google Reader. `MIT` `PHP`
- [RSS2EMail](https://github.com/rss2email/rss2email) - Fetches RSS/Atom-feeds and pushes new Content to any email-receiver, supports OPML. `GPL-2.0` `Python`
- [Screaming Liquid Tiger](https://github.com/herrbischoff/screaming-liquid-tiger) - Simple script to automatically generate valid RSS and Atom feeds from a list of media files in the same folder. `MIT` `PHP`
- [Selfoss](https://selfoss.aditu.de/) - New multipurpose rss reader, live stream, mashup, aggregation web application. ([源码](https://github.com/fossar/selfoss)) `GPL-3.0` `PHP`
- [Sismics Reader](https://www.sismics.com/reader/) - Free and open source feeds reader, including all major Google Reader features. ([Demo](https://www.sismics.com/reader/#!/demo), [源码](https://github.com/sismics/reader)) `GPL-2.0` `Java`
- [Stringer](https://github.com/swanson/stringer) - Work-in-progress self-hosted, anti-social RSS reader. `MIT` `Ruby`
- [Temboz](https://github.com/fazalmajid/temboz) - Two-column feed reader emphasizing filtering capabilities to manage information overload. `MIT` `Python`
- [Tiny Tiny RSS](https://tt-rss.org) - Open source web-based news feed (RSS/Atom) reader and aggregator. ([Demo](https://framanews.org/), [源码](https://git.tt-rss.org/fox/tt-rss)) `GPL-3.0` `PHP`
- [ttrss-mobile](https://github.com/mboinet/ttrss-mobile) - Mobile webapp for Tiny Tiny RSS. `AGPL-3.0` `Javascript`
- [ttrss-reader](https://github.com/kucrut/ttrss-reader) - Light and responsive client for TTRSS. `GPL-2.0` `Javascript`
- [Winds](https://getstream.io/winds/) `⚠` - Open source and beautiful RSS reader built using React/Redux/Sails/Node and Stream. It showcases personalized feeds powered by the Stream API. ([Demo](https://winds.getstream.io/), [源码](https://github.com/GetStream/Winds)) `BSD-3-Clause` `Nodejs`


### File Transfer & Synchronization

**[`^        返回顶部        ^`](#)**

_关联: [Groupware](#groupware)_

- [Git Annex](https://git-annex.branchable.com/) - File synchronization between computers, servers, external drives. ([源码](https://git.joeyh.name/index.cgi/git-annex.git/)) `GPL-3.0` `Haskell`
- [Kinto](https://kinto.readthedocs.org) - Kinto is a minimalist JSON storage service with synchronisation and sharing abilities. ([源码](https://github.com/Kinto)) `Apache-2.0` `Python`
- [myDrive](https://github.com/subnub/myDrive) - Fully featured online storage solution, upload/download files, photo/video viewer, and more, all through the web client. ([Demo](https://mydrive-demo.herokuapp.com/)) `GPL-3.0` `Nodejs`
- [Nextcloud](https://nextcloud.com/) - Access and share your files, calendars, contacts, mail and [more](https://apps.nextcloud.com/) from any device, on your terms. ([Demo](https://demo.nextcloud.com/), [源码](https://github.com/nextcloud/server)) `AGPL-3.0` `PHP`
- [OpenSSH SFTP server](https://www.openssh.com/) - Secure File Transfer Program. ([源码](https://cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.bin/ssh)) `BSD-2-Clause` `C`
- [ownCloud](https://owncloud.org/) - All-in-one solution for saving, synchronizing, viewing, editing and sharing files, calendars, address books and more. ([源码](https://github.com/owncloud/core), [Clients](https://github.com/owncloud/core/wiki/Apps)) `AGPL-3.0` `PHP`
- [Pydio](https://pydio.com/) - Turn any web server into a powerful file management system and an alternative to mainstream cloud storage providers. ([源码](https://github.com/pydio/cells)) `AGPL-3.0` `Go`
- [Samba](https://www.samba.org/) - Samba is the standard Windows interoperability suite of programs for Linux and Unix. It provides secure, stable and fast file and print services for all clients using the SMB/CIFS protocol. ([源码](https://git.samba.org/samba.git/)) `GPL-3.0` `C`
- [Seafile](https://www.seafile.com/en/home/) - File hosting and sharing solution primary for teams and organizations. ([源码](https://github.com/haiwen/seafile)) `GPL-2.0/GPL-3.0/AGPL-3.0/Apache-2.0` `C`
- [SparkleShare](https://sparkleshare.org/) - Self hosted, instant, secure file sync. ([源码](https://github.com/hbons/SparkleShare)) `GPL-3.0` `C#`
- [Syncany](https://www.syncany.org/) - Secure file sync software for arbitrary storage backends, an open-source cloud storage and filesharing application. Securely synchronize your files to any kind of storage. `GPL-3.0` `Java`
- [Syncthing](https://syncthing.net/) - Syncthing is an open source peer-to-peer file synchronisation tool. ([源码](https://github.com/syncthing/syncthing)) `MPL-2.0` `Go`
- [Unison](https://www.cis.upenn.edu/~bcpierce/unison/) - Unison is a file-synchronization tool for OSX, Unix, and Windows. `GPL-3.0` `OCaml`
- [Z-Push](https://z-push.org/) - Implementation of Microsoft’s ActiveSync protocol. ([源码](https://stash.kopano.io/projects/ZHUB/repos/z-push)) `AGPL-3.0` `PHP`


### File Transfer - Distributed Filesystems

**[`^        返回顶部        ^`](#)**

**请访问 [awesome-sysadmin/Distributed Filesystems](https://github.com/awesome-foss/awesome-sysadmin#distributed-filesystems)**


### File Transfer - Object Storage & File Servers

**[`^        返回顶部        ^`](#)**

- [Minio](https://minio.io/) - Minio is an open source object storage server compatible with Amazon S3 APIs. ([源码](https://github.com/minio/minio)) `Apache-2.0` `Go`
- [SeaweedFS](https://github.com/chrislusf/seaweedfs) - SeaweedFS is an open source distributed file system supporting WebDAV, S3 API, FUSE mount, HDFS, etc, optimized for lots of small files, and easy to add capacity. `Apache-2.0` `Go`
- [SFTPGo](https://github.com/drakkan/sftpgo) - Flexible, fully featured and highly configurable SFTP server with optional FTP/S and WebDAV support. `AGPL-3.0` `Go`
- [Zenko CloudServer](https://www.zenko.io/cloudserver) - Zenko CloudServer, an open-source implementation of a server handling the Amazon S3 protocol. ([源码](https://github.com/scality/cloudserver)) `Apache-2.0` `Nodejs`


### File Transfer - Peer-to-peer Filesharing

**[`^        返回顶部        ^`](#)**

- [bittorrent-tracker](https://webtorrent.io/) - Simple, robust, BitTorrent tracker (client and server) implementation. ([源码](https://github.com/webtorrent/bittorrent-tracker)) `MIT` `Nodejs`
- [cloud-torrent](https://github.com/jpillora/cloud-torrent) - Torrent Web Client with HTTP retrievable or streamable downloaded files. `AGPL-3.0` `Go`
- [Dat Project](https://datproject.org) - Powerful decentralized file sharing applications built from a large ecosystem of modules. ([源码](https://github.com/datproject)) `MIT` `Nodejs`
- [exatorrent](https://github.com/varbhat/exatorrent) - BitTorrent client written in Go that can be run locally or hosted on a remote server, and supports streaming via HTTP. `GPL-3.0` `Go`
- [FilePizza](https://file.pizza/) - Peer-to-peer file transfers in your browser. ([源码](https://github.com/kern/filepizza)) `BSD-3-Clause` `Nodejs`
- [instant.io](https://github.com/webtorrent/instant.io) - Streaming file transfer over WebTorrent. ([Demo](https://instant.io)) `MIT` `Nodejs`
- [Magnetico](https://github.com/boramalper/magnetico) - Magnetico is the first autonomous (self-hosted) BitTorrent DHT search engine suite that is designed for end-users. `AGPL-3.0` `Python`
- [Magnetissimo](https://github.com/sergiotapia/magnetissimo) - Search engine that indexes all popular torrent sites. `MIT` `Elixir`
- [Opentracker](https://erdgeist.org/arts/software/opentracker/) - Open and free bittorrent tracker. It aims for minimal resource usage and is intended to run at your wlan router. ([源码](https://erdgeist.org/gitweb/opentracker/)) `Beerware` `C`
- [peerflix-server](https://github.com/asapach/peerflix-server) - Downloads torrent files and provides a direct link download or a direct link stream. `MIT` `Nodejs`
- [qBittorrent](https://www.qbittorrent.org/) - Free cross-platform bittorrent client with a feature rich Web UI for remote access. ([源码](https://github.com/qbittorrent/qBittorrent)) `GPL-2.0` `C++`
- [rartracker](https://github.com/swetorrentking/rartracker) - Complete private bittorrent tracker. `WTFPL` `PHP`
- [Send](https://github.com/timvisee/send) - Simple, private, end to end encrypted temporary file sharing, originally built by Mozilla. ([Clients](https://github.com/timvisee/send#clients)) `MPL-2.0` `Nodejs`
- [Torrents.csv](https://codeberg.org/heretic/torrents-csv-server) - A self-hostable torrent search engine. `GPL-3.0` `Rust`
- [Transmission](https://transmissionbt.com/) - Fast, easy, Free Bittorrent client. ([源码](https://github.com/transmission/transmission)) `GPL-3.0` `C`


### File Transfer - Single-click & Drag-n-drop Upload

**[`^        返回顶部        ^`](#)**

- [ass](https://github.com/tycrek/ass) - The superior self-hosted ShareX server. For use with clients such as ShareX (Windows), Flameshot (Linux), & MagicCap (Linux, macOS). `ISC` `Nodejs`
- [BoZoN](https://github.com/broncowdd/BoZoN) - Minimalist Drag and drop file sharing app. `AGPL-3.0` `PHP`
- [Chibisafe](https://lolisafe.moe/) - Blazing fast file uploader and awesome bunker written in node. ([源码](https://github.com/weebdev/chibisafe)) `MIT` `Nodejs`
- [Coquelicot](https://coquelicot.potager.org/) - Coquelicot is a “one-click” file sharing web application with a focus on protecting users’ privacy. ([源码](https://coquelicot.potager.org/dist/coquelicot-0.9.6.tar.gz)) `AGPL-3.0` `Ruby`
- [elixire](https://elixi.re) - Simple yet advanced screenshot uploading and link shortening service. ([源码](https://gitlab.com/elixire/elixire), [Clients](https://gitlab.com/elixire/elixiremanager)) `AGPL-3.0` `Python`
- [fibridge](https://github.com/anderspitman/fibridge-proxy-rs) - Stream huge files out of your browser without having to upload. `MIT` `Rust`
- [Files Sharing](https://github.com/axeloz/filesharing) - Open Source and self-hosted files sharing application based on unique and temporary links. `GPL-3.0` `PHP`
- [FileShelter](https://github.com/epoupon/fileshelter) - FileShelter is a self-hosted software that allows you to easily share files over the Internet. ([Demo](https://fileshelter.demo.poupon.io/)) `GPL-3.0` `C++`
- [FireShare](https://github.com/rockmanvnx6/FireShare) - A full-stack, pub-sub, real-time secure file sharing system. ([Demo](https://auspham.dev/FireShare)) `MIT` `Nodejs`
- [Gokapi](https://github.com/Forceu/gokapi) - Lightweight server to share files, which expire after a set amount of downloads or days. Similar to the discontinued Firefox Send, with the difference that only the admin is allowed to upload files. `GPL-3.0` `Go`
- [goploader](https://github.com/Depado/goploader) - Easy file sharing with server-side encryption, curl/httpie/wget compliant. `MIT` `Go`
- [image-uploader](https://github.com/daggy1234/image-uploader) - A shareX compatible image uploader built for speed with a web interface and REST API. `AGPL-3.0` `Rust`
- [imgpush](https://github.com/hauxir/imgpush) - imgpush is a self-hosted file upload service that can easily be integrated into other webapps. `MIT` `Python`
- [Jirafeau](https://gitlab.com/mojo42/Jirafeau) - Jirafeau is a web site permitting to upload a file in a simple way and give an unique link to it. ([Demo](http://jirafeau.net/)) `AGPL-3.0` `PHP`
- [Kleeja](https://kleeja.net/) - File Upload/sharing application, used by thousands of webmasters since 2007. ([源码](https://github.com/kleeja-official/kleeja)) `GPL-2.0` `PHP`
- [linx-server](https://github.com/ZizzyDizzyMC/linx-server) - Simple file sharing and pastebin with API, auto-expiry, deletion keys, and web seed support. ([Demo](https://put.icu/)) `GPL-3.0` `Go`
- [lufi](https://framagit.org/fiat-tux/hat-softwares/lufi) - Let's Upload that FIle, client-side encrypted. ([Demo](https://demo.lufi.io), [源码](https://framagit.org/fiat-tux/hat-softwares/lufi/tree/master)) `AGPL-3.0` `Perl`
- [lutim](https://github.com/ldidry/lutim) - Let's Upload That Image. `AGPL-3.0` `Perl`
- [OnionShare](https://github.com/micahflee/onionshare) - Securely and anonymously share a file of any size. `GPL-2.0` `Python`
- [PictShare](https://www.pictshare.net/) - PictShare is a multi lingual, open source image hosting service with a simple resizing and upload API. ([源码](https://github.com/HaschekSolutions/pictshare)) `Apache-2.0` `PHP`
- [Plik](https://github.com/root-gg/plik) - Plik is a scalable and friendly temporary file upload system. ([Demo](https://plik.root.gg/)) `MIT` `Go`
- [Pomf](https://github.com/Pomf/Pomf) - Simple file uploading and sharing, source for the now shut down site Pomf.se. `MIT` `PHP`
- [ProjectSend](https://www.projectsend.org/) - Upload files and assign them to specific clients you create. Give access to those files to your clients. ([源码](https://github.com/projectsend/projectsend)) `GPL-2.0` `PHP`
- [PsiTransfer](https://github.com/psi-4ward/psitransfer) - Simple open source self-hosted file sharing solution with robust up-/download-resume and password protection. `BSD-2-Clause` `Nodejs`
- [Pste](https://dev.pste.pw/) - Just a simple file hosting application inspired by the likes of pomf.se and teknik.io. ([源码](https://github.com/FoxDev/pste)) `GPL-3.0` `Python`
- [QuickShare](https://github.com/ihexxa/quickshare) - Quick and simple file sharing between different devices. ([Demo](https://hexxa-quickshare.herokuapp.com/)) `LGPL-3.0` `Go`
- [Share](https://github.com/MrDemonWolf/share) - Simple yet advanced uploader - upload files, images and text with moderation tools for admins. Can be used for friends and family or just for you. Integration with ShareX and more. `MIT` `Nodejs`
- [Sharry](https://github.com/eikek/sharry) - Share files easily over the internet between authenticated and anonymous users (both ways) with resumable up- and downloads. `GPL-3.0` `Scala/Java`
- [transfer.sh](https://transfer.sh) - Easy file sharing from the command line. ([源码](https://github.com/dutchcoders/transfer.sh)) `MIT` `Go`
- [Uguu](https://uguu.se/) - Stores files and deletes after X amount of time. ([源码](https://github.com/nokonoko/uguu)) `MIT` `PHP`
- [Up1](https://github.com/Upload/Up1) - Client-side Encrypted Image Host. `MIT` `Nodejs`
- [Void](https://github.com/AlphaNecron/Void) - Lightweight, fast and elegant file hosting service for ShareX with Web UI and REST API. ([源码](https://github.com/AlphaNecron/Void/)) `MIT` `Nodejs`
- [Web-File-Uploader](https://v2.femto.pw/) - A simple tool to let people upload and share images and files. ([源码](https://github.com/femto-apps/web-file-uploader)) `MIT` `Nodejs`
- [XBackBone](https://github.com/SergiX44/XBackBone) - A simple, fast and lightweight file manager with instant sharing tools integration, like ShareX (a free and open-source screenshot utility for Windows). `AGPL-3.0` `PHP`
- [YouTransfer](https://www.youtransfer.io) - YouTransfer is a simple but elegant self-hosted file transfer and sharing solution. ([源码](https://github.com/YouTransfer/YouTransfer)) `Apache-2.0` `Nodejs`
- [Zipline](https://zipline.diced.me/) - A lightweight, fast and reliable file sharing server that is commonly used with ShareX, offering a react-based Web UI and fast API. ([源码](https://github.com/diced/zipline)) `MIT` `Nodejs`

### File Transfer - Web-based File Managers

**[`^        返回顶部        ^`](#)**

- [Apaxy](https://oupala.github.io/apaxy/) - Theme built to enhance the experience of browsing web directories, using the mod_autoindex Apache module and some CSS to override the default style of a directory listing. ([源码](https://github.com/oupala/apaxy)) `GPL-3.0` `HTML`
- [DirectoryLister](https://www.directorylister.com/) - Simple PHP based directory lister that lists a directory and all its sub-directories and allows you to navigate there within. ([源码](https://github.com/DirectoryLister/DirectoryLister)) `MIT` `PHP`
- [explorer](https://soyuka.github.io/explorer/) - Highly-configurable directory listing. ([源码](https://github.com/soyuka/explorer)) `MIT` `Nodejs`
- [filebrowser](https://filebrowser.org/) - Web File Browser with a Material Design web interface. ([源码](https://github.com/filebrowser/filebrowser)) `Apache-2.0` `Go`
- [FileGator](https://filegator.io/) - FileGator is a powerful multi-user file manager with a single page front-end. ([Demo](https://demo.filegator.io), [源码](https://github.com/filegator/filegator)) `MIT` `PHP`
- [Filestash](https://www.filestash.app/) - A web file manager that lets you manage your data anywhere it is located: FTP, SFTP, WebDAV, Git, S3, Minio, Dropbox, or Google Drive . ([Demo](https://demo.filestash.app/), [源码](https://github.com/mickael-kerjean/filestash)) `AGPL-3.0` `Go`
- [goBrowser](https://github.com/xataz/gobrowser) - Simple http file browser. `GPL-3.0` `Go`
- [Gossa](https://github.com/pldubouilh/gossa) - Gossa is a light and simple webserver for your files. `MIT` `Go`
- [h5ai](https://larsjung.de/h5ai/) - Modern file indexer for HTTP web servers with focus on your files. Directories are displayed in a appealing way and browsing them is enhanced by different views, a breadcrumb and a tree overview. ([Demo](https://larsjung.de/h5ai/demo/), [源码](https://github.com/lrsjng/h5ai)) `MIT` `PHP`
- [IFM](https://github.com/misterunknown/ifm) - Single script file manager. `MIT` `PHP`
- [ResourceSpace](https://www.resourcespace.com) - ResourceSpace open source digital asset management software is the simple, fast, and free way to organise your digital assets. ([Demo](https://www.resourcespace.com/trial), [源码](https://www.resourcespace.com/svn)) `BSD-4-Clause` `PHP`
- [s3server](https://github.com/jessfraz/s3server) - Simple HTTP interface to index and browse files in a public S3 or Google Cloud Storage bucket. `MIT` `Go`
- [Surfer](https://git.cloudron.io/cloudron/surfer) - Simple static file server with webui to manage files. `MIT` `Nodejs`
- [TagSpaces](https://www.tagspaces.org/) - TagSpaces is an offline, cross-platform file manager and organiser that also can function as a note taking app. The WebDAV version of the application can be installed on top of a WebDAV servers such as Nextcloud or ownCloud. ([Demo](https://demo.tagspaces.com), [源码](https://github.com/tagspaces/tagspaces)) `AGPL-3.0` `Javascript`
- [updog](https://github.com/sc0tfree/updog) - Updog is a replacement for Python's SimpleHTTPServer. It allows uploading and downloading via HTTP/S, can set ad hoc SSL certificates and use http basic auth. `MIT` `Python`


### Games

**[`^        返回顶部        ^`](#)**

Games, game servers and control panels.

- [A Dark Room](https://github.com/doublespeakgames/adarkroom) - Minimalist text adventure game for your browser. ([Demo](https://adarkroom.doublespeakgames.com/)) `MPL-2.0` `HTML5`
- [elevatorsaga](https://play.elevatorsaga.com/) - The elevator programming game. ([源码](https://github.com/magwo/elevatorsaga)) `MIT` `Javascript`
- [EmuLinkerSF](https://emulinker.org) - EmuLinkerSF is an open source Kaillera server. Kaillera is a client/server system that any emulator can implement to enable netplay over the Internet. ([源码](https://github.com/God-Weapon/EmuLinkerSF)) `GPL-2.0` `Java`
- [Hextris](https://github.com/Hextris/hextris) - Fast paced HTML5 puzzle game inspired by Tetris. ([Demo](https://hextris.github.io/hextris)) `GPL-3.0` `HTML5`
- [Legend of the Green Dragon](https://github.com/lotgd/core) - Legend of the Green Dragon is a text-based RPG originally developed by Eric Stevens and JT Traub as a remake of and homage to the classic BBS Door game, Legend of the Red Dragon, by Seth Able Robinson. ([Demo](http://lotgd.net/)) `AGPL-3.0` `PHP`
- [Lila](https://lichess.org/) - The forever free, adless and open source chess server powering lichess.org, with official iOS and Android client apps. ([源码](https://github.com/ornicar/lila)) `AGPL-3.0` `Scala`
- [Mindustry](https://mindustrygame.github.io/) - Factorio-like tower defense game. Build production chains to gather more resources, and build complex facilities. ([源码](https://github.com/Anuken/Mindustry)) `GPL-3.0` `Java`
- [Minetest](https://www.minetest.net/) - An open source voxel game engine. Play one of our many games, mod a game to your liking, make your own game, or play on a multiplayer server. ([源码](https://github.com/minetest/minetest)) `LGPL-2.1/CC-BY-SA-3.0/Other` `C++`
- [MTA:SA](https://mtasa.com/) `⚠` - Multi Theft Auto (MTA) is a software project that adds network play functionality to Rockstar North's Grand Theft Auto game series, in which this functionality is not originally found. ([源码](https://github.com/multitheftauto/mtasa-blue)) `GPL-3.0` `C++`
- [Net64+](https://net64-mod.github.io) `⚠` - Net64 aka SM64O allows playing Super Mario 64 in an online multiplayer mode. Net64+ is the official continuation of the program and features an integrated server list. ([源码](https://github.com/Tarnadas/net64plus-server/), [Clients](https://github.com/Tarnadas/net64plus/)) `MIT` `Nodejs`
- [node-virtual-gamepads](https://github.com/jehervy/node-virtual-gamepads) - Turn your smartphone into a game controller, keyboard, or touchpad for a remote Linux OS machine. `MIT` `Nodejs/CoffeScript`
- [piqueserver](https://github.com/piqueserver/piqueserver) - Server for openspades, the first-person shooter in a destructible voxel world. ([Clients](https://github.com/yvt/openspades)) `GPL-3.0` `Python/C++`
- [Posio](https://github.com/abrenaut/posio) - Geography multiplayer game. `MIT` `Python`
- [QuakeJS](https://github.com/begleysm/quakejs) - QuakeJS is a port of ioquake3 to Javascript that can be played in a browser. `MIT` `Nodejs`
- [Quizmaster](https://github.com/nymanjens/quizmaster) - A web-app for conducting a quiz, including a page for players to enter their answers. `Apache-2.0` `Scala`
- [RconCli](https://github.com/gorcon/rcon-cli) - CLI for executing queries on a remote Valve Source dedicated server using the RCON Protocol. `MIT` `Go`
- [SourceBans++](https://sbpp.github.io) - Admin, ban, and communication management system for games running on the Source engine. ([源码](https://github.com/sbpp/sourcebans-pp)) `CC-BY-SA-4.0` `PHP`
- [Teeworlds](https://www.teeworlds.com) - Open source 2D retro multiplayer shooter. ([源码](https://github.com/teeworlds/teeworlds)) `BSD-3-Clause/Other` `C++`
- [The Battle for Wesnoth](https://github.com/wesnoth/wesnoth) - The Battle for Wesnoth is an Open Source, turn-based tactical strategy game with a high fantasy theme, featuring both singleplayer and online/hotseat multiplayer combat. `GPL-2.0` `C++`
- [Zero-K](https://zero-k.info/) - Open Source on Springrts engine. Zero-K is a traditional real time strategy game with a focus on player creativity through terrain manipulation, physics, and a large roster of unique units - all while being balanced to support competitive play. ([源码](https://github.com/ZeroK-RTS/Zero-K)) `GPL-2.0` `Lua`


### Gateways and Terminal Sharing

**[`^        返回顶部        ^`](#)**

- [asciinema](https://github.com/asciinema/asciinema-server) - Web app for hosting asciicasts. ([Demo](https://asciinema.org/)) `Apache-2.0` `Elixir/Docker`
- [GateOne](http://liftoffsoftware.com/Products/GateOne) - Gate One is an HTML5 web-based terminal emulator and SSH client. ([源码](https://github.com/liftoff/GateOne)) `AGPL-3.0` `Python`
- [Guacamole](https://guacamole.apache.org) - Guacamole is a clientless remote desktop gateway. It supports standard protocols like VNC and RDP. ([源码](https://github.com/glyptodon/)) `Apache-2.0` `Java/C`
- [Neko](https://neko.m1k1o.net) - A self hosted virtual browser (rabb.it clone) that runs in Docker. ([源码](https://github.com/m1k1o/neko)) `Apache-2.0` `Docker/Go`
- [oneye](https://oneye-project.org/) - Cloud software to access your data from everywhere with any browser. ([Demo](https://wiki.oneye-project.org/0.9:demo), [源码](https://github.com/oneye/oneye)) `AGPL-3.0` `PHP`
- [OS.js](https://www.os-js.org/) - Desktop implementation for your browser with a fully-fledged window manager, Application APIs, GUI toolkits and filesystem abstraction. ([Demo](https://demo.os-js.org/), [源码](https://github.com/os-js/OS.js)) `BSD-2-Clause` `Nodejs`
- [ShellHub](https://www.shellhub.io) - ShellHub is a modern SSH server for remotely accessing linux devices via command line (using any SSH client) or web-based user interface, designed as an alternative to sshd. Think ShellHub as centralized SSH for the edge and cloud computing. ([源码](https://github.com/shellhub-io/shellhub)) `Apache-2.0` `Go/Other`
- [Sshwifty](https://github.com/nirui/sshwifty) - Sshwifty is a SSH and Telnet connector made for the Web. `AGPL-3.0` `Go/Docker`
- [Teleport](https://goteleport.com/) - Certificate authority and access plane for SSH, Kubernetes, web applications, and databases. ([源码](https://github.com/gravitational/teleport)) `Apache-2.0` `Go`
- [tmate](https://tmate.io/) - Instant terminal sharing. ([源码](https://github.com/tmate-io/tmate)) `ISC` `C`


### Genealogy

**[`^        返回顶部        ^`](#)**

- [Genea.app](https://genea.app/) - Genea is a privacy by design and open source tool anyone can use to author or edit their family tree. Data is stored in the GEDCOM format and all processing is done in the browser. ([源码](https://github.com/genea-app/genea-app)) `MIT` `Javascript`
- [GeneWeb](https://geneweb.tuxfamily.org/wiki/GeneWeb) - GeneWeb is an open source genealogy software written in OCaml. It comes with a Web interface and can be used off-line or as a Web service. ([Demo](https://demo.geneweb.tuxfamily.org/gw7/), [源码](https://github.com/geneweb/geneweb)) `GPL-2.0` `OCaml`
- [webtrees](https://www.webtrees.net) - Webtrees is the web's leading on-line collaborative genealogy application. ([Demo](https://dev.webtrees.net/demo-stable/index.php?ctype=gedcom&ged=demo), [源码](https://github.com/fisharebest/webtrees)) `GPL-3.0` `PHP`


### Groupware

**[`^        返回顶部        ^`](#)**

- [BlueMind](https://www.bluemind.net/en/) - Groupware with email, calendar, addressbooks, exchange active sync, exchange MAPI protocol support. ([源码](https://forge.bluemind.net/stash/projects/BM/repos/bluemind-public/browse)) `AGPL-3.0` `Java`
- [Citadel](https://www.citadel.org/doku.php) - Groupware including email, calendar/scheduling, address books, forums, mailing lists, IM, wiki and blog engines, RSS aggregation and more. ([源码](https://www.citadel.org/source.html)) `GPL-3.0` `C`
- [Corteza](https://cortezaproject.org) - CRM including a unified workspace, enterprise messaging and a low code environment for rapidly and securely delivering records-based management solutions. ([Demo](https://latest.cortezaproject.org), [源码](https://github.com/cortezaproject/corteza-server)) `Apache-2.0` `Go`
- [Cozy Cloud](https://cozy.io) - Personal cloud where you can manage and sync your contact, files and calendars, and manage your budget with an app store full of community contributions. ([源码](https://github.com/cozy)) `GPL-3.0` `Nodejs`
- [Group Office](https://www.group-office.com) - Group-Office is an enterprise CRM and groupware tool. Share projects, calendars, files and e-mail online with co-workers and clients. ([源码](https://github.com/Intermesh/groupoffice/)) `AGPL-3.0` `PHP`
- [egroupware](https://www.egroupware.org/) - Software suite including calendars, address books, notepad, project management tools, client relationship management tools (CRM), knowledge management tools, a wiki and a CMS. ([源码](https://github.com/EGroupware/egroupware)) `GPL-2.0` `PHP`
- [EspoCRM](https://www.espocrm.com/) - CRM with a frontend designed as a single page application, and a REST API. ([Demo](https://demo.espocrm.com/), [源码](https://github.com/espocrm/espocrm)) `GPL-3.0` `PHP`
- [Horde](https://www.horde.org/) - The Horde Project is about creating high quality Open Source applications and libraries, based on PHP and the Horde Framework. ([Demo](http://demo.horde.org/login.php), [源码](https://github.com/horde/horde)) `GPL-2.0` `PHP`
- [HRCloud2](https://github.com/zelon88/HRCloud2) - Full-featured home hosted Cloud Drive, Personal Assistant, App Launcher, File Converter, Streamer, Share Tool and more. `GPL-3.0` `PHP`
- [Kolab](https://kolab.org/) - Kolab community is a unified communication and collaboration system. ([源码](https://git.kolab.org/)) `GPL-2.0/LGPL-2.1/GPL-3.0` `C++/Python/PHP`
- [Kopano](https://kopano.com/) - Groupware suite including e-mail, calendars, tasks, todos and notes. Featuring a modern WebApp, DeskApp and mobile access over Z-Push/ActiveSync. ([Demo](https://demo.kopano.com), [源码](https://stash.kopano.io)) `AGPL-3.0` `C/Python/PHP`
- [Openmeetings](https://openmeetings.apache.org/index.html) - Openmeetings provides video conferencing, instant messaging, white board, collaborative document editing and other groupware tools using API functions of the Red5 Streaming Server for Remoting and Streaming. ([源码](https://openmeetings.apache.org/scm.html)) `Apache-2.0` `Java`
- [SOGo](https://sogo.nu/) - SOGo offers multiple ways to access the calendaring and messaging data. CalDAV, CardDAV, GroupDAV, as well as ActiveSync, including native Outlook compatibility and Web interface. ([Demo](https://demo.sogo.nu/SOGo/), [源码](https://github.com/inverse-inc/sogo)) `LGPL-2.1` `Objective-C`
- [SuiteCRM](https://suitecrm.com) - The award-winning, enterprise-class open source CRM. ([源码](https://github.com/salesagility/SuiteCRM)) `AGPL-3.0` `PHP`
- [Tine 2.0](https://www.tine20.org) - Contacts, Calendar, Tasks, WebDAV, ActiveSync, VOIP, Mail-Client, CRM, Sales, Projects, Timetracker. ([Demo](https://demo.tine20.net), [源码](https://packages.tine20.com/maintenance/source/)) `AGPL-3.0/Other` `PHP`
- [Tracim](https://github.com/tracim/tracim) - Collaborative Platform for team collaboration: file,threads,notes,agenda,etc. `AGPL-3.0/LGPL-3.0/MIT` `Python`
- [Zimbra Collaboration](https://www.zimbra.com/) - Email, calendar, collaboration server with Web interface and lots of integrations. ([源码](https://github.com/zimbra)) `GPL-2.0/CPAL-1.0` `Java`


### Human Resources Management (HRM)

**[`^        返回顶部        ^`](#)**

- [admidio](https://www.admidio.org/) - Admidio is a free open source user management system for websites of organizations and groups. The system has a flexible role model so that it’s possible to reflect the structure and permissions of your organization. ([Demo](https://www.admidio.org/demo/), [源码](https://github.com/Admidio/admidio)) `GPL-2.0` `PHP`
- [IceHrm](https://icehrm.com/) - IceHrm employee management system allows companies to centralize confidential employee information. ([Demo](https://icehrm.com/demo.php), [源码](https://github.com/gamonoid/icehrm)) `Apache-2.0` `PHP`
- [OrangeHRM](https://www.orangehrm.com/) - OrangeHRM is a comprehensive HRM system that captures all the essential functionalities required for any enterprise. ([源码](https://sourceforge.net/projects/orangehrm/)) `GPL-2.0` `PHP`
- [Sentrifugo](http://www.sentrifugo.com/) - Sentrifugo is a HRM system that can be easily configured to meet your organizational needs. ([源码](https://github.com/sapplica/sentrifugo)) `GPL-3.0` `PHP`
- [TimeOff.Management](https://timeoff.management) - Simple yet powerful absence management software for small and medium size business. ([Demo](https://app.timeoff.management), [源码](https://github.com/timeoff-management/timeoff-management-application)) `MIT` `Nodejs`


### Internet of Things (IoT)

**[`^        返回顶部        ^`](#)**

- [DeviceHive](https://www.devicehive.com/) - Open Source IoT Platform with a wide range of integration options. ([Demo](https://playground.devicehive.com/), [源码](https://github.com/devicehive/devicehive-java-server)) `Apache-2.0` `Java`
- [Domoticz](https://www.domoticz.com/) - Home Automation System that lets you monitor and configure various devices like: Lights, Switches, various sensors/meters like Temperature, Rain, Wind, UV, Electra, Gas, Water and much more. ([源码](https://github.com/domoticz/domoticz), [Clients](https://github.com/domoticz/domoticz-android)) `GPL-3.0` `C/C++`
- [FHEM](https://fhem.de/fhem.html) - FHEM is used to automate common tasks in the household like switching lamps and heating. It can also be used to log events like temperature or power consumption. You can control it via web or smartphone frontends, telnet or TCP/IP directly. ([源码](https://svn.fhem.de/trac)) `GPL-3.0` `Perl`
- [Gladys](https://gladysassistant.com/) - Gladys is a privacy-first, open-source home assistant. ([源码](https://github.com/GladysAssistant/Gladys)) `Apache-2.0` `Nodejs`
- [Home Assistant](https://home-assistant.io/) - Open-source home automation platform. ([Demo](https://home-assistant.io/demo/), [源码](https://github.com/home-assistant/core)) `Apache-2.0` `Python`
- [Node RED](https://nodered.org/) - Browser-based flow editor that helps you wiring hardware devices, APIs and online services to create IoT solutions. ([源码](https://github.com/node-red/node-red)) `Apache-2.0` `Nodejs`
- [openHAB](https://www.openhab.org) - Vendor and technology agnostic open source software for home automation. ([源码](https://github.com/openhab/openhab-core)) `EPL-2.0` `Java`
- [OpenRemote](https://openremote.io) - 100% Open Source IoT Platform - IoT Asset management, Flow Rules and WHEN-THEN rules, Data visualization, Edge Gateway. ([Demo](https://demo.openremote.io/), [源码](https://github.com/openremote/openremote)) `AGPL-3.0` `Java`
- [Thingsboard](https://thingsboard.io/) - Open-source IoT Platform - Device management, data collection, processing and visualization. ([Demo](https://demo.thingsboard.io/signup), [源码](https://github.com/thingsboard/thingsboard)) `Apache-2.0` `Java`
- [Thingspeak](https://thingspeak.com/) - Open source “Internet of Things” application and API to store and retrieve data from things using HTTP. ([Demo](https://thingspeak.com/channels/public), [源码](https://github.com/iobridge/thingspeak)) `GPL-3.0` `Ruby`
- [WebThings Gateway](https://webthings.io/gateway/) - WebThings is an open source implementation of the Web of Things, including the WebThings Gateway and the WebThings Framework. ([源码](https://github.com/WebThingsIO/gateway)) `MPL-2.0` `Nodejs`


### Knowledge Management Tools

**[`^        返回顶部        ^`](#)**

- [Mindmaps](https://github.com/drichard/mindmaps) - Open source, offline capable, mind mapping application. ([Demo](https://www.mindmaps.app)) `AGPL-3.0` `HTML5`
- [My Mind](https://github.com/ondras/my-mind) - Web application for creating and managing mind maps. ([Demo](https://my-mind.github.io/?url=examples%2Ffeatures.mymind)) `MIT` `Javascript`
- [Weaviate](https://github.com/semi-technologies/weaviate) - A cloud-native, realtime vector search engine integrating scalable machine learning models (GraphQL and RESTful APIs). ([Demo](https://www.semi.technology/documentation/weaviate/current/)) `BSD-3-Clause` `Go`


### Learning and Courses

**[`^        返回顶部        ^`](#)**

- [Canvas LMS](https://www.canvaslms.com/) - Canvas is the trusted, open-source learning management system (LMS) that is revolutionizing the way we educate. ([Demo](https://canvas.instructure.com/register), [源码](https://github.com/instructure/canvas-lms)) `AGPL-3.0` `Ruby`
- [Chamilo LMS](https://chamilo.org/) - Chamilo LMS allows you to create a virtual campus for the provision of online or semi-online training. ([源码](https://github.com/chamilo/chamilo-lms)) `GPL-3.0` `PHP`
- [edX](https://www.edx.org/) - The Open edX platform is open-source code that powers edX.org. ([源码](https://github.com/edx/)) `AGPL-3.0` `Python`
- [Gibbon](https://www.gibbonedu.org/) - The flexible, open source school management platform designed to make life better for teachers, students, parents and leaders. ([源码](https://github.com/GibbonEdu/core)) `GPL-3.0` `PHP`
- [ILIAS](https://www.ilias.de) - ILIAS is the Learning Management System that can cope with anything you throw at it. ([Demo](https://demo.ilias.de), [源码](https://github.com/ILIAS-eLearning/ILIAS)) `GPL-3.0` `PHP`
- [Mahara](https://mahara.org/) - Open Source fully featured web application to build students electronic portfolio. ([源码](https://github.com/MaharaProject/mahara)) `GPL-3.0` `PHP`
- [Moodle](https://moodle.org/) - Moodle is a learning and courses platform with one of the largest open source communities worldwide. ([Demo](https://moodle.org/demo/), [源码](https://git.moodle.org/gw)) `GPL-3.0` `PHP`
- [Open eClass](https://www.openeclass.org/) - Open eClass is an advanced e-learning solution that can enhance the teaching and learning process. ([Demo](https://demo.openeclass.org/), [源码](https://github.com/gunet/openeclass)) `GPL-2.0` `PHP`
- [OpenOLAT](https://www.openolat.com/?lang=en) - OpenOLAT is a web-based learning management system for teaching, education, assessment and communication. ([Demo](https://learn.olat.com), [源码](https://github.com/OpenOLAT/OpenOLAT)) `Apache-2.0` `Java`
- [RELATE](https://documen.tician.de/relate/) - RELATE is a web-based courseware package, includes features such as: flexible rules, statistics, multi-course support, class calendar. ([源码](https://github.com/inducer/relate)) `MIT` `Python`
- [RosarioSIS](https://www.rosariosis.org/) - RosarioSIS, free Student Information System for school management. ([Demo](https://www.rosariosis.org/demo/), [源码](https://gitlab.com/francoisjacquet/rosariosis/)) `GPL-2.0` `PHP`
- [Sakai](https://www.sakaiproject.org/) - The Sakai project provides a flexible and feature-rich environment for teaching, learning, research and other collaboration. ([Demo](https://www.sakaiproject.org/try-sakai), [源码](https://github.com/sakaiproject/sakai)) `ECL-2.0` `Java`


### Maps and Global Positioning System (GPS)

**[`^        返回顶部        ^`](#)**

_See also: [awesome-gis](https://github.com/sshuair/awesome-gis)_

- [Geo2tz](https://github.com/noandrea/geo2tz) - Get the timezone from geo coordinates (lat, lon). `MIT` `Go/Docker`
- [GraphHopper](https://graphhopper.com/) - Fast routing library and server using OpenStreetMap. ([源码](https://github.com/graphhopper/graphhopper)) `Apache-2.0` `Java`
- [Hauk](https://github.com/bilde2910/Hauk) - Easy to setup location sharing platform that lets you temporarily share your location with anyone in real-time. ([Demo](https://github.com/bilde2910/Hauk#demo-server)) `Apache-2.0` `PHP`
- [MapBBCodeShare](https://github.com/MapBBCode/share.mapbbcode.org) - Tool for sharing custom OSM maps. Support for annotated markers, polygons, lines, multi-format import/export, multiple layers, shortlinks. ([Demo](http://share.mapbbcode.org/)) `WTFPL/Other` `PHP`
- [Nominatim](https://nominatim.org/) - Server application for reverse geocoding (address -> coordinates) on OpenStreetMap data. ([源码](https://github.com/osm-search/Nominatim)) `GPL-2.0` `C`
- [Open Source Routing Machine (OSRM)](http://project-osrm.org/) - High performance routing engine designed to run on OpenStreetMap data and offering an HTTP API, C++ library interface, and Nodejs wrapper. ([Demo](https://map.project-osrm.org/), [源码](https://github.com/Project-OSRM/osrm-backend)) `BSD-2-Clause` `C++`
- [OpenGTS](http://www.opengts.org/) - Entry-level fleet tracking system. Supports variety of tracking devices and protocols. Comes with rich web-interface and reporting features. ([Demo](http://track.opengts.org/track/Track), [源码](https://sourceforge.net/projects/opengts/files/server-base/)) `Apache-2.0` `Java`
- [OpenStreetMap](https://www.openstreetmap.org/) - Collaborative project to create a free editable map of the world. ([源码](https://github.com/openstreetmap/openstreetmap-website), [Clients](https://wiki.openstreetmap.org/wiki/Software)) `GPL-2.0` `Ruby`
- [OpenTripPlanner](https://www.opentripplanner.org/) - Multimodal trip planning software based on OpenStreetMap data and consuming published GTFS-formatted data to suggest routes using local public transit systems. ([源码](https://github.com/opentripplanner/OpenTripPlanner)) `LGPL-3.0` `Java/Javascript`
- [Orion](https://github.com/LINKIWI/orion-web) - Powerful OwnTracks API-compliant location data visualization frontend for the web. ([Demo](https://linkiwi.github.io/orion-web/)) `MIT` `Python/Nodejs`
- [OwnTracks Recorder](https://github.com/owntracks/recorder) `⚠` - Store and access data published by [OwnTracks](https://owntracks.org/) location tracking apps. `GPL-2.0` `C/Lua`
- [TileServer GL](https://tileserver.readthedocs.io/) - Vector and raster maps with GL styles. Server side rendering by Mapbox GL Native. Map tile server for Mapbox GL JS, Android, iOS, Leaflet, OpenLayers, GIS via WMTS, etc. ([源码](https://github.com/maptiler/tileserver-gl)) `BSD-2-Clause` `Nodejs`
- [TileServer PHP](https://www.maptiler.com/server/) - Serve map tiles from any PHP hosting. ([源码](https://github.com/maptiler/tileserver-php)) `BSD-2-Clause` `PHP`
- [Traccar](https://www.traccar.org/) - Java application to track GPS positions. Supports loads of tracking devices and protocols, has an Android and iOS App. Has a web interface to view your trips. ([Demo](https://demo.traccar.org/), [源码](https://github.com/traccar)) `Apache-2.0` `Java`
- [uMap](https://umap.openstreetmap.fr/en/) - Create maps with OpenStreetMap layers in a minute and embed them in your site. ([源码](https://github.com/umap-project/umap)) `WTFPL` `Python`
- [μlogger](https://github.com/bfabiszewski/ulogger-server) - Collect geolocation from users in real-time and display their GPS tracks on a website. ([Demo](http://ulogger.fabiszewski.net/)) `GPL-3.0` `PHP`


### Media Streaming

**[`^        返回顶部        ^`](#)**

**请访问 [Media streaming - Audio Streaming](#media-streaming---audio-streaming), [Media streaming - Multimedia Streaming](#media-streaming---mutimedia-streaming), [Media streaming - Video Streaming](#media-streaming---video-streaming)**

_See also: [List of streaming media systems - Wikipedia](https://en.wikipedia.org/wiki/List_of_streaming_media_systems), [Comparison of streaming media systems - Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_streaming_media_systems)_


### Media Streaming - Audio Streaming

**[`^        返回顶部        ^`](#)**

- [Airsonic](https://airsonic.github.io/) - Open-source web-based media streamer and jukebox. A fork of Subsonic's last open-source release, before it switched licenses. ([源码](https://github.com/airsonic/airsonic), [Clients](https://airsonic.github.io/docs/apps/)) `GPL-3.0` `Java`
- [Ampache](https://ampache.org/) - Web based audio/video streaming application. ([Demo](https://play.dogmazic.net/), [源码](https://github.com/ampache/ampache)) `AGPL-3.0` `PHP`
- [Audioserve](https://github.com/izderadicka/audioserve) - Simple personal server to serve audio files from directories (audiobooks, music, podcasts...). Focused on simplicity and supports sync of play position between clients. `MIT` `Rust`
- [AzuraCast](https://www.azuracast.com/) - A modern and accessible self-hosted web radio management suite. ([源码](https://github.com/AzuraCast/AzuraCast)) `Apache-2.0` `PHP`
- [Beets](https://beets.io/) - Music library manager and MusicBrainz tagger (command-line and Web interface). ([源码](https://github.com/beetbox/beets)) `MIT` `Python`
- [Black Candy](https://github.com/aidewoode/black_candy) - Music streaming server built with Rails and Stimulus. `MIT` `Ruby`
- [Compactd](https://github.com/compactd/compactd) - Remote music player that supports adding content. `MIT` `Nodejs`
- [euterpe](https://listen-to-euterpe.eu) - Self-hosted music streaming server with RESTful API and Web interface. ([Demo](https://listen-to-euterpe.eu/demo), [源码](https://github.com/ironsmile/euterpe)) `GPL-3.0` `Go`
- [FriendsRadio](https://github.com/xouabita/friends-radio) `⚠` - Share music with your friends from Youtube and Soundcloud. ([Demo](https://friends-radio.herokuapp.com/)) `MIT` `Nodejs`
- [Funkwhale](https://funkwhale.audio/) - Modern, web-based, convivial, multi-user and free music server. ([Demo](https://demo.funkwhale.audio/), [源码](https://code.eliotberriot.com/funkwhale/funkwhale)) `BSD-3-Clause` `Python/Django`
- [GNU FM](https://gnu.io/fm/) - Running music community websites, alternative to last.fm. ([源码](https://git.savannah.gnu.org/cgit/librefm.git/)) `AGPL-3.0` `PHP`
- [gonic](https://github.com/sentriz/gonic) - Lightweight music streaming server. Subsonic compatible. `GPL-3.0` `Go`
- [Groove Basin](https://github.com/andrewrk/groovebasin) - Music player server with a web-based user interface inspired by Amarok 1.4. `MIT` `Nodejs`
- [koel](https://koel.dev/) - Personal music streaming server that works. ([源码](https://github.com/koel/koel)) `MIT` `PHP`
- [KooZic](https://koozic.net/) - Music server with powerful playlist features and Subsonic compatibility. ([Demo](https://demo.koozic.net/public), [源码](https://github.com/DocMarty84/koozic)) `LGPL-3.0/MIT` `Python`
- [LibreTime](https://libretime.org) - Simple, open source platform that lets you broadcast streaming radio on the web (fork of [Airtime](https://github.com/sourcefabric/Airtime)). ([源码](https://github.com/LibreTime/libretime)) `AGPL-3.0` `PHP`
- [LMS](https://github.com/epoupon/lms) - Access your self-hosted music using a web interface. ([Demo](https://lms.demo.poupon.io/)) `GPL-3.0` `C++`
- [moOde Audio](https://moodeaudio.org/) - Audiophile-quality music playback for the wonderful Raspberry Pi family of single board computers. ([源码](https://github.com/moode-player/moode)) `GPL-3.0` `PHP`
- [Moped](https://github.com/martijnboland/moped) - Responsive HTML5 + Javascript client for the Mopidy music server. `MIT` `HTML5`
- [Mopidy MusicBox](https://github.com/pimusicbox/mopidy-musicbox-webclient) - Web Client for Mopidy Music Server. `Apache-2.0` `HTML5`
- [Mopidy-Party](https://github.com/Lesterpig/mopidy-party) - Mopidy web extension designed for party! Let your guests manage the sound. `Apache-2.0` `Python`
- [Mopidy](https://docs.mopidy.com/) - Extensible music server. Offers a superset of the mpd API, as well as integration with 3rd party services like Spotify, SoundCloud etc. ([源码](https://github.com/mopidy/mopidy)) `Apache-2.0` `Python`
- [mpd](https://www.musicpd.org/) - Daemon to remotely play music, stream music, handle and organize playlists. Many clients available. ([源码](https://github.com/MusicPlayerDaemon/MPD), [Clients](https://www.musicpd.org/clients/)) `GPL-2.0` `C++`
- [mStream](https://mstream.io/) - Music streaming server with GUI management tools. Runs on Mac, Windows, and Linux. ([源码](https://github.com/IrosTheBeggar/mStream)) `GPL-2.0` `Nodejs`
- [musikcube](https://musikcube.com/) - Streaming audio server with Linux/macOS/Windows/Android clients. ([源码](https://github.com/clangen/musikcube)) `BSD-3-Clause` `C++`
- [Navidrome Music Server](https://www.navidrome.org) - Modern Music Server and Streamer, compatible with Subsonic/Airsonic. ([Demo](https://www.navidrome.org/demo), [源码](https://github.com/navidrome/navidrome), [Clients](https://www.navidrome.org/docs/overview/#apps)) `GPL-3.0` `Go/Javascript`
- [Polaris](https://github.com/agersant/polaris) - Music browsing and streaming application optimized for large music collections, ease of use and high performance. `MIT` `Rust`
- [Raveberry](https://github.com/raveberry/raveberry) - A multi-user music server with a focus on participation. ([Demo](https://demo.raveberry.party/)) `LGPL-3.0` `Python`
- [Snapcast](https://github.com/badaix/snapcast) - Synchronous multiroom audio server. `GPL-3.0` `C++`
- [Stretto](https://github.com/benkaiser/stretto) - Music player with Youtube/Soundcloud import and iTunes/Spotify discovery. ([Demo](https://next.kaiserapps.com), [Clients](https://github.com/benkaiser/stretto-mobile-next)) `MIT` `Nodejs`
- [Volumio](https://volumio.org/) - A free and open source linux distribution, designed and fine-tuned exclusively for music playback. ([源码](https://github.com/volumio/Volumio2)) `GPL-3.0` `Nodejs`
- [ympd](https://www.ympd.org/) - Standalone MPD Web GUI written in C, utilizing Websockets and Bootstrap/JS. ([源码](https://github.com/notandy/ympd)) `GPL-2.0` `C`


### Media Streaming - Multimedia Streaming

**[`^        返回顶部        ^`](#)**

- [Gerbera](https://gerbera.io/) - Gerbera is an UPnP Media Server. It allows you to stream your digital media throughout your home network and listen to/watch it on a variety of UPnP compatible devices. ([源码](https://github.com/gerbera/gerbera)) `GPL-2.0` `C++`
- [homehost](https://github.com/ridhwaans/homehost) `⚠` - Self-hosted React + Redux app that streams your media collection (music, movies, books, podcasts, comics etc). `MIT` `Nodejs`
- [Icecast 2](https://icecast.org) - streaming audio/video server which can be used to create an Internet radio station or a privately running jukebox and many things in between. ([源码](https://gitlab.xiph.org/xiph/icecast-server), [Clients](https://icecast.org/apps/)) `GPL-2.0` `C`
- [Jellyfin](https://jellyfin.org) - Media server for audio, video, books, comics, and photos with a sleek interface and robust transcoding capabilities. Almost all modern platforms have clients, including Roku, Android TV, iOS, and Kodi. ([Demo](https://demo.jellyfin.org/stable), [源码](https://github.com/jellyfin/jellyfin)) `GPL-2.0` `C#`
- [Karaoke Forever](https://www.karaoke-forever.com) - Host awesome karaoke parties where everyone can easily find and queue songs from their phone's web browser. The player is also browser-based with support for MP3+G, MP4 and WebGL visualizations. ([源码](https://www.karaoke-forever.com/repo)) `ISC` `Nodejs`
- [LBRY](https://lbry.com/) - Is a secure, open, and community-run digital marketplace that aims to replace Youtube and Amazon. ([Demo](https://lbry.tv/), [源码](https://github.com/lbryio/lbry.com), [Clients](https://github.com/lbryio/lbry-desktop)) `MIT` `PHP`
- [MistServer](https://mistserver.org/) - Streaming media server that works well in any streaming environment. ([源码](https://github.com/DDVTECH/mistserver)) `AGPL-3.0` `C++`
- [NymphCast](http://nyanko.ws/nymphcast.php) - NymphCast is a Chromecast alternative which turns your choice of Linux-capable hardware into an audio and video source for a television or powered speakers. ([源码](https://github.com/MayaPosch/NymphCast)) `BSD-3-Clause` `C++`
- [Podify](https://www.podify.org/) - Allows you to download videos and audio from any source supported by youtube-dl and subscribe to and watch these downloads using your favorite podcast app. ([源码](https://github.com/podify-org/podify/)) `GPL-3.0` `Ruby`
- [ReadyMedia](https://sourceforge.net/projects/minidlna/) - Simple media server software, with the aim of being fully compliant with DLNA/UPnP-AV clients. Formerly known as MiniDLNA. ([源码](https://sourceforge.net/p/minidlna/git/ci/master/tree/)) `GPL-2.0` `C`
- [Rygel](https://wiki.gnome.org/action/show/Projects/Rygel) - Rygel is a UPnP AV MediaServer that allows you to easily share audio, video, and pictures. Media player software may use Rygel to become a MediaRenderer that may be controlled remotely by a UPnP or DLNA Controller. ([源码](https://gitlab.gnome.org/GNOME/rygel/)) `GPL-3.0` `C`
- [SheetAble](https://sheetable.net) - Self-hosted music sheet organizing software for all music enthusiasts. Upload and organize your sheets for any kind of instrument. ([源码](https://github.com/SheetAble/SheetAble)) `AGPL-3.0` `Go`
- [Stash](https://stashapp.cc) - A web-based library organizer and player for your adult media stash, with auto-tagging and metadata scraping support. ([源码](https://github.com/stashapp/stash)) `AGPL-3.0` `Go`
- [üWave](https://u-wave.net/) `⚠` - üWave is a self-hosted collaborative listening platform. Users take turns playing media—songs, talks, gameplay videos, or anything else—from a variety of media sources like YouTube and SoundCloud. ([Demo](https://wlk.yt/), [源码](https://github.com/u-wave)) `MIT` `Nodejs`


### Media Streaming - Video Streaming

**[`^        返回顶部        ^`](#)**

- [Bluecherry](https://www.bluecherrydvr.com/) - Closed-circuit television (CCTV) software application which supports IP and Analog cameras. ([源码](https://github.com/bluecherrydvr/bluecherry-apps)) `GPL-2.0` `PHP`
- [CyTube](https://github.com/calzoneman/sync) - CyTube is a web application providing media synchronization, chat, and more for an arbitrary number of channels. ([Demo](https://cytu.be)) `MIT` `Nodejs`
- [Hellowlol HTPC Manager fork](https://github.com/Hellowlol/HTPC-Manager) - Fully responsive interface to manage all your favorite media on your HTPC. `MIT` `Python`
- [Invidious](https://github.com/iv-org/invidious) - `⚠` Invidious is an alternative front-end to YouTube. ([Demo](https://docs.invidious.io/Invidious-Instances.md)) `AGPL-3.0` `Crystal`
- [Kerberos.io](https://kerberos.io) - Kerberos.io is a video surveillance solution, which works with any camera and on every Linux based machine (Raspberry Pi, Docker, Kubernetes cluster). ([Demo](https://demo.kerberos.io/), [源码](https://github.com/kerberos-io/kerberos-docker)) `MIT` `C++`
- [MediaCMS](https://mediacms.io) - MediaCMS is a modern, fully featured open source video and media CMS, written in Python/Django/React, featuring a REST API. ([源码](https://github.com/mediacms-io/mediacms)) `AGPL-3.0` `Python/Docker`
- [Myflix](https://github.com/farfalleflickan/Myflix) `⚠` - Self-hosted, super lightweight Netflix alternative. `MIT` `Shell`
- [Oblecto](https://github.com/robinp7720/Oblecto) `⚠` - Media server for Movies and TV Shows with a responsive Vue.js frontend. It has robust transcoding support as well as federation capabilities to share your library with your friends. `AGPL-3.0` `Nodejs`
- [Oddworks](https://gitlab.com/oddnetworks/oddworks/core) - Oddworks is an open source video distribution platform built to destroy the barriers to streaming television with SDKs for Roku, Apple iOS/tvOS, Google Android, and Amazon FireTV. `MIT` `Nodejs`
- [Olaris](https://gitlab.com/olaris/olaris-server) - Olaris is an open-source, community driven, media manager and transcoding server. `GPL-3.0` `Go`
- [Open Streaming Platform](https://openstreamingplatform.com) - Self-Hosted alternative to Twitch and Youtube Live for live and on-demand video streaming. ([源码](https://gitlab.com/Deamos/flask-nginx-rtmp-manager)) `MIT` `Python`
- [OvenMediaEngine](https://ovenmediaengine.com) - OvenMediaEngine is a selfhostable Open-Source Streaming Server with Sub-Second Latency. ([Demo](https://demo.ovenplayer.com), [源码](https://github.com/AirenSoft/OvenMediaEngine)) `GPL-3.0` `C++`
- [Owncast](https://github.com/owncast/owncast) - Owncast is an open source, self-hosted, decentralized, single user live video streaming and chat server for running your own live streams similar in style to the large mainstream options. `MIT` `Go`
- [PeerTube](https://joinpeertube.org/en/) - Decentralized video streaming platform using P2P (BitTorrent) directly in the web browser. ([源码](https://github.com/Chocobozzz/PeerTube)) `AGPL-3.0` `Nodejs`
- [Radium](https://github.com/Zibbp/Radium) - Synced stream and video playback with VOD capabilities utilizing HLS. Developed for movie nights but has many use cases. ([Demo](https://radium-demo.herokuapp.com)) `MIT` `Nodejs/Docker`
- [Rapidbay](https://github.com/hauxir/rapidbay/) - Self-hosted torrent videostreaming service/torrent client that allows searching and playing videos from torrents in the browser or from a Chromecast/AppleTV/Smart TV. `MIT` `Python/Docker`
- [Restreamer](https://datarhei.github.io/restreamer/) - Restreamer allows you to do h.264 real-time video streaming on your website without a streaming provider. ([源码](https://github.com/datarhei/restreamer)) `Apache-2.0` `Nodejs/Docker`
- [ShinobiCE](https://gitlab.com/Shinobi-Systems/ShinobiCE) - Open Source CCTV software written in Node with both IP and local camera support. `AGPL-3.0/GPL-3.0` `Nodejs`
- [Streama](https://github.com/streamaserver/streama) - Self hosted streaming media server. `MIT` `Java`
- [SyncTube](https://github.com/RblSb/SyncTube) - Lightweight and very simple to setup CyTube alternative to watch videos with friends and chat. ([Demo](https://synctube-example.herokuapp.com/)) `MIT` `Nodejs/Haxe`
- [Tube](https://prologic.github.io/tube) - a Youtube-like (_without censorship and features you don't need!_) Video Sharing App written in Go which also supports automatic transcoding to MP4 H.265 AAC, multiple collections and RSS feed. ([Demo](https://tube.mills.io), [源码](https://git.mills.io/prologic/tube)) `MIT` `Go`
- [VideoLAN Client (VLC)](https://www.videolan.org/) - Cross-platform multimedia player client and server supporting most multimedia files as well as DVDs, Audio CDs, VCDs, and various streaming protocols. ([源码](https://github.com/videolan/vlc)) `GPL-2.0` `C`
- [Zoneminder](https://www.zoneminder.com/) - Closed-circuit television (CCTV) software application which supports IP, USB and Analog cameras. ([源码](https://github.com/ZoneMinder/ZoneMinder)) `GPL-2.0` `PHP`


### Miscellaneous

**[`^        返回顶部        ^`](#)**

- [2FAuth](https://github.com/Bubka/2FAuth) - A web app to manage your Two-Factor Authentication (2FA) accounts and generate their security codes. ([Demo](https://demo.2fauth.app/)) `AGPL-3.0` `PHP`
- [411](https://github.com/etsy/411) - Alert Management Web Application. `MIT` `PHP`
- [AlertHub](https://github.com/Ardakilic/alerthub) `⚠` - AlertHub is a simple tool to get alerted from GitHub releases. `MIT` `Nodejs`
- [Anchr](https://anchr.io) - Anchr is a toolbox for tiny tasks on the internet, including bookmark collections, URL shortening and (encrypted) image uploads. ([源码](https://github.com/muety/anchr)) `GPL-3.0` `Nodejs`
- [Anuko](https://www.anuko.com/time_tracker/index.htm) - Anuko provides simple time and project tracking on a selfhosted basis. ([Demo](https://timetracker.anuko.com/), [源码](https://github.com/anuko/timetracker)) `Other` `PHP`
- [asciiflow](https://asciiflow.com/) - Flow Diagram Drawing Tool. ([源码](https://github.com/lewish/asciiflow)) `MIT` `Nodejs`
- [Cachet](https://cachethq.io/) - An open source status page system for everyone. ([Demo](https://demo.cachethq.io/), [源码](https://github.com/CachetHQ/Cachet)) `BSD-3-Clause` `PHP`
- [CapRover](https://caprover.com/) - Build your own PaaS in a few minutes. ([Demo](https://captain.server.demo.caprover.com/#/login), [源码](https://github.com/caprover/caprover)) `Apache-2.0` `Docker/Nodejs`
- [changedetection.io](https://github.com/dgtlmoon/changedetection.io) - Self-hosted tool for staying up-to-date with web-site content changes. `Apache-2.0` `Python/Docker`
- [cState](https://github.com/cstate/cstate/) - Static status page for hyperfast Hugo. Clean design, minimal JS, super light HTML/CSS, high customization, optional admin panel, read-only API, IE8+. Best used with Netlify, Docker. ([Demo](https://cstate.mnts.lt/)) `MIT` `Go`
- [CUPS](https://www.cups.org/) - The Common Unix Print System uses Internet Printing Protocol (IPP) to support printing to local and network printers. ([源码](https://github.com/apple/cups)) `GPL-2.0` `C`
- [CyberChef](https://github.com/gchq/CyberChef) - Perform all manner of operations within a web browser such as AES, DES and Blowfish encryption and decryption, creating hexdumps, calculating hashes, and much more. ([Demo](https://gchq.github.io/CyberChef)) `Apache-2.0` `Javascript`
- [DailyTxT](https://github.com/PhiTux/DailyTxT) - Encrypted Diary Web-App to save your personal memories of each day. Includes a search-function and encrypted file-upload. `MIT` `Python`
- [Databunker](https://databunker.org/) - Network-based, self-hosted, GDPR compliant, secure database for personal data or PII. ([源码](https://github.com/securitybunker/databunker)) `MIT` `Go`
- [Digital-Currency](https://github.com/Icesofty/Digital-Currency) - Create your own Self-Hosted Digital Currency. ([Demo](https://tonken.glitch.me/)) `GPL-3.0` `Nodejs`
- [DomainMOD](https://domainmod.org) - Application to manage your domains and other internet assets in a central location. DomainMOD includes a Data Warehouse framework that allows you to import your WHM/cPanel web server data so that you can view, export, and report on your data. ([Demo](https://demo.domainmod.org), [源码](https://github.com/domainmod/domainmod)) `GPL-3.0` `PHP`
- [Flox](https://github.com/devfake/flox) `⚠` - Self hosted movie, TV series and anime watch list with a 3-point rating system. Uses The Movie Database backend for information. ([Demo](https://flox-demo.pyxl.dev/)) `MIT` `PHP`
- [formspree](https://formspree.io/) `⚠` - Just send your form to our URL and we'll forward it to your email. No PHP, Javascript or sign up required. ([Demo](https://test.formspree.io/), [源码](https://github.com/formspree/formspree)) `AGPL-3.0` `Python`
- [google-webfonts-helper](https://github.com/majodev/google-webfonts-helper) `⚠` - Hassle-Free Way to Self-Host Google Fonts. Get eot, ttf, svg, woff and woff2 files + CSS snippets. ([Demo](https://google-webfonts-helper.herokuapp.com/)) `MIT` `Nodejs`
- [graph-vl](https://github.com/verifid/graph-vl) - Identity document verification using Machine Learning and GraphQL. `MIT` `Python`
- [Journal](https://github.com/inoda/journal) - Simple journaling with encrypted entries and sharing capabilities. `MIT` `Ruby`
- [Kimai](https://www.kimai.org/) - Kimai is a free & open source timetracker. It tracks work time and prints out a summary of your activities on demand. ([Demo](https://www.kimai.org/demo/), [源码](https://github.com/kevinpapst/kimai2/)) `MIT` `PHP`
- [King Phisher](https://github.com/rsmusllp/king-phisher) - King Phisher is a tool for testing and promoting user awareness by simulating real world phishing attacks. `BSD-3-Clause` `Python`
- [Lancache](https://lancache.net) `⚠` - LAN Party game caching made easy. ([源码](https://github.com/lancachenet/monolithic)) `MIT` `Docker/Shell`
- [MailyGo](https://codeberg.org/jlelse/MailyGo) - MailyGo is a small tool written in Go that allows to send HTML forms, for example from static websites without a dynamic backend, via email. `MIT` `Go`
- [MindsDB](https://github.com/mindsdb/mindsdb) - MindsDB is an open source self hosted AI layer for existing databases that allows you to effortlessly develop, train and deploy state-of-the-art machine learning models using standard queries. `GPL-3.0` `Python`
- [MissionKontrol](https://www.missionkontrol.io) - Configurable admin panel allowing non-technical users to CRUD data on MySQL/PostGRES databases. ([源码](https://github.com/Mission-Kontrol/MissionKontrol-rails)) `AGPL-3.0` `Ruby`
- [Monica](https://monicahq.com/) - Personal relationship manager, and a new kind of CRM to organize interactions with your friends and family. ([源码](https://github.com/monicahq/monica)) `AGPL-3.0` `PHP`
- [Musical Artifacts](https://musical-artifacts.com/) - Helping to catalog, preserve and free the artifacts you need to produce music. ([源码](https://github.com/lfzawacki/musical-artifacts)) `MIT` `Ruby`
- [nnmm](https://github.com/Mechazawa/nnmm) - Super tiny pastebin/url minifier _microservice_. `Beerware` `PHP`
- [Notica](https://notica.us) - Lets you send browser notifications from your terminal to your desktop or phone. No installation or registration is required. ([源码](https://github.com/tannercollin/Notica)) `MIT` `Nodejs`
- [Ombi](https://ombi.io/) - A content request system for Plex/Emby, connects to SickRage, CouchPotato, Sonarr, with a growing feature set. ([Demo](https://app.ombi.io/), [源码](https://github.com/Ombi-app/Ombi)) `GPL-2.0` `C#`
- [Orchest](https://www.orchest.io/) - A new kind of IDE for Data Science. ([Demo](https://cloud.orchest.io), [源码](https://github.com/orchest/orchest)) `AGPL-3.0` `Docker`
- [oTranscribe](https://github.com/oTranscribe/oTranscribe) - Free web app to take the pain out of transcribing recorded interviews. ([Demo](https://otranscribe.com/)) `MIT` `Javascript`
- [PassCheck](https://apacketofsweets.github.io/PassCheck/) - A web application featuring some handy password tools, including a password generator, strength checker and HaveIBeenPwned breach checker. ([源码](https://github.com/apacketofsweets/PassCheck)) `MIT` `Javascript`
- [Reactive Resume](https://rxresu.me/) - A one-of-a-kind resume builder that keeps your privacy in mind. Completely secure, customizable, portable, open-source and free forever. ([Demo](https://rxresu.me/app/dashboard/), [源码](https://github.com/AmruthPillai/Reactive-Resume)) `MIT` `Docker/Nodejs`
- [ReleaseBell](https://releasebell.com/) - Send release notifications for starred Github repos. ([源码](https://git.cloudron.io/cloudron/releasebell)) `MIT` `Nodejs`
- [revealjs](https://revealjs.com) - Framework for easily creating beautiful presentations using HTML. ([Demo](https://revealjs.com/), [源码](https://github.com/hakimel/reveal.js)) `MIT` `Javascript`
- [Revive Adserver](https://www.revive-adserver.com/) - World's most popular free, open source ad serving system. Formerly known as OpenX Adserver and phpAdsNew. ([源码](https://github.com/revive-adserver/revive-adserver)) `GPL-2.0-or-later` `PHP`
- [s.Status](https://github.com/scolastico-dev/s.Status) - s.Status is a open source server status page written in java. ([Demo](https://status.scolasti.co/)) `MPL-2.0` `Java`
- [SANE Network Scanning](http://sane-project.org/) - Allow remote clients to access image acquisition devices (scanners) available on the local host. ([源码](http://www.sane-project.org/cvs.html)) `GPL-2.0` `C`
- [TeslaMate](https://github.com/adriankumpf/teslamate) - A powerful data logger for Tesla vehicles. `MIT` `Elixir`
- [Trello Burndown](https://github.com/mtricht/trello-burndown) `⚠` - Easy to use SCRUM burndown chart for Trello boards. `MIT` `Go/Docker`
- [ViMbAdmin](https://www.vimbadmin.net/) - Provides a web based virtual mailbox administration system to allow mail administrators to easily manage domains, mailboxes and aliases. ([Demo](https://www.vimbadmin.net/demo/auth/login), [源码](https://github.com/opensolutions/ViMbAdmin)) `GPL-3.0` `PHP`
- [Web fonts repository](https://github.com/Finesse/web-fonts-repository) - Simple webfont hosting. Google Fonts alternative for your own fonts. `MIT` `PHP`
- [ytdl-webserver](https://github.com/Algram/ytdl-webserver) - Docker-ready webserver for downloading youtube videos. `MIT` `Nodejs`


### Money, Budgeting & Management

**[`^        返回顶部        ^`](#)**

_See also: [awesome-sysadmin/IT Asset Management](https://github.com/awesome-foss/awesome-sysadmin#it-asset-management)_

- [Akaunting](https://akaunting.com/) - Akaunting is a free, online and open source accounting software designed for small businesses and freelancers. ([源码](https://github.com/akaunting/akaunting)) `GPL-3.0` `PHP`
- [Boodle](https://github.com/manuel-uberti/boodle) - Simple accounting single-page application in Clojure and ClojureScript. `EPL-1.0` `Java`
- [BTCPay Server](https://btcpayserver.org/) - A self-hosted Bitcoin and other cryptocurrencies payment processor. ([Demo](https://mainnet.demo.btcpayserver.org/), [源码](https://github.com/btcpayserver/)) `MIT` `C#`
- [Budget App](https://github.com/paukiatwee/budgetapp) - Budget App is an open source personal budgeting application. `Apache-2.0` `Java`
- [budgetzero](https://github.com/budgetzero/budgetzero) - Free, self-hosted, open-source, envelope-budgeting web and desktop app. ([Demo](https://app.budgetzero.io/budget)) `AGPL-3.0` `Nodejs`
- [Crater](https://github.com/bytefury/crater) - Free & Open Source Invoice App for Freelancers & Small Businesses. ([Demo](https://demo.craterapp.com/)) `AAL` `PHP`
- [Dot Ledger](https://www.dotledger.com/) - Web-based personal finance management tool. ([Demo](https://demo.dotledger.com/), [源码](https://github.com/dotledger/dotledger)) `Apache-2.0` `Ruby`
- [EasyQuickImport](https://github.com/karser/EasyQuickImport) `⚠` - A tool that helps you import transactions, invoices and bills into QuickBooks Desktop from Excel or CSV. `MIT` `PHP`
- [Economizzer](https://www.economizzer.org/) - An easy and secure system for you to manage your personal money and achieve your goals, and can be accessed by computer, tablet or smartphone. ([Demo](https://github.com/gugoan/economizzer#live-demo), [源码](https://github.com/gugoan/economizzer)) `MIT` `PHP`
- [ExMoney](https://github.com/gaynetdinov/ex_money) - Self-hosted personal finance app. `ISC` `Elixir`
- [Family Accounting Tool](https://github.com/nymanjens/facto) - Web-based finance management tool for partners with partially shared expenses. `Apache-2.0` `Scala`
- [Fava](https://beancount.github.io/fava/) - Fava is the web frontend of Beancount, a text based double-entry accounting system. ([Demo](https://fava.pythonanywhere.com/example-with-budgets/income_statement/), [源码](https://github.com/beancount/fava)) `MIT` `Python`
- [Firefly III](https://firefly-iii.org/) - Firefly III is a modern financial manager. It helps you to keep track of your money and make budget forecasts. It supports credit cards, has an advanced rule engine and can import data from many banks. ([Demo](https://demo.firefly-iii.org/), [源码](https://github.com/firefly-iii/firefly-iii)) `AGPL-3.0` `PHP`
- [Galette](https://galette.eu/dc/) - Galette is a membership management web application towards non profit organizations. ([源码](https://git.tuxfamily.org/galette/galette.git/)) `GPL-3.0` `PHP`
- [GRR](https://grr.devome.com/?lang=en) - Assets management and booking for small/medium companies. ([源码](https://github.com/JeromeDevome/GRR)) `GPL-2.0` `PHP`
- [Hospital Run](https://hospitalrun.io/) - Hospital Run is offline enabled hospital management software. ([Demo](https://hospitalrun.io/demo/), [源码](https://github.com/HospitalRun/hospitalrun-server)) `GPL-3.0` `Nodejs`
- [Hub20](https://hub20.io/) - A self-hosted payment processor for Ethereum and ERC20 Tokens. ([源码](https://gitlab.com/mushroomlabs/hub20/)) `AGPL-3.0` `Docker/Python`
- [IHateMoney](https://ihatemoney.org/) - Manage your shared expenses, easily. ([Demo](https://ihatemoney.org/demo/), [源码](https://github.com/spiral-project/ihatemoney)) `BSD-3-Clause` `Docker/Python`
- [IHateToBudget](https://github.com/bminusl/ihatetobudget) - A simple web app to understand and control your expenses. `GPL-3.0` `Docker/Python`
- [Inventaire](https://inventaire.io/welcome) - Collaborative resources mapper project, while yet only focused on exploring books mapping with wikidata and ISBNs. ([源码](https://github.com/inventaire/inventaire)) `AGPL-3.0` `Nodejs`
- [Inventree](https://inventree.readthedocs.io/en/latest/) - InvenTree is an open-source inventory management system which provides intuitive parts management and stock control. ([源码](https://github.com/inventree/InvenTree)) `MIT` `Python`
- [Invoice Ninja](https://www.invoiceninja.org/) - Powerful tool to invoice clients online. ([Demo](https://app.invoiceninja.com/invoices/create), [源码](https://github.com/invoiceninja/invoiceninja)) `AAL` `PHP`
- [InvoicePlane](https://github.com/InvoicePlane/InvoicePlane) - Manage quotes, invoices, payments and customers for your small business. `MIT` `PHP`
- [Kresus](https://kresus.org/) - Open source personal finance manager. ([Demo](https://kresus.org/en/demo.html), [源码](https://github.com/kresusapp/kresus)) `MIT` `Nodejs`
- [OnTrack](https://github.com/inoda/ontrack) - A simple app to track spend and set goals. `MIT` `Ruby/React`
- [PartKeepr](https://www.partkeepr.org) - PartKeepr is an electronic part inventory management software. It helps you to keep track of your available parts and assist you with re-ordering parts. ([Demo](https://demo.partkeepr.org/), [源码](https://github.com/partkeepr/PartKeepr)) `GPL-3.0` `PHP`
- [REI3](https://rei3.de/home_en/) - Open source, expandable Business Management Software. Manage tasks, time, assets and much more. ([Demo](https://rei3.de/demo_en/), [源码](https://github.com/r3-team/r3)) `MIT` `Go`
- [SilverStrike](https://silverstrike.org/) - Personal finance management made easy. ([Demo](https://demo.silverstrike.org/), [源码](https://github.com/agstrike/silverstrike)) `MIT` `Python/Django`
- [StockazNG](https://dev.sigpipe.me/dashie/StockazNG) - Asset Management System. `MIT` `Python`
- [Tabby](https://github.com/bertvandepoel/tabby) - A tool to manage shared expenses across friends, such as restaurant costs or food delivery, without requiring everyone to create an account. Includes email reminders and tracks who has (re)paid what. `AGPL-3.0-only` `PHP`


### Monitoring

**[`^        返回顶部        ^`](#)**

**请访问 [awesome-sysadmin/Monitoring](https://github.com/awesome-foss/awesome-sysadmin#monitoring), [awesome-sysadmin/Metric and Metric Collection](https://github.com/awesome-foss/awesome-sysadmin#metric--metric-collection)**


### Note-taking & Editors

**[`^        返回顶部        ^`](#)**

_关联: [Wikis](#wikis)_

- [BulletNotes](https://bulletnotes.io/) - Workflowy / Dynalist clone with Kanban (Trello) and Calendar functionality. Organize everything. ([源码](https://gitlab.com/NickBusey/BulletNotes)) `MIT` `Nodejs`
- [DailyNotes](https://github.com/m0ngr31/DailyNotes/) - App for taking notes and tracking tasks on a daily basis in Markdown. `MIT` `Python`
- [dillinger](https://dillinger.io/) - The last Markdown editor, ever. ([源码](https://github.com/joemccann/dillinger)) `MIT` `Nodejs`
- [Dnote](https://www.getdnote.com) - A simple command line notebook with multi-device sync and web interface. ([源码](https://github.com/dnote/dnote)) `AGPL-3.0` `Go`
- [DocPHT](https://docpht.org/) - With DocPHT you can take notes and quickly document anything and without the use of any database. ([Demo](https://demo.docpht.org/), [源码](https://github.com/docpht/docpht)) `MIT` `PHP`
- [draw.io](https://draw.io) - Diagram software for making flowcharts, process diagrams, org charts, UML, ER and network diagrams. ([源码](https://github.com/jgraph/drawio)) `Apache-2.0` `Javascript`
- [HedgeDoc](https://demo.hedgedoc.org/) - Realtime collaborative markdown notes on all platforms, formerly known as CodiMD and HackMD CE. ([源码](https://github.com/hedgedoc/hedgedoc)) `AGPL-3.0` `TypeScript`
- [Joplin](https://joplinapp.org/) - Joplin is a note taking application with Markdown editor and encryption support for mobile and desktop platforms. Runs client-side and syncs through self hosted Nextcloud or similar. Consider it like open source alternative to Evernote. ([源码](https://github.com/laurent22/joplin)) `MIT` `Nodejs`
- [Leanote](http://leanote.org/) - Leanote, Not Just A Notepad! Open source cloud notepad. ([Demo](https://leanote.com/note), [源码](https://github.com/leanote/leanote)) `GPL-2.0` `Go`
- [Markdown Edit](https://github.com/georgeOsdDev/markdown-edit/) - Online markdown editor/viewer. `MIT` `HTML5`
- [Meemo](https://meemo.minimal-space.de/) - Personal notes stream with Markdown support. ([源码](https://github.com/nebulade/meemo)) `MIT` `Nodejs`
- [minimalist-web-notepad](https://github.com/pereorga/minimalist-web-notepad) - Minimalist notepad.cc clone. ([Demo](https://notes.orga.cat/)) `Apache-2.0` `PHP`
- [MiniNote](https://github.com/muety/mininote) - Simple Markdown note-taking app with persistence. `MIT` `Nodejs`
- [Notea](https://cinwell.com/notea/) - Self-hosted note-taking app stored on S3-compatible storage. ([源码](https://github.com/QingWei-Li/notea)) `MIT` `Nodejs`
- [Notes'n'Todos](https://github.com/larspontoppidan/notesntodos) - Write notes and todos online in markdown with tag filtering and date sorting. ([Demo](https://lpss.dk/nnt-playground/)) `MIT` `Python`
- [Oddmuse](https://oddmuse.org/) - A simple wiki engine written in Perl. No database required. ([源码](https://github.com/kensanata/oddmuse)) `GPL-3.0` `Perl`
- [OpenNote](https://github.com/FoxUSA/OpenNote) - OpenNote was built to be an open web-based alternative to Microsoft OneNote (T) and EverNote. ([Demo](https://foxusa.github.io/OpenNote/OpenNote/#/folder)) `MIT` `HTML5`
- [Overleaf](https://www.overleaf.com/) - Web-based collaborative LaTeX editor. ([源码](https://github.com/overleaf/overleaf)) `AGPL-3.0` `Ruby`
- [Paperwork](https://paperwork.cloud) - OpenSource note-taking and archiving alternative to Evernote, Microsoft OneNote and Google Keep. ([源码](https://github.com/paperwork/paperwork)) `MIT` `PHP`
- [Plainpad](https://alextselegidis.com/get/plainpad/) - A modern note taking application for the cloud, utilizing the best features of progressive web apps technology. ([Demo](https://alextselegidis.com/try/plainpad/), [源码](https://github.com/alextselegidis/plainpad)) `GPL-3.0` `PHP`
- [savepad](https://github.com/shelltr/textpad) - Minimalist notepad based on notepad.cc. `MIT` `PHP`
- [Standard Notes](https://standardnotes.com) - Simple and private notes app. Protect your privacy while getting more done. That's Standard Notes. ([Demo](https://app.standardnotes.org/), [源码](https://github.com/standardnotes)) `GPL-3.0` `Ruby`
- [Trilium Notes](https://github.com/zadam/trilium) - Trilium Notes is a hierarchical note taking application with focus on building large personal knowledge bases. `AGPL-3.0` `Nodejs`
- [turndown](https://mixmark-io.github.io/turndown/) - HTML to Markdown converter written in Javascript. ([源码](https://github.com/mixmark-io/turndown)) `MIT` `Javascript`
- [Turtl](https://turtl.it/) - Totally private personal database and note taking app. ([源码](https://github.com/turtl)) `GPL-3.0` `CommonLisp`
- [Wreeto](https://wreeto.com) - Wreeto is an open source note-taking, knowledge management and wiki system built on top of Ruby on Rails framework. ([源码](https://github.com/chrisvel/wreeto_official)) `AGPL-3.0` `Ruby`
- [Writing](https://josephernest.github.io/writing/) - Lightweight distraction-free text editor, in the browser (Markdown and LaTeX supported). No lag when writing. ([源码](https://github.com/josephernest/writing)) `MIT` `Javascript`


### Office Suites

**[`^        返回顶部        ^`](#)**

- [Collabora Online Development Edition](https://www.collaboraoffice.com/code) - Collabora Online Development Edition (CODE) is a powerful LibreOffice-based online office that supports all major document, spreadsheet and presentation file formats, which you can integrate in your own infrastructure. ([源码](https://cgit.freedesktop.org/libreoffice/online/)) `MPL-2.0` `C++`
- [CryptPad](https://cryptpad.fr/) - CryptPad is the zero knowledge realtime collaborative editor (rich-text, files, source-code, ...). ([源码](https://github.com/xwiki-labs/cryptpad)) `AGPL-3.0` `Nodejs`
- [EtherCalc](https://ethercalc.net/) - Web spreadsheet. ([源码](https://github.com/audreyt/ethercalc)) `CPAL-1.0/Other` `Nodejs`
- [Etherpad](https://etherpad.org/) - Etherpad is a highly customizable Open Source online editor providing collaborative editing in really real-time. ([Demo](https://demo.sandstorm.io/appdemo/h37dm17aa89yrd8zuqpdn36p6zntumtv08fjpu8a8zrte7q1cn60), [源码](https://github.com/ether/etherpad-lite)) `Apache-2.0` `Nodejs`
- [Infinoted](https://github.com/gobby/gobby/wiki/Dedicated%20Server) - Server for [Gobby](https://github.com/gobby/gobby/wiki), a multi-platform collaborative text editor. ([源码](https://github.com/gobby/gobby)) `MIT` `C++`
- [ONLYOFFICE](https://helpcenter.onlyoffice.com/faq/server-opensource.aspx) - Office suite that enables you to manage documents, projects, team and customer relations in one place. ([源码](https://github.com/ONLYOFFICE/DocumentServer)) `AGPL-3.0` `Nodejs`
- [PHPOffice](https://github.com/PHPOffice) - PHPOffice contains libraries which permits to write and read files from most office suites. `LGPL-3.0` `PHP`
- [Rustpad](https://rustpad.io/) - Efficient and minimal collaborative code editor, self-hosted, no database required. ([源码](https://github.com/ekzhang/rustpad)) `MIT` `Rust`
- [WebODF](https://webodf.org/) - Tools and libraries to view and edit Open Document Format (ODF) files. ([源码](https://github.com/webodf/WebODF)) `AGPL-3.0` `HTML5`


### Password Managers

**[`^        返回顶部        ^`](#)**

- [Bitwarden](https://bitwarden.com/) `⚠` - Password manager with webapp, browser extension, and mobile app. ([源码](https://github.com/bitwarden/server)) `AGPL-3.0` `C#`
- [keeweb](https://keeweb.info/) - This webapp is a browser and desktop password manager compatible with KeePass databases. ([源码](https://github.com/keeweb/keeweb)) `MIT` `HTML5`
- [Padloc](https://padloc.app/) - A modern, open source password manager for individuals and teams. ([源码](https://github.com/padloc/padloc)) `GPL-3.0` `Nodejs`
- [Passbolt](https://www.passbolt.com/) - Password manager dedicated for managing passwords in a collaborative way on any Web server, using a MySQL database backend. ([源码](https://github.com/passbolt/passbolt_api)) `AGPL-3.0` `PHP`
- [PassIt](https://passit.io/) - Simple password manage with sharing features by group and user, but no administration interface. ([Demo](https://app.passit.io/), [源码](https://gitlab.com/passit)) `AGPL-3.0` `Python`
- [Passky](https://passky.org) - Simple, modern and open source password manager with website, browser extension, android and desktop application. ([Demo](https://vault.passky.org), [源码](https://github.com/Rabbit-Company/Passky-Server)) `GPL-3.0` `PHP`
- [PassWall](https://github.com/passwall/passwall-server) - Open source password manager. `AGPL-3.0` `Go`
- [Psono](https://psono.com/) - A promising password managers fully featured for teams. ([Demo](https://www.psono.pw), [源码](https://gitlab.com/psono)) `Apache-2.0` `Python`
- [Shaark](https://github.com/MarceauKa/shaark) - All in one platform for your links, stories, passwords and albums. Built with Laravel and Vue.js. `MIT` `PHP`
- [sysPass](https://www.syspass.org/) - Multiuser password management system. ([Demo](https://demo.syspass.org/), [源码](https://github.com/nuxsmin/sysPass)) `GPL-3.0` `PHP`
- [Teampass](https://teampass.net/) - Password manager dedicated for managing passwords in a collaborative way. One symmetric key is used to encrypt all shared/team passwords and stored server side in a file and the database. works on any server Apache, MySQL and PHP. ([源码](https://github.com/nilsteampassnet/TeamPass)) `GPL-3.0` `PHP`
- [vaults](https://github.com/MatrixEternal/vaults) - Password manager featuring client side AES-256 encryption, PBKDF2 hashing, vaults, password generation & more. `GPL-3.0` `PHP`
- [Vaultwarden](https://github.com/dani-garcia/vaultwarden) - Lightweight Bitwarden server API implementation written in Rust. `GPL-3.0` `Rust`


### Pastebins

**[`^        返回顶部        ^`](#)**

- [0bin](https://github.com/Tygs/0bin) - Client side encrypted pastebin. ([Demo](https://0bin.net/)) `WTFPL` `Python`
- [bepasty](https://bepasty-server.readthedocs.io/en/latest/) - A pastebin for all kinds of files. ([源码](https://github.com/bepasty/bepasty-server)) `BSD-2-Clause` `Python`
- [bin](https://github.com/w4/bin) - a paste bin. `WTFPL/0BSD` `Rust`
- [cryptonote](https://cryptonote.me/) - Simple open source web application that lets users encrypt and share messages that can only be read once. ([源码](https://github.com/alainmeier/cryptonote)) `MIT` `Ruby`
- [dogbin](https://github.com/dogbin/dogbin) - The sexiest pastebin and URL shortener ever. `MIT` `Kotlin`
- [dpaste](https://dpaste.org/) - simple pastebin with multiple text and code option, with short url result easy to remember. ([源码](https://github.com/bartTC/dpaste)) `MIT` `Docker`
- [EdPaste](https://github.com/eahlys/EdPaste) - Self-hosted pastebin written in Laravel (PHP Framework). `MIT` `PHP`
- [ExBin](https://github.com/m1dnight/exbin) - A pastebin with public/private snippets and netcat server. ([Demo](https://exbin.call-cc.be)) `MIT` `Elixir`
- [fiche](https://github.com/solusipse/fiche) - Command line pastebin, all you need is netcat. ([Demo](https://termbin.com/)) `MIT` `C`
- [filite](https://github.com/raftario/filite) - A simple, light and standalone pastebin, URL shortener and file-sharing service. ([Demo](https://filite.raphaeltheriault.com)) `MIT` `Rust`
- [FlashPaper](https://github.com/AndrewPaglusch/FlashPaper) - A one-time encrypted zero-knowledge password/secret sharing application focused on simplicity and security. No database or complicated set-up required. ([Demo](https://flashpaper.io)) `MIT` `PHP`
- [Fugacious](https://fugacio.us) - Open source short-term secure messaging (OSSSM). ([源码](https://github.com/fugacious/fugacious)) `CC0-1.0` `Ruby`
- [Hastebin](https://haste.zneix.eu/about.md) - Open source pastebin. (This is a fork with extended maintenance). ([Demo](https://haste.zneix.eu), [源码](https://github.com/zneix/haste-server)) `MIT` `Nodejs`
- [LogPaste](https://github.com/mtlynch/logpaste) - Minimal pastebin web app that's easy to self-host and persists data to any S3-compatible backend. ([Demo](https://logpaste.com/)) `MIT` `Go`
- [mkaczanowski pastebin](https://github.com/mkaczanowski/pastebin) - Simple, fast, feature-rich, standalone pastebin service. `MIT` `Rust`
- [mojopaste](https://metacpan.org/dist/App-mojopaste) - Perl based pastebin. ([Demo](https://p.thorsen.pm/), [源码](https://github.com/jhthorsen/app-mojopaste)) `Artistic-2.0` `Perl`
- [MokinToken](https://github.com/nexus-uw/mokintoken) - Clientside encrypted pastebin using tweetnacl. `Unlicense` `PHP`
- [NoteHub](https://github.com/chmllr/NoteHub) - Free and Hassle-free Pastebin for Markdown Pages. Simple, clean, password provided, generated-short link. `MIT` `Nodejs`
- [Paste](https://phpaste.sourceforge.io/) - Paste is forked from the original source pastebin.com used before it was bought. ([源码](https://github.com/jordansamuel/PASTE)) `GPL-3.0` `PHP`
- [pasty](https://github.com/lus/pasty) - Pasty is a fast and lightweight code pasting server. ([Demo](https://pasty.lus.pm/)) `MIT` `Go`
- [pb](https://github.com/ptpb/pb) - Lightweight pastebin (and url shortener) built using flask. `GPL-3.0` `Python`
- [PrivateBin](https://privatebin.info/) - PrivateBin is a minimalist, opensource online pastebin/discussion board where the server has zero knowledge of hosted data. ([Demo](https://privatebin.net/), [源码](https://github.com/PrivateBin/PrivateBin)) `Zlib` `PHP`
- [prologic pastebin](https://git.mills.io/prologic/pastebin) - Simple pastebin service with convenient api and CLI. ([Demo](https://paste.mills.io)) `MIT` `Go`
- [PurritoBin](https://github.com/PurritoBin/PurritoBin) - Ultra fast, minimalistic, encrypted command line paste-bin, where the server has no knowledge of the paste data. `ISC` `C++`
- [rustypaste](https://github.com/orhun/rustypaste) - A minimal file upload/pastebin service. `MIT` `Rust`
- [SharpPaste](https://github.com/phonicmouse/SharpPaste) - Cross-platform C# pastebin with client-side AES-256 encryption that just works. `MIT` `C#/NancyFX`
- [Snibox](https://snibox.github.io/) - Code snippets manager with attractive tag-oriented interface. ([Demo](https://snibox-demo.herokuapp.com/), [源码](https://github.com/snibox/snibox)) `MIT` `Ruby`
- [Snippet Box](https://github.com/pawelmalak/snippet-box) - Snippet Box is a simple self-hosted app for organizing your code snippets. It allows you to easily create, edit, browse and manage your snippets in various languages. `MIT` `Nodejs`
- [snipt](https://github.com/nicksergeant/snipt) - Long-term memory for coders. Share and store code snippets. `MIT` `Python`
- [SocksBin](https://github.com/magnumdingusedu/socksbin) - Simple and fast terminal based pastebin, with optional code highlighting. No specific client required, all you need is netcat. `GPL-3.0` `Python`
- [Spacebin](https://docs.spaceb.in) - Text-sharing for the final frontier — Reliable Pastebin server in Golang and Fiber. ([Demo](https://spaceb.in), [源码](https://github.com/spacebin-org/spirit)) `Apache-2.0` `Go`
- [Stikked](https://github.com/claudehohl/Stikked) - Advanced and beautiful pastebin. ([Demo](https://paste.scratchbook.ch/)) `GPL-3.0` `PHP`
- [Sup3rS3cretMes5age](https://github.com/algolia/sup3rS3cretMes5age) - Very simple (to deploy and to use) secret message service using Hashicorp Vault as a secrets storage. `MIT` `Go`
- [Pastefy](https://pastefy.ga) - Beautiful, simple and easy to deploy Pastebin with optional Client-Encryption, Multitab-Pastes, an API, a highlighted Editor and more. ([源码](https://github.com/interaapps/pastefy), [Clients](https://github.com/topics/pastefy-addon)) `MIT` `Java`


### Personal Dashboards

**[`^        返回顶部        ^`](#)**

_关联: [Monitoring](#monitoring)_

- [Baby Buddy](https://github.com/babybuddy/babybuddy) - Helps caregivers track baby sleep, feedings, diaper changes, and tummy time. ([Demo](https://babybuddy.herokuapp.com/)) `BSD-2-Clause` `Python`
- [Dashboard](https://github.com/phntxx/dashboard) - Minimalist homepage for organizing your web applications and bookmarks using JSON-files. `MIT` `Nodejs/Docker`
- [DashMachine](https://github.com/rmountjoy92/DashMachine) - Another web application bookmark dashboard, with fun features. `GPL-3.0` `Python`
- [Dashy](https://github.com/lissy93/dashy) - Feature-rich homepage for your homelab, with easy YAML configuration. ([Demo](https://demo.dashy.to/)) `MIT` `Nodejs/Docker`
- [Flame](https://github.com/pawelmalak/flame) - Flame is self-hosted startpage for your server. Easily manage your apps and bookmarks with built-in editors. `MIT` `Nodejs`
- [Habitica](https://habitica.com/) - Habit tracker app which treats your goals like a Role Playing Game. Previously called HabitRPG. ([源码](https://github.com/HabitRPG/habitica)) `GPL-3.0/CC-BY-NC-SA-3.0/CC-BY-SA-3.0` `Nodejs`
- [Heimdall](https://heimdall.site/) - Heimdall is an elegant solution to organise all your web applications. ([源码](https://github.com/linuxserver/Heimdall)) `MIT` `PHP`
- [Hiccup](https://designedbyashw.in/test/hiccup/) - A beautiful static homepage to get to your links and services quickly. It has built-in search, editing, PWA support and localstorage caching to easily organize your start page. ([源码](https://github.com/ashwin-pc/hiccup)) `MIT` `HTML5`
- [Homepage](https://github.com/tomershvueli/homepage) - Simple, standalone, self-hosted PHP page that is your window to your server and the web. `MIT` `PHP`
- [Homer](https://github.com/bastienwirtz/homer) - A dead simple static homepage to expose your server services, with an easy yaml configuration and connectivity check. `Apache-2.0` `HTML5`
- [LinkPage](https://links.zrd.sh) - LinkPage is a FOSS self-hosted alternative to link listing websites such as LinkTree and Campsite.bio. ([源码](https://github.com/rhnvrm/linkpage)) `BSD-2-Clause` `Go`
- [Jmz HomeProxy](https://github.com/jmztaylor/homelab_proxy) - A simple and clean dashboard for self hosted services. `GPL-3.0` `PHP`
- [Organizr](https://github.com/causefx/Organizr) - Organizr aims to be your one stop shop for your Servers Frontend. `GPL-3.0` `PHP`
- [Personal management system](https://github.com/Volmarg/personal-management-system) - Central point for managing personal data (billings, payments, job holidays, notes etc.). ([Demo](http://personal-management-system.pl/)) `MIT` `PHP`
- [simple-dash](https://github.com/kutyla-philipp/simple-dash) - A simple, fully responsive Dashboard to forward to the services of your choice. ([Demo](https://kutyla-philipp.github.io/simple-dash/)) `MIT` `Javascript`
- [Smashing](https://smashing.github.io/) - Smashing, the spiritual successor to Dashing, is a Sinatra based framework that lets you build excellent dashboards. It looks especially great on TVs. ([源码](https://github.com/Smashing/smashing)) `MIT` `Ruby`
- [wger](https://wger.de/) - Web-based personal workout, fitness and weight logger/tracker. It can also be used as a simple gym management utility and offers a full REST API as well. ([Demo](https://wger.de/en/dashboard), [源码](https://github.com/wger-project/wger)) `AGPL-3.0` `Python`
- [Your Spotify](https://github.com/Yooooomi/your_spotify) `⚠` - Allows you to record your Spotify listening activity and have statistics about them served through a Web application. `MIT` `Nodejs/Docker`


### Photo and Video Galleries

**[`^        返回顶部        ^`](#)**

- [Chevereto Free](https://chevereto.com/free) - Powerful and fast image hosting script that allows you to create your very own full featured image hosting website in just minutes. ([源码](https://github.com/Chevereto/Chevereto-Free)) `AGPL-3.0` `PHP`
- [Coppermine](https://coppermine-gallery.net/) - Multilingual photo gallery that integrates with various bulletin boards. Includes upload approval and password protected albums. ([Demo](https://coppermine-gallery.net/demo/cpg15x/), [源码](https://github.com/coppermine-gallery/cpg1.6.x)) `GPL-3.0` `PHP`
- [Damselfly](https://damselfly.info) - Fast server-based photo management system for large collections of images. Includes face detection, face & object recognition, powerful search, and EXIF Keyword tagging. Runs on Linux, MacOS and Windows. `GPL-3.0` `C#/.NET`
- [Fussel](https://github.com/cbenning/fussel) - Fussel is a static photo gallery generator. Easily generate a reactive gallery and host the optimized static folder of assets. `MIT` `Python`
- [Gallery CSS](https://benschwarz.github.io/gallery-css/) - Gallery.css is all CSS. Think: Simple, maintainable and understandable galleries without the use of Javascript. ([源码](https://github.com/benschwarz/gallery-css)) `MIT` `CSS`
- [HomeGallery](https://home-gallery.org) - Self-hosted open-source web gallery to browse personal photos and videos featuring tagging, mobile-friendly, and AI powered image discovery. ([Demo](https://demo.home-gallery.org), [源码](https://github.com/xemle/home-gallery)) `MIT` `Nodejs`
- [ImageStore](https://github.com/gregordr/ImageStore) - Self-hosted Google Photos alternative, with a very similar UI. ([Demo](https://gregordr.github.io/ImageStore/)) `Apache-2.0` `Nodejs/Docker`
- [LibrePhotos](https://github.com/LibrePhotos/librephotos) - Self hosted wannabe Google Photos clone, with a slight focus on cool graphs. `MIT` `Python`
- [Lychee](https://lycheeorg.github.io/) - Open source grid and album based photo-management-system. ([源码](https://github.com/LycheeOrg/Lychee)) `MIT` `PHP`
- [Mediagoblin](https://mediagoblin.org) - Free software media publishing platform that anyone can run. You can think of it as a decentralized alternative to Flickr, YouTube, SoundCloud, etc. ([源码](https://savannah.gnu.org/projects/mediagoblin)) `AGPL-3.0` `Python`
- [Mejiro](https://github.com/dmpop/mejiro) - An easy-to-use PHP web application for instant photo publishing. `GPL-3.0` `PHP`
- [Photato](https://github.com/trebonius0/Photato) - Self-hosted photo gallery, accessible through a responsive WebUI. Directly uses and indexes a specific folder in the filesystem. `AGPL-3.0` `Java`
- [Photo Stream](https://github.com/waschinski/photo-stream) - Minimalist self-hosted photo stream. ([Demo](https://floremotion.de/)) `MIT` `Ruby`
- [PhotoLight](https://github.com/thibaud-rohmer/PhotoLight) - The easiest photo gallery there is. `GPL-3.0` `PHP`
- [Photonix](https://photonix.org/) - A new web-based photo management application with object recognition, location awareness, color analysis and other ML algorithms. ([Demo](https://demo.photonix.org/), [源码](https://github.com/photonixapp/photonix)) `AGPL-3.0` `Python`
- [PhotoPrism](https://photoprism.org) - Personal photo management powered by Go and Google TensorFlow.  Browse, organize, and share your personal photo collection, using the latest technologies to automatically tag and find pictures. ([源码](https://github.com/photoprism/photoprism)) `MIT` `Go`
- [Photoview](https://photoview.github.io/) - A simple and user-friendly Photo Gallery for personal servers. It is made for photographers and aims to provide an easy and fast way to navigate directories, with thousands of high resolution photos. ([Demo](https://photos.qpqp.dk/), [源码](https://github.com/photoview/photoview)) `GPL-3.0` `Go`
- [PiGallery 2](https://bpatrik.github.io/pigallery2/) - A directory-first photo gallery website, with a rich UI, optimised for running on low resource servers. ([源码](https://github.com/bpatrik/pigallery2)) `MIT` `Docker/Nodejs`
- [Piwigo](https://piwigo.org/) - Photo gallery software for the web, built by an active community of users and developers. ([Demo](https://piwigo.org/demo/), [源码](https://github.com/Piwigo/Piwigo)) `GPL-2.0` `PHP`
- [Plumi](https://engagemedia.org/projects/plumi/) - Create your own sophisticated video-sharing site. ([源码](https://github.com/plumi/plumi.app)) `GPL-2.0` `Python`
- [Quru Image Server](https://quruimageserver.com/) - High performance dynamically resizing image server offering directory based access control cropping, rotation, color management and other tools. ([Demo](https://quruimageserver.com), [源码](https://github.com/quru/qis)) `AGPL-3.0` `Python`
- [sigal](https://github.com/saimn/sigal) - Yet another simple static gallery generator. `MIT` `Python`
- [UberGallery](https://www.ubergallery.net) - UberGallery is an easy to use, simple to manage, web photo gallery. UberGallery does not require a database and supports JPEG, GIF and PNG file types. Simply upload your images and UberGallery will automatically generate thumbnails and output HTML. ([源码](https://github.com/UberGallery/UberGallery)) `MIT` `PHP`
- [Zenphoto](https://www.zenphoto.org/) - Open-source gallery and CMS project. ([源码](https://github.com/zenphoto/zenphoto)) `GPL-2.0` `PHP`


### Polls and Events

**[`^        返回顶部        ^`](#)**

_关联: [Booking and Scheduling](#booking-and-scheduling)_

- [Calagator](https://calagator.org/) - Event aggregator. ([源码](https://github.com/calagator/calagator)) `MIT` `Ruby`
- [ClearFlask](https://clearflask.com) - Community-feedback tool for managing incoming feedback and prioritizing a public roadmap. Alternative to Canny, UserVoice, Upvoty. ([Demo](https://product.clearflask.com), [源码](https://github.com/clearflask/clearflask)) `AGPL-3.0` `Docker`
- [Clerk](https://github.com/AppMini/Clerk) - Simple event logger to keep track of periodic events, habits, etc. as they occur. `GPL-3.0` `PHP`
- [Croodle](https://github.com/jelhan/croodle) - Croodle is an end-to-end encrypted web application to schedule a date or to do a poll on any topic. `MIT` `Javascript`
- [dudle](http://primelife.ercim.eu/results/opensource/63-dudle) - Online scheduling application. ([Demo](https://dudle.inf.tu-dresden.de/), [源码](https://github.com/kellerben/dudle)) `AGPL-3.0` `Ruby`
- [Feedka](https://github.com/drabkirn/feedka) `⚠` - Open-source web application that can serve as a platform to get authentic, kindful, and constructive feedback from your friends, family, and co-workers. ([Demo](https://feedka.herokuapp.com)) `AGPL-3.0` `Ruby`
- [Fider](https://getfider.com) - Open source alternative to UserVoice for customer feedback. ([Demo](https://demo.fider.io), [源码](https://github.com/getfider/fider)) `MIT` `Go`
- [Framadate](https://framadate.org/) - Online service for planning an appointment or make a decision quickly and easily: Make a poll, Define dates or subjects to choose, Send the poll link to your friends or colleagues, Discuss and make a decision. ([Demo](https://framadate.org/aqg259dth55iuhwm), [源码](https://git.framasoft.org/framasoft/framadate)) `CECILL-B` `PHP`
- [Gancio](https://gancio.org/) - A shared agenda for local communities. ([Demo](https://demo.gancio.org/), [源码](https://framagit.org/les/gancio)) `AGPL-3.0` `Nodejs`
- [hitobito](https://hitobito.com/en) - A web application to manage complex group hierarchies with members, events and a lot more. ([Demo](https://demo.hitobito.com/en/users/sign_in), [源码](https://github.com/hitobito/hitobito)) `AGPL-3.0` `Ruby`
- [JD Esurvey](https://www.jdsoft.com/jd-esurvey.html) - Open source enterprise survey web application. ([源码](https://github.com/JD-Software/JDeSurvey)) `AGPL-3.0` `Java`
- [Kyélà](https://kyela.net/) - Participation polls for group events. ([Demo](https://kyela.net/concert/), [源码](https://github.com/abienvenu/Kyela)) `AGPL-3.0` `PHP`
- [LimeSurvey](https://www.limesurvey.org) - Feature-rich Open Source web based polling software. Supports extensive survey logic. ([Demo](https://demo.limesurvey.org), [源码](https://github.com/LimeSurvey/LimeSurvey)) `GPL-2.0` `PHP`
- [Meetable](https://meetable.org) - Event aggregator. ([Demo](https://events.indieweb.org), [源码](https://github.com/aaronpk/Meetable)) `MIT` `PHP`
- [Mobilizon](https://mobilizon.org) - A federated tool that helps you find, create and organise events and groups. ([Demo](https://demo.mobilizon.org/), [源码](https://framagit.org/framasoft/mobilizon/)) `GPL-3.0` `Elixir`
- [Open Event Server](https://github.com/fossasia/open-event-server) - Enables organizers to manage events from concerts to conferences and meet-ups. `GPL-3.0` `Python`
- [PHPBack](https://www.phpback.org) - The open source feedback system. ([Demo](https://www.phpback.org/demo/), [源码](https://github.com/ivandiazwm/phpback)) `GPL-3.0` `PHP`


### Proxy

**[`^        返回顶部        ^`](#)**

- [imgproxy](https://imgproxy.net/) - Fast and secure standalone server for resizing and converting remote images. It works great when you need to resize multiple images on the fly without preparing a ton of cached resized images or re-doing it every time the design changes. ([源码](https://github.com/imgproxy/imgproxy)) `MIT` `Go/Docker`
- [inlets](https://inlets.dev/) - Expose your local endpoints to the Internet - with a Kubernetes integration, Docker image and CLI available. `MIT` `Go/Docker`
- [iodine](https://code.kryo.se/iodine/) - IPv4 over DNS tunnel solution, enabling you to start up a socks5 proxy listener. ([源码](https://github.com/yarrick/iodine)) `ISC` `C`
- [microproxy](https://github.com/thekvs/microproxy) - lightweight non-caching HTTP/HTTPS proxy server. `MIT` `Go`
- [Nginx Proxy Manager](https://nginxproxymanager.com/) - Nginx Proxy Manager is an easy way to accomplish reverse proxying hosts with SSL termination. ([源码](https://github.com/jc21/nginx-proxy-manager)) `MIT` `Nodejs/Docker`
- [PHP-Proxy](https://www.php-proxy.com/) - Web proxy script built specifically to be fast, easy to modify and to support video sites such as YouTube. ([Demo](https://unblockvideos.com/), [源码](https://github.com/Athlon1600/php-proxy-app)) `MIT` `PHP`
- [Pomerium](https://pomerium.io) - An identity-aware reverse proxy, successor to now obsolete oauth_proxy. It inserts an OAuth step before proxying your request to the backend, so that you can safely expose your self-hosted websites to public Internet. ([源码](https://github.com/pomerium/pomerium)) `Apache-2.0` `Go`
- [Pound](https://www.apsis.ch/pound.html) - Light-weight reverse proxy and load balancer for HTTP/HTTPS. `GPL-2.0` `C`
- [Privoxy](https://www.privoxy.org) - Non-caching web proxy with advanced filtering capabilities for enhancing privacy, modifying web page data and HTTP headers, controlling access, and removing ads and other obnoxious Internet junk. `GPL-2.0` `C`
- [Redbird](https://github.com/OptimalBits/redbird) - A modern reverse proxy for node that includes cluster, HTTP2, LetsEncrypt, and Docker support. `BSD-2-Clause` `Javascript`
- [sish](https://github.com/antoniomika/sish) - Open source serveo/ngrok alternative providing HTTP(S)/WS(S)/TCP tunnels to localhost using only SSH. `MIT` `Go`
- [socks5-proxy-server](https://github.com/nskondratev/socks5-proxy-server) - SOCKS5 proxy server with built-in authentication and Telegram-bot for user management and user statistics on data spent (handy when you pay per GB of data). It is dockerised and simple to install. `Apache-2.0` `Nodejs`
- [SOCKS5Engine](https://github.com/VeeSecurity/SOCKS5Engine) - Lightweight & resource-efficient SOCKS5 proxy server, optimized for high-load. `AGPL-3.0` `Go`
- [Squid](http://www.squid-cache.org/) - Caching proxy for the Web supporting HTTP, HTTPS, FTP, and more. It reduces bandwidth and improves response times by caching and reusing frequently-requested web pages. ([源码](https://code.launchpad.net/squid)) `GPL-2.0` `C`
- [SWAG (Secure Web Application Gateway)](https://github.com/linuxserver/docker-swag) - Nginx webserver and reverse proxy with PHP support, built-in Certbot (Let's Encrypt) client and fail2ban integration. `GPL-3.0` `Docker`
- [Swiperproxy](https://swiperproxy.github.io/) - Lightning-fast, open source web proxy that is easy for you to run and customize. ([源码](https://github.com/swiperproxy/swiperproxy)) `MIT` `Python`
- [Tinyproxy](https://tinyproxy.github.io/) - Light-weight HTTP/HTTPS proxy daemon. ([源码](https://github.com/tinyproxy/tinyproxy)) `GPL-2.0` `C`
- [Traefik](https://traefik.io/) - Træfɪk is a modern HTTP reverse proxy and load balancer made to deploy microservices with ease. It supports several backends (Docker, Swarm, Mesos/Marathon, …) to manage its configuration automatically and dynamically. ([源码](https://github.com/traefik/traefik)) `MIT` `Go`


### 稍后读清单

**[`^        返回顶部        ^`](#)**

- [Readflow](https://readflow.app) - Lightweight news reader with modern interface and features: full-text search, automatic categorization, archiving, offline support, notifications... ([源码](https://github.com/ncarlier/readflow)) `MIT` `Go`
- [Wallabag](https://www.wallabag.org) - Wallabag, formerly Poche, is a web application allowing you to save articles to read them later with improved readability. ([Demo](https://app.wallabag.it/register/), [源码](https://github.com/wallabag/wallabag)) `MIT` `PHP`


### 食谱管理

**[`^        返回顶部        ^`](#)**

- [kcal](https://github.com/kcal-app/kcal) - 追踪食物和食谱的营养信息，设定目标，并记录食物日记，以帮助一路上的发展。Kcal是一个个人系统，重点是直接控制投入，并以最小的、易于使用的食谱展示来准备膳食。 ([Demo](http://demo.kcal.cooking/login)) `MPL-2.0` `PHP`
- [Mealie](https://hay-kot.github.io/mealie/) - Material 料设系统计为灵感的菜谱管理器，具有分类和标签管理、购物清单、膳食计划和网站定制功能。Mealie专注于简单的用户互动，使整个家庭都能使用这个应用程序。 ([源码](https://github.com/hay-kot/mealie)) `MIT` `Python`
- [OpenEats](https://github.com/open-eats/OpenEats) - 菜谱管理网站，允许用户创建、存储、分享和评价菜谱，创建杂货清单等。 ([Demo](https://open-eats.github.io/)) `MIT` `Python`
- [RecipeSage](https://github.com/julianpoy/recipesage) - 一个可以直接从任何URL导入食谱的食谱保存者、膳食计划组织者和购物清单管理者。 ([Demo](https://recipesage.com)) `AGPL-3.0` `Nodejs`
- [Tandoor Recipes](https://docs.tandoor.dev/) - Django 应用程序使用内置模型或托管PDF、图片或其他文件的外部存储供应商来管理、标记和搜索食谱。 ([Demo](https://app.tandoor.dev/), [源码](https://github.com/vabene1111/recipes/)) `MIT` `Python`


### 资源规划

**[`^        返回顶部        ^`](#)**

- [farmOS](https://farmos.org/) - 基于 web 的农场记录保存应用程序。 ([源码](https://github.com/farmOS/farmOS)) `GPL-2.0` `PHP`
- [grocy](https://grocy.info/) - 超越你的冰箱的 ERP - grocy 是一个基于 web 的自我托管的杂货和家庭管理解决方案，为你的家。 ([Demo](https://en.demo.grocy.info/), [源码](https://github.com/grocy/grocy)) `MIT` `PHP`
- [Tania](https://github.com/Tanibox/tania-core) - Tania 是一个免费和开源的耕作管理系统，适合所有人。你可以管理你的地区、水库、农场任务、库存和作物生长进度。 `Apache-2.0` `Go`


### 资源规划 - 企业资源规划

**[`^        返回顶部        ^`](#)**

- [Dolibarr](https://www.dolibarr.org/) - Dolibarr ERP CRM 是一个现代化的软件包，用于管理你的公司或基金会的活动（联系人、供应商、发票、订单、库存、议程、会计...）。 ([Demo](https://www.dolibarr.org/onlinedemo.php), [源码](https://github.com/Dolibarr/dolibarr)) `GPL-3.0-or-later` `PHP`
- [ERPNext](https://erpnext.com) - 免费的开放源码ERP系统。 ([源码](https://github.com/frappe/erpnext)) `GPL-3.0` `Python`
- [LedgerSMB](https://ledgersmb.org/) - 适用于中小型企业的综合会计和 ERP 系统，具有复式记账、预算编制、发票、报价、项目、订单和库存管理、运输等功能。 ([Demo](https://demo.cloud.efficito.com/erp/1.5/login.pl), [源码](https://github.com/ledgersmb/LedgerSMB)) `GPL-2.0` `Perl`
- [Odoo](https://www.odoo.com) - 免费的开放源码ERP系统。 ([Demo](https://demo.odoo.com/), [源码](https://github.com/odoo/odoo)) `LGPL-3.0` `Python`
- [OFBiz](https://ofbiz.apache.org/) - FOSS 企业资源规划系统，有一套灵活的商业应用，可以在任何行业使用。 ([源码](https://svn.apache.org/viewvc/ofbiz/)) `Apache-2.0` `Java`
- [Tryton](https://www.tryton.org/) - 免费的开放源码商业解决方案。 ([Demo](https://www.tryton.org/download.html), [源码](https://hg.tryton.org/)) `GPL-3.0` `Python`


### 搜索引擎

**[`^        返回顶部        ^`](#)**

- [Ambar](https://ambar.cloud) - 文件搜索引擎（OCR，存储和搜索）。 ([Demo](https://app.ambar.cloud/), [源码](https://github.com/RD17/ambar)) `MIT` `Nodejs/Python`
- [Gigablast](https://www.gigablast.com/) - 开源搜索引擎。 ([源码](https://github.com/gigablast/open-source-search-engine)) `Apache-2.0` `C++`
- [Jina](https://github.com/jina-ai/jina/) - 用于任何类型数据的云原生神经搜索框架。 `Apache-2.0` `Python`
- [MeiliSearch](https://meilisearch.com) - 超相关的、即时的和容忍错别字的全文搜索API。 ([源码](https://github.com/meilisearch/MeiliSearch)) `MIT` `Rust`
- [Searx](https://searx.github.io/searx/) - 尊重隐私、可黑客的元搜索引擎。 ([Demo](https://searx.me/), [源码](https://github.com/searx/searx)) `AGPL-3.0` `Python`
- [sist2](https://github.com/simon987/sist2) - 快如闪电的文件系统索引器和搜索工具。 ([Demo](https://sist2.simon987.net/)) `GPL-3.0` `C`
- [Typesense](https://typesense.org) - 速度极快、可容忍错别字的开源搜索引擎，为开发者的快乐和易用性进行了优化。 ([源码](https://github.com/typesense/typesense)) `GPL-3.0` `C++`
- [Whoogle](https://github.com/benbusby/whoogle-search) `⚠` - 一个自我托管、无广告、尊重隐私的元搜索引擎。 `MIT` `Python`
- [Yacy](https://yacy.net/en/index.html) - 基于P2P的、去中心化的搜索引擎服务器。 ([Demo](https://search.yacy.net/), [源码](https://github.com/yacy/yacy_search_server)) `GPL-2.0` `Java`


### 自我托管解决方案

**[`^        返回顶部        ^`](#)**

- [Ansible-NAS](https://github.com/DaveStephens/ansible-nas) - 用这个游戏手册和 Ubuntu 盒子构建一个全功能的家庭服务器。 `MIT` `YAML/Docker`
- [Bitsii Bridge](https://gitlab.com/bitsii/Bitsii/-/wikis/home) `⚠` - 易于安装的自我托管平台，适用于 Windows、MacOS 和 Linux。取决于一个动态 DNS 提供商和 Let's Encrypt。 ([源码](https://gitlab.com/edgii/BBridge)) `MPL-2.0` `Java/Other`
- [Cloudbox](https://cloudbox.works) - 基于 Ansible 的解决方案，快速部署 Docker 容器化的云媒体服务器。 ([源码](https://github.com/Cloudbox/Cloudbox)) `GPL-3.0` `Shell/Ansible`
- [DietPi](https://dietpi.com/) - 为单板计算机优化的最小的 Debian 操作系统，它允许你轻松地安装和管理几个服务，在家里自我托管。 ([源码](https://github.com/MichaIng/DietPi)) `GPL-2.0` `Shell`
- [DockSTARTer](https://dockstarter.com/) - DockSTARTer 帮助你开始使用在 Docker 中运行的家庭服务器应用程序。 ([源码](https://github.com/GhostWriters/DockSTARTer)) `MIT` `Shell`
- [DPlatform](https://dfabric.github.io/DPlatform-Shell/) - 轻松部署自我托管的应用程序：简单、无臃肿、独立安装。 ([源码](https://github.com/DFabric/DPlatform-Shell)) `MIT` `Shell`
- [FLAP](https://www.flap.cloud) - 低维护框架来管理自我托管的服务。 ([源码](https://gitlab.com/flap-box/flap)) `AGPL-3.0` `Docker/Shell`
- [FreedomBone](https://freedombone.net/) - 基于 Debian 的家庭服务器配置。 ([源码](https://code.freedombone.net/bashrc/freedombone)) `AGPL-3.0` `Shell`
- [FreedomBox](https://freedomboxfoundation.org/) - 开发、设计和推广运行自由软件的个人服务器的社区项目，用于私人、个人、通信。 ([源码](https://salsa.debian.org/freedombox-team/freedombox)) `AGPL-3.0` `Python/Other`
- [HomelabOS](https://homelabos.com) - 你自己的离线第一以隐私为中心的开源数据中心。只需几个命令就可以部署 100 多个服务。 ([源码](https://gitlab.com/NickBusey/HomelabOS)) `MIT` `Docker`
- [NextCloudPi](https://nextcloudpi.com/) - Nextcloud 预安装和预配置，具有文本和 web 管理界面，以及自我托管私人数据所需的所有工具。有用于 Raspberry Pi、Odroid、Rock64、Docker 的安装镜像，以及用于 Armbian/Debian 的 curl 安装程序。 ([源码](https://github.com/nextcloud/nextcloudpi)) `GPL-2.0-or-later` `Bash/PHP`
- [OpenMediaVault](https://www.openmediavault.org/) - OpenMediaVault 是基于 Debian Linux 的下一代网络连接存储（NAS）解决方案。它包含像SSH、（S）FTP、SMB/CIFS、DAAP媒体服务器、RSync、BitTorrent客户端等服务。 ([源码](https://github.com/openmediavault/openmediavault)) `GPL-3.0` `PHP`
- [Sandstorm](https://sandstorm.io/) - 个人服务器用于轻松和安全地运行自我托管的应用程序。 ([Demo](https://demo.sandstorm.io/), [源码](https://github.com/sandstorm-io/sandstorm)) `Apache-2.0` `C++/Other`
- [sovereign](https://github.com/sovereign/sovereign) - 一套Ansible操作手册，用于构建和维护你自己的私有云：电子邮件、日历、联系人、文件同步、IRC保镖、VPN等等。 `GPL-3.0` `YAML/Other`
- [Syncloud](https://syncloud.org/) - 你自己的在线文件存储、社交网络或电子邮件服务器。 ([源码](https://github.com/syncloud/platform)) `GPL-3.0` `Python/Other`
- [UBOS](https://ubos.net/) - 在独立盒子（个人服务器和物联网设备）上运行的Linux发行版。单命令安装和管理应用程序 - Jenkins、Mediawiki、Owncloud、WordPress等，以及其他功能。 `GPL-3.0` `Perl/Other`
- [WikiSuite](https://wikisuite.org) - 最全面和集成的自由/自由/开源企业软件套件。 ([源码](https://wikisuite.org/Source-Code)) `GPL-3.0/LGPL-2.1/Apache-2.0/MPL-2.0/MPL-1.1/MIT/AGPL-3.0` `ClearOS`
- [xsrv](https://xsrv.readthedocs.io/) - 在你自己的服务器上安装和管理自我托管的服务/应用程序。 ([源码](https://github.com/nodiscc/xsrv)) `GPL-3.0` `Shell/Ansible`
- [YunoHost](https://yunohost.org/) - 服务器操作系统，旨在使每个人都能使用自我托管。 ([Demo](https://yunohost.org/#/try), [源码](https://github.com/YunoHost)) `AGPL-3.0` `Python/Other`


### 软件开发

**[`^        返回顶部        ^`](#)**


### 软件开发 - API 管理

**[`^        返回顶部        ^`](#)**

- [DreamFactory](https://www.dreamfactory.com/) - 将任何 SQL/NoSQL/结构化数据变成 Restful API。 ([源码](https://github.com/dreamfactorysoftware/dreamfactory)) `Apache-2.0` `PHP`
- [form.io](https://form.io) - 一个 REST API 构建平台，采用拖放式表单生成器，与应用程序框架无关。包含开放源码和企业版。 ([Demo](https://portal.form.io), [源码](https://github.com/formio)) `MIT` `Nodejs`
- [Fusio](https://www.fusio-project.org/) - 开源的 API 管理平台，帮助建立和管理 REST APIs。 ([Demo](https://fusio-project.org/demo), [源码](https://github.com/apioo/fusio)) `AGPL-3.0` `PHP`
- [Hapttic](https://github.com/jsoendermann/hapttic) - 简单的 HTTP 服务器，将所有请求转发给一个 shell 脚本，以处理你收到的 webhooks。 `Apache-2.0` `Go`
- [Hasura](https://hasura.io) - 在 Postgres 上的快速、即时的实时 GraphQL APIs，具有精细的访问控制，还可以在数据库事件上触发 webhooks。 ([源码](https://github.com/hasura/graphql-engine)) `Apache-2.0` `Haskell`
- [Hoppscotch](https://hoppscotch.io) - 一个免费、快速、漂亮的 API 请求生成器。 ([源码](https://github.com/hoppscotch/hoppscotch)) `MIT` `Nodejs/Vue/Nuxt`
- [Kong](https://konghq.com/kong/) - 世界上最受欢迎的开源微服务 API 网关和平台。 ([源码](https://github.com/Kong/kong)) `Apache-2.0` `Lua`
- [Lura](https://luraproject.org/) - 开源的高性能 API 网关。 ([源码](https://github.com/luraproject/lura)) `Apache-2.0` `Go`
- [Para](https://paraio.org) - 灵活和模块化的后端框架/服务器，用于对象持久性、API 开发和认证。 ([源码](https://github.com/erudika/para)) `Apache-2.0` `Java`
- [Pizzly](https://github.com/bearer/pizzly) - 开源的 API 集成管理器，提供开发人员与基于 OAuth 的 API 交互所需的一切。 `MIT` `Nodejs`
- [Tyk](https://tyk.io) - 快速和可扩展的开源 API 网关。开箱即用，Tyk 提供了一个 API 管理平台，包括 API 网关、API 分析、开发者门户和 API 管理仪表板。 ([源码](https://github.com/TykTechnologies/tyk)) `MPL-2.0` `Go`


### 软件开发 - Bug 追踪

**[`^        返回顶部        ^`](#)**

**请访问 [追踪](#追踪)**


### 软件开发 - 持续集成和部署

**[`^        返回顶部        ^`](#)**

**请访问 [awesome-sysadmin/Continuous Integration & Continuous Deployment](https://github.com/awesome-foss/awesome-sysadmin#continuous-integration--continuous-deployment)**


### 软件开发 - 文档生成

**[`^        返回顶部        ^`](#)**

_关联: [静态站点生成](#静态站点生成)_

- [Docstore](https://git.haldean.org/docstore/) - 静态文件托管，没有任何服务器端的处理，不需要你在每次改变文章时重新编译。克隆资源库并在text/目录下添加文章就可以开始了。 ([源码](https://github.com/haldean/docstore)) `BSD-3-Clause` `Javascript`
- [Flatdoc](https://ricostacruz.com/flatdoc/) - 微小的 Javascript 文件可以获取 Markdown 文件并将其渲染成完整的页面。 `MIT` `Javascript`
- [markdown-tree](https://github.com/mil/markdown-tree) - 提供一个层次结构/树状的 markdown 文件目录。用于用 markdown 建立的小型网站。 `MIT` `Ruby`
- [Read the Docs](https://readthedocs.org/) - 托管文档，使其完全可搜索并易于查找；使用任何主要的版本控制系统导入你的文档，包括Mercurial、Git、Subversion和Bazaar。 ([Demo](https://readthedocs.org/projects/), [源码](https://github.com/readthedocs/readthedocs.org)) `MIT` `Python`


### 软件开发 - FaaS & Serverless

**[`^        返回顶部        ^`](#)**

[Serverless 计算 - Wikipedia](https://en.wikipedia.org/wiki/Serverless_computing)

- [Appwrite](https://appwrite.io) - 为网络、原生和移动端开发者提供端到端的后端服务器🚀。 ([源码](https://github.com/appwrite/appwrite)) `BSD-3-Clause` `PHP`
- [fx](https://github.com/metrue/fx) - fx 是一个工具，帮助你在自己的服务器上以无痛的方式实现功能即服务。 `MIT` `Go`
- [IronFunctions](https://github.com/iron-io/functions) - [iron.io](https://www.iron.io/)推出的 Serverless 微服务平台。 `Apache-2.0` `Go`
- [LocalStack](https://localstack.cloud/) - LocalStack 是一个功能齐全的本地 AWS云栈。这包括用于 Serverless 计算的 Lambda。 ([源码](https://github.com/localstack/localstack)) `Apache-2.0` `Python/Other`
- [OpenFaaS](https://www.openfaas.com/) - Docker 和 Kubernetes 的 Serverless 功能的简单化。 ([源码](https://github.com/openfaas/faas)) `MIT` `Go`
- [Trusted-CGI](https://github.com/reddec/trusted-cgi) - 轻量级自我托管的 Lambda/应用/cgi/Serverless 功能平台。 `MIT` `Go`


### 软件开发 - IDE & Tools

**[`^        返回顶部        ^`](#)**

- [Appsmith](https://www.appsmith.com/) - 构建管理面板、CRUD应用程序和工作流的云端或自我托管的开源平台。构建你需要的一切，速度快10倍。 ([源码](https://github.com/appsmithorg/appsmith)) `Apache-2.0` `Java/Docker`
- [Atheos](https://www.atheos.io) - 基于web的集成开发环境框架，占地面积小，要求低，延续自Codiad。 ([源码](https://github.com/Atheos/Atheos)) `MIT` `PHP`
- [Babelfish](https://github.com/bblfsh/bblfshd) - 用于源代码解析的自我托管服务器。它可以解析任何文件，在任何支持的语言中，从中提取抽象语法树，并将其转换为通用抽象语法树，从而实现进一步的分析和转换。 `GPL-3.0` `Go`
- [Budibase](https://www.budibase.com) - 在几分钟内建立和自动化内部工具、管理面板、仪表盘、CRUD应用程序等。Budibase是Outsystems, Retool, Mendix, Appian的开源替代品。 ([源码](https://github.com/Budibase/budibase)) `GPL-3.0` `Nodejs`
- [Code-Server](https://coder.com/) - 浏览器中的Visual Studio代码，托管在一个远程服务器上。 ([源码](https://github.com/cdr/code-server)) `MIT` `Nodejs/Docker`
- [Eclipse Che](https://www.eclipse.org/che/) - 开源的工作区服务器和云IDE。 ([源码](https://github.com/eclipse/che)) `EPL-1.0` `Docker/Java`
- [Gitpod](https://gitpod.io/) - GitHub和GitLab的在线IDE。 ([Demo](https://gitpod.io/#https://github.com/awesome-selfhosted/awesome-selfhosted), [源码](https://github.com/gitpod-io/self-hosted)) `EPL-2.0` `Go/Docker`
- [Hakatime](https://github.com/mujx/hakatime) - WakaTime服务器的实施与分析仪表板。 `Unlicense` `Haskell`
- [HttPlaceholder](https://github.com/dukeofharen/httplaceholder) - 使用HttPlaceholder可以快速地模拟任何网络服务。HttPlaceholder让你指定请求应该是什么样子，需要返回什么响应。 `MIT` `C#`
- [ICEcoder](https://icecoder.net/) - ICEcoder是一个web IDE/基于浏览器的代码编辑器，它允许你直接在web浏览器中开发网站。 ([Demo](http://demo.icecoder.net/ICEcoder/), [源码](https://github.com/icecoder/ICEcoder)) `MIT` `PHP`
- [JS Bin](https://jsbin.com/) - 开源的协作式web开发调试工具。 ([源码](https://github.com/jsbin/jsbin)) `MIT` `Nodejs`
- [Judge0 CE](https://judge0.com) - 编译和运行源代码的开放源码API。 ([源码](https://github.com/judge0/judge0)) `GPL-3.0` `Ruby`
- [JupyterLab](https://jupyterlab.github.io/jupyterlab/) - 基于web的交互式和可重复的计算环境。 ([Demo](https://mybinder.org/v2/gh/jupyterlab/jupyterlab-demo/try.jupyter.org?urlpath=lab), [源码](https://github.com/jupyterlab/jupyterlab/)) `BSD-3-Clause` `Python/Docker`
- [Lowdefy](https://www.lowdefy.com/) - 使用YAML/JSON在一个自我托管的开源平台上，在几分钟内建立内部工具、BI仪表盘、管理面板、CRUD应用程序和工作流程。连接到你的数据源，通过Serverless、Netlify或Docker托管。 ([源码](https://github.com/lowdefy/lowdefy)) `Apache-2.0` `Nodejs`
- [ML Workspace](https://github.com/ml-tooling/ml-workspace) - 用于机器学习和数据科学的多合一网络集成开发环境。 `Apache-2.0` `Docker`
- [Motor Admin](https://www.getmotoradmin.com/) - 无代码管理面板和商业智能软件--搜索、创建、更新和删除数据条目，创建自定义动作，并建立报告。 ([Demo](https://motor-admin.herokuapp.com/demo/), [源码](https://github.com/motor-admin/motor-admin)) `AGPL-3.0` `Ruby`
- [Regexr](https://regexr.com/) - RegExr是一个基于HTML/JS的工具，用于创建、测试和学习正则表达式。 ([源码](https://github.com/gskinner/regexr)) `MIT` `Nodejs`
- [RStudio Server](https://www.rstudio.com/products/rstudio/#Server) - 基于web浏览器的R的IDE。 ([源码](https://github.com/rstudio/rstudio)) `AGPL-3.0` `Java/C++`
- [Slingcode](https://slingcode.net/) - 在一个静态HTML文件中的Web应用IDE和计算平台。 ([Demo](https://slingcode.net/slingcode.html), [源码](https://github.com/chr15m/slingcode/)) `MIT` `HTML`
- [sourcegraph](https://sourcegraph.com) - Sourcegraph是一个用Go语言编写的快速、开源、功能齐全的代码搜索和导航引擎。 ([源码](https://github.com/sourcegraph/sourcegraph)) `Apache-2.0` `Go`
- [ToolJet](https://tooljet.io/) - ToolJet是Retool和Mendix的开源低代码框架替代品，以最小的工程努力来构建和部署内部工具。 ([源码](https://github.com/ToolJet/ToolJet)) `GPL-3.0` `Nodejs`
- [Wakapi](https://wakapi.dev/) - 编码统计的跟踪工具，与WakaTime兼容。 ([源码](https://github.com/muety/wakapi)) `GPL-3.0` `Go`


### 软件开发 - 本地化

**[`^        返回顶部        ^`](#)**

- [Accent](https://www.accent.reviews/) - 开源的、自我托管的、面向开发者的翻译工具。 ([源码](https://github.com/mirego/accent)) `BSD-3-Clause` `Elixir`
- [Localizer](https://localizer.dev) - 为你的产品提供免费的自我托管的开源人群翻译服务。 ([Demo](https://localize.todorant.com), [源码](https://github.com/backmeupplz/localizer-backend)) `MIT` `Nodejs/Docker`
- [Pootle](https://pootle.translatehouse.org) - 在线翻译和本地化工具。 ([源码](https://github.com/translate/pootle)) `GPL-3.0` `Python`
- [Traduora](https://traduora.com) - 为团队提供的翻译管理平台。 ([源码](https://github.com/ever-co/ever-traduora)) `AGPL-3.0` `Docker/Nodejs`
- [Weblate](https://weblate.org) - 基于web的翻译工具，具有严格的版本控制集成。 ([Demo](https://demo.weblate.org), [源码](https://github.com/WeblateOrg/weblate)) `GPL-3.0` `Python`
- [Zanata](http://zanata.org) - 基于web的翻译平台，供译员、内容创作者和开发人员管理本地化项目。 ([源码](https://github.com/zanata/zanata-platform)) `GPL-2.0` `Java`


### 软件开发 - 项目管理

**[`^        返回顶部        ^`](#)**

_关联: [追踪](#追踪), [任务管理 & 待办清单](#任务管理和待办清单)_

_另见: [awesome-sysadmin/Code Review](https://github.com/awesome-foss/awesome-sysadmin#code-review)_

- [Bonobo Git Server](https://bonobogitserver.com/) - 在 Windows 的 IIS 上建立你自己的 git 托管服务器。通过一个漂亮的用户友好的图形界面来管理用户并完全控制你的存储库。 ([源码](https://github.com/jakubgarfield/Bonobo-Git-Server)) `MIT` `C#`
- [Fossil](https://www.fossil-scm.org/index.html/doc/trunk/www/index.wiki) - 分布式版本控制系统，具有维基和错误跟踪器。 `BSD-2-Clause-FreeBSD` `C`
- [Git WebUI](https://github.com/alberthier/git-webui) - 独立的基于 web 的用户接口，用于git仓库。 `Apache-2.0` `Python`
- [Gitblit](https://gitblit.github.io/gitblit/) - 用于管理、查看和服务 Git 存储库的纯 Java 堆栈。 ([源码](https://github.com/gitblit/gitblit)) `Apache-2.0` `Java`
- [gitbucket](https://gitbucket.github.io/gitbucket-news/) - 由 Scala 驱动的可轻松安装的 GitHub 克隆。 ([源码](https://github.com/gitbucket/gitbucket)) `Apache-2.0` `Scala/Java`
- [Gitea](https://gitea.io) - 社区管理的 Gogs 分叉，轻量级代码托管解决方案。 ([Demo](https://try.gitea.io), [源码](https://github.com/go-gitea/gitea)) `MIT` `Go`
- [GitLab](https://about.gitlab.com) - 自我托管的 Git 存储库管理、代码审查、问题跟踪、活动反馈和维基。 ([Demo](https://gitlab.com/), [源码](https://gitlab.com/gitlab-org/gitlab-foss)) `MIT` `Ruby`
- [Gitlist](https://gitlist.org/) - 基于web的 git 仓库浏览器 - GitList 允许你使用你喜欢的浏览器浏览仓库，查看不同修订版下的文件，提交历史和差异。 ([源码](https://github.com/klaussilveira/gitlist)) `BSD-3-Clause` `PHP`
- [Gitolite](https://gitolite.com/gitolite/index.html) - Gitolite 允许你在一个中央服务器上设置 git 托管，具有细粒度的访问控制和许多更强大的功能。 ([源码](https://github.com/sitaramc/gitolite)) `GPL-2.0` `Perl`
- [GitPrep](https://gitprep.yukikimoto.com/) - 便携式 Github 克隆。 ([Demo](https://perlcodesample.sakura.ne.jp/gitprep/gitprep.cgi), [源码](https://github.com/yuki-kimoto/gitprep)) `Artistic-2.0` `Perl`
- [Gogs](https://gogs.io/) - 用 Go 编写的无痛的自我托管的 Git 服务。 ([Demo](https://try.gogs.io/), [源码](https://github.com/gogs/gogs)) `MIT` `Go`
- [Goodwork](https://usegood.work/) - 由 Laravel 和 VueJS 驱动的自我托管的项目管理和协作工具。 ([Demo](https://github.com/iluminar/goodwork#demo), [源码](https://github.com/iluminar/goodwork)) `MIT` `PHP`
- [Kallithea](https://kallithea-scm.org/) - 源代码管理系统，支持两个领先的版本控制系统，Mercurial 和 Git，有一个 web 界面。 ([源码](https://kallithea-scm.org/repos/kallithea)) `GPL-3.0` `Python`
- [Klaus](https://github.com/jonashaag/klaus) - 简单、易于设置的 Git 网络浏览器，只需工作。 `ISC` `Python`
- [Lavagna](https://lavagna.io) - Lavagna 是一个开源的问题/项目管理工具，专为小型团队设计。轻量级，纯 Java，易于安装，易于使用。 ([源码](https://github.com/digitalfondue/lavagna)) `GPL-3.0` `Java`
- [Lazylead](https://lazylead.org) `⚠` - 消除 ticketing 系统（Jira、GitHub、Trello）中的烦人工作。允许自动化日常行动，如票据字段验证、JQL/GQL 的电子邮件通知、向您（或队友）的日历提出会议请求。 ([源码](https://github.com/dgroup/lazylead)) `MIT` `Ruby`
- [Leantime](https://leantime.io) - Leantime 是一个针对小型团队和初创企业的精益项目管理系统，帮助管理从构思到交付的项目。 ([源码](https://github.com/leantime/leantime)) `GPL-2.0` `PHP`
- [Microgit](https://github.com/microgit-com/microgit) - 用 Crystal 和 Lucky 制作的 Git 托管服务。 `MIT` `Crystal`
- [Octobox](https://octobox.io/) `⚠` - 夺回对 GitHub 通知的控制权。 ([源码](https://github.com/octobox/octobox)) `AGPL-3.0` `Ruby`
- [OneDev](https://onedev.io/) - 一体化的 DevOps 平台。拥有 Git 管理、问题跟踪和 CI/CD。简单而强大。 ([源码](https://code.onedev.io/projects/160)) `MIT` `Java`
- [OpenProject](https://www.openproject.org) - OpenProject 是一个基于 web 的项目管理系统。 ([源码](https://github.com/opf/openproject)) `GPL-3.0` `Ruby`
- [Pagure](https://pagure.io/pagure) - 一个轻量级的、强大的、灵活的、以 git 为中心的 forge，其功能为联合和分散开发奠定了基础。 ([Demo](https://pagure.io/)) `GPL-2.0` `Python`
- [Phproject](https://www.phproject.org/) - 高性能的全功能项目管理系统。 ([Demo](https://demo.phproject.org/), [源码](https://github.com/Alanaktion/phproject)) `GPL-3.0` `PHP`
- [ProjeQtOr](https://www.projeqtor.org/) - 一个完整的、成熟的、多用户的项目管理系统，对项目的所有阶段都有广泛的功能。 ([Demo](https://demo.projeqtor.org/), [源码](https://sourceforge.net/p/projectorria/code/HEAD/tree/branches/)) `AGPL-3.0` `PHP`
- [Re:Backlogs](https://github.com/kaishuu0123/rebacklogs) - 由 Ruby on Rails 和 VueJS 驱动的项目管理和协作工具。 ([Demo](https://rebacklogs.saino.me/users/sign_up)) `MIT` `Ruby`
- [Redmine](https://www.redmine.org/) - Redmine 是一个灵活的项目管理网络应用。 ([Demo](http://demo.redmine.org/), [源码](https://svn.redmine.org/redmine/)) `GPL-2.0` `Ruby`
- [RhodeCode](https://rhodecode.com/) - Rhode 是一个面向软件开发团队的开源平台。它统一并简化了 Git、Subversion 和Mercurial的存储库管理。 ([源码](https://code.rhodecode.com/)) `AGPL-3.0` `Python`
- [SCM Manager](https://www.scm-manager.org/) - 通过 http 共享和管理你的 Git、Mercurial 和 Subversion 存储库的最简单的方法。 ([源码](https://github.com/scm-manager/scm-manager)) `BSD-3-Clause` `Java`
- [Taiga](https://taiga.io/) - 基于看板和 Scrum 方法的敏捷项目管理工具。 ([源码](https://github.com/taigaio)) `AGPL-3.0` `Python`
- [Titra](https://titra.io/en/free-time-tracking-online/) - 为自由职业者和小团队提供时间追踪解决方案。 ([Demo](https://app.titra.io/try), [源码](https://github.com/kromitgmbh/titra)) `GPL-3.0` `Javascript`
- [Trac](https://trac.edgewall.org/) - Trac 是一个增强的维基和问题跟踪系统，用于软件开发项目。 `BSD-3-Clause` `Python`
- [Tuleap](https://www.tuleap.org/) - Tuleap 是一个用于计划、跟踪、编码和协作软件项目的自由套装。 ([源码](https://tuleap.net/plugins/git/tuleap/tuleap/stable?p=tuleap%2Fstable.git&a=tree)) `GPL-2.0` `PHP`
- [UVDesk](https://www.uvdesk.com/) - UVDesk 社区是一个以服务为导向，事件驱动的可扩展开源服务台系统，可以被你的组织用来为你的客户毫不费力地提供高效的支持，无论你怎么想象。 ([Demo](https://demo.uvdesk.com/), [源码](https://github.com/uvdesk/community-skeleton)) `MIT` `PHP`
- [ZenTao](https://www.zentao.pm/) - 敏捷（Scrum）项目管理系统/工具。 ([Demo](https://demo.zentao.pm/user-login.html), [源码](https://github.com/easysoft/zentaopms)) `ZPL-1.2` `PHP`


### 软件开发 - UX 测试

**[`^        返回顶部        ^`](#)**

- [DeepfakeHTTP](https://github.com/xnbox/DeepfakeHTTP) - 一个使用 HTTP 转储作为响应来源的 web 服务器。 `MIT` `Java`
- [Selenoid](https://aerokube.com/selenoid/latest/) - 轻量级的 Selenium hub 实现在 Docker 容器内启动浏览器。 ([源码](https://github.com/aerokube/selenoid)) `Apache-2.0` `Go`
- [Uier](https://github.com/sjoerdvanderhoorn/Uier) - 无代码或低代码的用户体验测试编辑和管理，使用 Selenium 进行测试或 UI 自动化。Uier 倾向于成为Applitools、Endtest、Ghost Inspector、Usetrace、Screenster 和其他许多公司的免费自我托管替代方案。 `Apache-2.0` `Nodejs`


### 静态站点生成

**[`^        返回顶部        ^`](#)**

**请访问 [staticsitegenerators.net](https://staticsitegenerators.net), [staticgen.com](https://www.staticgen.com)**


### 任务管理和待办清单

**[`^        返回顶部        ^`](#)**

_关联: [软件开发 - 项目管理](#软件开发---项目管理), [追踪](#追踪)_

- [Focalboard](https://www.focalboard.com/) - Trello、Notion和Asana的一个开源、自我托管的替代品。它有助于定义、组织、跟踪和管理个人和团队的工作。 ([源码](https://github.com/mattermost/focalboard), [客户端](https://www.focalboard.com/download/personal-edition/desktop/)) `MIT/AGPL-3.0/Apache-2.0` `Nodejs/Go`
- [Kanbana](https://github.com/SrGMC/kanbana) - 创建看板，从扁平的 markdown 文件中跟踪用户和项目。Forked from Crepido. `MIT` `Nodejs`
- [Kanboard](https://kanboard.net/) - 简单和开源的可视化任务看板。 ([源码](https://github.com/kanboard/kanboard)) `MIT` `PHP`
- [myTinyTodo](https://www.mytinytodo.net/) - 以 AJAX 风格管理你的待办事项列表的简单方法。使用 PHP、jQuery、SQLite/MySQL。符合 GTD 标准。 ([Demo](https://www.mytinytodo.net/demo/), [源码](https://github.com/maxpozdeev/mytinytodo/)) `GPL-2.0` `PHP`
- [Nullboard](https://github.com/apankrat/nullboard) - 单页的简约看板；结构紧凑，可读性强，使用快捷。 `BSD-2-Clause` `Javascript`
- [Planka](https://planka.app/) - 开源的Trello替代品。 ([Demo](https://plankanban.github.io/planka/#/), [源码](https://github.com/plankanban/planka)) `MIT` `Nodejs`
- [Restyaboard](https://restya.com/board/) - 开源的类似Trello的看板。 ([Demo](https://restya.com/board/demo), [源码](https://github.com/RestyaPlatform/board)) `OSL-3.0` `PHP`
- [Task Keeper](https://github.com/nymanjens/piga) - 为强大的用户提供的列表编辑器，由一个自我托管的服务器支持。 `Apache-2.0` `Scala`
- [TaskBoard](https://taskboard.matthewross.me/) - 受看板启发的应用程序，用于记录需要完成的事情。 ([Demo](https://taskboard.matthewross.me/demo.html), [源码](https://github.com/kiswa/TaskBoard)) `MIT` `PHP`
- [Taskfreak](https://www.taskfreak.com/original) - 用PHP编写的简单而有效的基于 web 的任务管理器。 `GPL-3.0` `PHP`
- [Taskord](https://taskord.com) - 与创客社区一起在社会上完成事情。 ([源码](https://gitlab.com/yo/taskord)) `MIT` `PHP`
- [tasks.php](https://github.com/lgg/tasks.php) - 简单的任务/Todo 列表，使用 JSON 文本文件进行任务。 `MIT` `PHP`
- [Tasks](https://github.com/m1guelpf/tasks) - 用 PHP、jQuery 和 Bootstrap 编写的简单任务和笔记管理器，使用一个自定义的平面文件数据库。 `MPL-2.0` `PHP`
- [Taskwarrior](https://taskwarrior.org/) - Taskwarrior 是免费的开源软件，可从命令行管理您的待办事项列表。 它灵活、快速、高效且不引人注目。 它完成它的工作然后让你离开。 ([源码](https://taskwarrior.org/download/#git)) `MIT` `C++`
- [thewhitetulip Tasks](https://github.com/thewhitetulip/Tasks) - 基于看板的待办事项列表管理器，用 Go 语言编写。 `MIT` `Go`
- [todo](https://git.mills.io/prologic/todo) - 简单的 Todo 列表管理器。 ([Demo](https://todo.mills.io)) `MIT` `Go`
- [todoMini](https://www.todomini.app/) - 移动友好的零功能TODO列表网络应用。遵循 Unix 哲学。 ([Demo](https://appmini.github.io/todoMini/?demo), [源码](https://github.com/appMini/todoMini)) `GPL-3.0` `PHP/Java`
- [Tracks](https://www.getontracks.org/) - 基于 web 的应用程序，帮助你实施 David Allen 的 [Getting Things Done™](https://en.wikipedia.org/wiki/Getting_Things_Done) 方法。 ([源码](https://github.com/TracksApp/tracks)) `GPL-2.0` `Ruby`
- [Vikunja](https://vikunja.io/) - 组织你的生活的待办事项应用程序。 ([Demo](https://try.vikunja.io/login), [源码](https://kolaente.dev/vikunja/)) `GPL-3.0` `Go`
- [Wekan](https://wekan.github.io/) - 开源的类似Trello的看板。 ([源码](https://github.com/wekan/wekan)) `MIT` `Nodejs`


### 追踪

**[`^        返回顶部        ^`](#)**

_关联: [任务管理和待办清单](#任务管理和待办清单), [软件开发 - 项目管理](#软件开发---项目管理)_

- [Bugzilla](https://www.bugzilla.org/) - 通用的错误跟踪器和测试工具，最初由 Mozilla 项目开发和使用。 `MPL-2.0` `Perl`
- [Bumpy Booby](https://bumpy-booby.derivoile.fr/) - 简单、反应灵敏、高度可定制的 PHP 错误跟踪系统。 ([源码](https://github.com/piero-la-lune/Bumpy-Booby)) `MIT` `PHP`
- [django-todo](http://django-todo.org/) - django-todo 是一个可插拔的、多用户的、多组的、多列表的 todo 和 tickting 系统--一个可重复使用的应用程序，旨在被放入任何现有的 Django 项目。 ([源码](https://github.com/shacker/django-todo)) `BSD-3-Clause` `Python/Django`
- [Erxes](https://erxes.io/install/) - 营销、销售和客户服务平台，旨在帮助企业吸引更多参与的客户。 ([Demo](https://demo.erxes.io/), [源码](https://github.com/erxes/erxes)) `GPL-3.0` `Javascript`
- [Flyspray](https://www.flyspray.org/) - 不复杂的、基于 web 的错误跟踪系统。 ([源码](https://github.com/Flyspray/flyspray)) `GPL-2.0` `PHP`
- [FreeScout](https://github.com/freescout-helpdesk/freescout) - 开源克隆的 Help Scout：基于电子邮件的客户支持应用程序，服务台和共享邮箱。 `AGPL-3.0` `PHP`
- [GlitchTip](https://glitchtip.com) - 开源的错误跟踪应用程序。GlitchTip 收集由你的应用程序报告的错误。 ([源码](https://gitlab.com/glitchtip/glitchtip)) `MIT` `Python`
- [Helpy](https://helpy.io) - Helpy是一个现代的、开源的帮助台客户支持应用程序。功能包括知识库、社区讨论和与电子邮件集成的支持票。 ([Demo](https://demo.helpy.io), [源码](https://github.com/helpyio/helpy)) `MIT` `Ruby`
- [HuBoard](https://github.com/huboard/huboard) `⚠` - 对你的 GitHub 问题进行即时项目管理（直接连接 GitHub API）。 `MIT` `Ruby`
- [MantisBT](https://www.mantisbt.org/) - 自我托管的错误跟踪器，最适合于软件开发。 ([Demo](https://www.mantisbt.org/bugs/my_view_page.php), [源码](https://github.com/mantisbt/mantisbt)) `GPL-2.0` `PHP`
- [OpenSupports](https://www.opensupports.com/) - 多语言 tickting 系统，具有FAQ、角色管理、指标和预制回复功能。 ([Demo](https://www.opensupports.com/demo/), [源码](https://github.com/opensupports/opensupports)) `GPL-3.0` `PHP`
- [osTicket](https://osticket.com/) - 在一个地方管理、组织和归档你所有的支持请求和回应。 ([源码](https://github.com/osTicket/osTicket)) `GPL-2.0` `PHP`
- [Pachno](https://pach.no/) - 用一个能与你和你的团队一起工作，并在你需要时进行调整的工具，把你的团队聚集在一起设计、建造和交付你的项目。 ([源码](https://github.com/pachno/pachno)) `MPL-2.0` `PHP`
- [Request Tracker](https://www.bestpractical.com/rt/) - 一个企业级的问题跟踪系统。 ([源码](https://github.com/bestpractical/rt)) `GPL-2.0` `Perl`
- [Sentry On-Premise](https://github.com/getsentry/onpremise) - 一个强大的错误跟踪平台，具有广泛的语言支持和强大的API。 ([源码](https://github.com/getsentry/sentry)) `BSD-3-Clause` `Python/Django`
- [SIT](https://sit.fyi/) - SCM-agnostic，基于文件，离线优先，不可更改的问题跟踪器。 ([源码](https://github.com/sit-fyi/sit)) `MIT` `Apache-2.0` `Rust`
- [Trudesk](https://trudesk.io/) - Trudesk 是一个开源的服务台/ticketing 解决方案。 ([源码](https://github.com/polonel/trudesk)) `Apache-2.0` `Nodejs`
- [Zammad](https://zammad.org/) - 易于使用但功能强大的开源支持和ticketing 系统。 ([源码](https://github.com/zammad/zammad)) `AGPL-3.0` `Ruby`


### URL 短链

**[`^        返回顶部        ^`](#)**

在托管前，请看URL缩短器的[缺点](https://en.wikipedia.org/wiki/URL_shortening#Shortcomings)。

- [Blink](https://docs.blink.rest) - 为团队提供易于托管、集成了SSO、由CDN驱动的链接缩短器（+解耦分析）。 ([源码](https://github.com/JaneJeon/blink)) `AGPL-3.0` `Nodejs`
- [goshorly](https://git.ucode.space/Phil/goshorly) - 一个在Golang中使用Redis <3的简易自我托管的链接缩短器。 ([Demo](https://gly.one)) `MIT` `Go`
- [Kutt](https://kutt.it) - 一个现代的URL缩短器，支持自定义域名。 ([源码](https://github.com/thedevs-network/kutt)) `MIT` `Nodejs`
- [Link-shortener-bot](https://github.com/tommyku/link-shortener-front-end) `⚠` - 使用Telegram Bot的URL缩短器。 ([Demo](https://t.me/GiveMeShortLinkBot)) `MIT` `Ruby`
- [Link](https://fsh.ee) - 一个最小的、由SQLite支持的URL缩短器。 ([Demo](https://demo.fsh.ee), [源码](https://git.fsh.ee/i/link)) `GPL-3.0` `Go`
- [liteshort](https://github.com/132ikl/liteshort) - 用户友好，实际上是轻量级的，可配置的URL缩短器。 ([Demo](https://ls.ikl.sh)) `MIT` `Python`
- [Lstu](https://github.com/ldidry/lstu) - _Let's SHorten That Url_ - 轻量级URL缩短器。 `WTFPL` `Perl`
- [Polr](https://project.polr.me/) - 现代的、简约的、模块化的、轻量级的URL缩短器。 ([源码](https://github.com/Cydrobolt/polr)) `GPL-2.0` `PHP`
- [reduc.io](https://github.com/ziyasal/reducio) - 用Scala编写的URL缩短器服务，使用Akka-Http和Redis。 `MIT` `Scala`
- [ReducePy](https://github.com/abdullahselek/ReducePy) - 使用Tornado和Redis的URL缩短器服务在Docker和Kubernetes上运行。 `MIT` `Python`
- [schort](https://github.com/sqozz/schort) - 没有登录，没有javascript，只有简短的链接。 ([Demo](https://s.wx0.de)) `CC0-1.0` `Python`
- [Shlink](https://shlink.io) - 具有REST API和命令行界面的URL缩短器。包括官方渐进式网络应用程序和docker图像。 ([源码](https://github.com/shlinkio/shlink), [Clients](https://shlink.io/apps)) `MIT` `PHP`
- [shorturl](https://git.mills.io/prologic/shorturl) - 简单的URL缩短器，有非常小的URL。 ([Demo](https://url.mills.io)) `MIT` `Go`
- [Simple-URL-Shortener](https://github.com/azlux/Simple-URL-Shortener) - KISS URL缩短器，公共或私人（有账户）。极简主义和轻量级。没有依赖性。 ([Demo](https://u.azlux.fr)) `MIT` `PHP`
- [Simply Shorten](https://gitlab.com/draganczukp/simply-shorten) - 一个简单的URL缩短器，只是缩短了链接。 `MIT` `Java`
- [url-shortener](https://github.com/cagataycali/url-shortener) `⚠` - 糟糕的网址缩短器，表情符号和人工智能驱动。 `MIT` `Nodejs`
- [YOURLS](https://yourls.org/) - YOURLS是一套PHP脚本，将允许你运行你自己的URL缩短器。功能包括密码保护、URL定制、小书签、统计、API、插件、jsonp。 ([源码](https://github.com/YOURLS/YOURLS)) `MIT` `PHP`


### VPN

**[`^        返回顶部        ^`](#)**

**请访问 [awesome-sysadmin/VPN](https://github.com/awesome-foss/awesome-sysadmin#vpn)**


### Web Servers

**[`^        返回顶部        ^`](#)**

**请访问 [awesome-sysadmin/Web](https://github.com/awesome-foss/awesome-sysadmin#web)**


### Wikis

**[`^        返回顶部        ^`](#)**

_关联: [Software Development - Documentation Generators](#software-development---documentation-generators)_

_See also: [Wikimatrix](https://www.wikimatrix.org/), [Wiki Engines - WikiIndex](https://wikiindex.org/Category:Wiki_Engine), [List of wiki software - Wikipedia](https://en.wikipedia.org/wiki/List_of_wiki_software), [Comparison of wiki software - Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_wiki_software)_

- [BookStack](https://www.bookstackapp.com/) - BookStack is a simple, self-hosted, easy-to-use platform for organizing and storing information. It allows for documentation to be stored in a book like fashion. ([Demo](https://www.bookstackapp.com/#demo), [源码](https://github.com/BookStackApp/BookStack)) `MIT` `PHP`
- [Cowyo](https://github.com/schollz/cowyo) - Cowyo is a feature-rich wiki for minimalists. ([Demo](https://cowyo.com)) `MIT` `Go`
- [django-wiki](https://github.com/django-wiki/django-wiki) - Wiki system with complex functionality for simple integration and a superb interface. Store your knowledge with style: Use django models. ([Demo](https://demo.django-wiki.org/)) `GPL-3.0` `Python`
- [Documize](https://documize.com) - Modern Docs + Wiki software with built-in workflow, single binary executable, just bring MySQL/Percona. ([源码](https://github.com/documize/community)) `AGPL-3.0` `Go`
- [Dokuwiki](https://www.dokuwiki.org/DokuWiki) - Easy to use, lightweight, standards-compliant wiki engine with a simple syntax allowing reading the data outside the wiki. All data is stored in plain files, therefore no database is required. ([源码](https://github.com/splitbrain/dokuwiki)) `GPL-2.0` `PHP`
- [Gitit](https://github.com/jgm/gitit) - Wiki program that stores pages and uploaded files in a git repository, which can then be modified using the VCS command line tools or the wiki's web interface. `GPL-2.0` `Haskell`
- [Gollum](https://github.com/gollum/gollum) - Simple, Git-powered wiki with a sweet API and local frontend. `MIT` `Ruby`
- [jingo](https://github.com/claudioc/jingo) - Git based wiki engine written for node.js, with a decent design, a search capability and good typography. `MIT` `Nodejs`
- [Mediawiki](https://www.mediawiki.org/wiki/MediaWiki) - MediaWiki is a free and open-source wiki software package written in PHP. It serves as the platform for Wikipedia and the other Wikimedia projects, used by hundreds of millions of people each month. ([Demo](https://en.wikipedia.org/wiki/Main_Page), [源码](https://phabricator.wikimedia.org/diffusion/MW/)) `GPL-2.0` `PHP`
- [MoinMoin](https://moinmo.in/) - Advanced, easy to use and extensible WikiEngine with a large community of users. ([源码](https://github.com/moinwiki/moin-1.9)) `GPL-2.0` `Python`
- [Outline](https://www.getoutline.com/) `⚠` - An open, extensible, wiki for your team. ([源码](https://github.com/outline/outline)) `BSD-3-Clause` `Nodejs`
- [Pepperminty Wiki](https://github.com/sbrl/Pepperminty-Wiki) - Complete markdown-powered wiki contained in a single PHP file. ([Demo](https://starbeamrainbowlabs.com/labs/peppermint/build/)) `MPL-2.0` `PHP`
- [PineDocs](https://github.com/xy2z/PineDocs) - Simple, fast, customizable and lightweight site for browsing files. `GPL-3.0` `PHP`
- [PmWiki](https://www.pmwiki.org) - Wiki-based system for collaborative creation and maintenance of websites. `GPL-3.0` `PHP`
- [Raneto](http://raneto.com/) - Raneto is an open source Knowledgebase platform that uses static Markdown files to power your Knowledgebase. `MIT` `Nodejs`
- [TiddlyWiki](https://tiddlywiki.com/) - Reusable non-linear personal web notebook. ([源码](https://github.com/Jermolene/TiddlyWiki5)) `BSD-3-Clause` `Nodejs`
- [Tiki](https://tiki.org) - Wiki CMS Groupware with the most built-in features. ([Demo](https://tiki.org/Demo), [源码](https://sourceforge.net/p/tikiwiki/code/HEAD/tree/)) `LGPL-2.1` `PHP`
- [TWiki](https://twiki.org/) - TWiki is a Perl-based structured wiki application, typically used to run a collaboration platform, knowledge or document management system, a knowledge base, or team portal. ([Demo](https://twiki.org/cgi-bin/view/Sandbox/WebHome), [源码](http://svn.twiki.org/svn/twiki/)) `GPL-1.0` `Perl`
- [WackoWiki](https://wackowiki.org/) - WackoWiki is a light and easy to install multilingual Wiki-engine. ([源码](https://github.com/WackoWiki/wackowiki)) `BSD-3-Clause` `PHP`
- [Wiki.js](https://wiki.js.org/) - Modern, lightweight and powerful wiki app using Git and Markdown. ([Demo](https://docs.requarks.io)) `AGPL-3.0` `Nodejs`
- [wiki](https://git.mills.io/prologic/wiki) - Simple Markdown based wiki engine. ([Demo](https://wiki.mills.io)) `MIT` `Go`
- [WiKiss](https://wikiss.tuxfamily.org/) - Wiki, simple to use and install. ([源码](https://svnweb.tuxfamily.org/listing.php?repname=wikiss/svn&path=%2F&sc=0)) `GPL-2.0` `PHP`
- [XWiki](https://www.xwiki.org) - Second generation wiki that allows the user to extend its functionalities with a powerful extension-based architecture. ([Demo](https://playground.xwiki.org), [源码](https://github.com/xwiki/xwiki-platform)) `LGPL-2.1` `Java`
- [Zim](https://zim-wiki.org/) - Graphical text editor used to maintain a collection of wiki pages. Each page can contain links to other pages, simple formatting and images. ([源码](https://github.com/zim-desktop-wiki/zim-desktop-wiki)) `GPL-2.0` `Python`


<!-- END SOFTWARE LIST -->

--------------------

## List of Licenses

**[`^        返回顶部        ^`](#)**

- `⚠ ` - Depends on a proprietary service outside the user's control
- `0BSD` - [BSD Zero-Clause Licence](https://opensource.org/licenses/0BSD)
- `AAL` - [Attribution Assurance License](https://opensource.org/licenses/AAL)
- `AGPL-3.0` - [GNU Affero General Public License 3.0](https://www.gnu.org/licenses/agpl-3.0)
- `AGPL-3.0-only` - [GNU Affero General Public License 3.0 only](https://spdx.org/licenses/AGPL-3.0-only.html)
- `Apache-2.0` - [Apache, Version 2.0](https://www.apache.org/licenses/)
- `APSL-2.0` - [Apple Public Source License, Version 2.0](https://opensource.org/licenses/APSL-2.0)
- `Artistic-2.0` - [Artistic License Version 2.0](https://opensource.org/licenses/Artistic-2.0)
- `Beerware` - [Beerware License](https://spdx.org/licenses/Beerware.html)
- `BSD-2-Clause` - [BSD 2-clause "Simplified"](https://opensource.org/licenses/BSD-2-Clause)
- `BSD-2-Clause-FreeBSD` - [BSD 2-Clause FreeBSD License](https://www.freebsd.org/copyright/freebsd-license.html)
- `BSD-3-Clause` - [BSD 3-Clause "New" or "Revised"](https://opensource.org/licenses/BSD-3-Clause)
- `BSD-3-Clause-Attribution` - [BSD with attribution](https://fedoraproject.org/wiki/Licensing/BSD_with_Attribution)
- `BSD-4-Clause` - [BSD 4-clause "Original"](https://spdx.org/licenses/BSD-4-Clause.html)
- `CC-BY-NC-SA-3.0` - [Creative Commons Attribution-NonCommercial-ShareAlike 3.0 International License](https://creativecommons.org/licenses/by-nc-sa/3.0/)
- `CC-BY-SA-3.0` - [Creative Commons Attribution-ShareAlike 3.0 International License](https://creativecommons.org/licenses/by-sa/3.0/)
- `CC-BY-SA-4.0` - [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/)
- `CC0-1.0` - [Public Domain](https://creativecommons.org/about/cc0/)
- `CDDL-1.0` - [Common Development and Distribution License](https://opensource.org/licenses/CDDL-1.0)
- `CECILL-B` - [CEA CNRS INRIA Logiciel Libre](https://spdx.org/licenses/CECILL-B.html)
- `CPAL-1.0` - [Common Public Attribution License Version 1.0](https://opensource.org/licenses/CPAL-1.0)
- `DPL` - [Devblocks Public License 1.0](https://cerb.ai/license/)
- `ECL-2.0` - [Educational Community License, Version 2.0](https://opensource.org/licenses/ECL-2.0)
- `EPL-1.0` - [Eclipse Public License, Version 1.0](https://www.eclipse.org/legal/epl-v10.html)
- `EPL-2.0` - [Eclipse Public License, Version 2.0](https://www.eclipse.org/legal/epl-v20.html)
- `EUPL-1.2` - [European Union Public License 1.2](https://joinup.ec.europa.eu/collection/eupl/eupl-text-11-12)
- `GFDL-1.1-only` - [GNU Free Documentation License v1.1](https://spdx.org/licenses/GFDL-1.1-only.html)
- `GFDL-1.1-or-later` - [GNU Free Documentation License v1.1](https://spdx.org/licenses/GFDL-1.1-or-later.html)
- `GFDL-1.2-only` - [GNU Free Documentation License v1.2](https://spdx.org/licenses/GFDL-1.2-only.html)
- `GFDL-1.2-or-later` - [GNU Free Documentation License v1.2](https://spdx.org/licenses/GFDL-1.2-or-later.html)
- `GFDL-1.3-only` - [GNU Free Documentation License v1.3](https://spdx.org/licenses/GFDL-1.3-only.html)
- `GFDL-1.3-or-later` - [GNU Free Documentation License v1.3](https://spdx.org/licenses/GFDL-1.3-or-later.html)
- `GPL-1.0` - [GNU General Public License](https://www.gnu.org/licenses/gpl-1.0)
- `GPL-2.0` - [GNU General Public License 2.0](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
- `GPL-2.0-or-later` - [GNU General Public License v2.0 or later](https://spdx.org/licenses/GPL-2.0-or-later.html)
- `GPL-3.0-only` - [GNU General Public License v3.0 only](https://spdx.org/licenses/GPL-3.0-only.html)
- `GPL-3.0-or-later` - [GNU General Public License v3.0 or later](https://spdx.org/licenses/GPL-3.0-or-later.html)
- `GPL-3.0` - [GNU General Public License 3.0](https://www.gnu.org/licenses/gpl-3.0.en.html)
- `IPL-1.0` - [IBM Public License](https://opensource.org/licenses/IPL-1.0)
- `ISC` - [Internet Systems Consortium License](https://www.isc.org/downloads/software-support-policy/isc-license/)
- `Lil Licence v1` - [The Lil License v1](https://www.lillicense.org/v1.html)
- `LGPL-2.1` - [Lesser General Public License 2.1](https://opensource.org/licenses/LGPL-2.1)
- `LGPL-3.0` - [Lesser General Public License 3.0](https://opensource.org/licenses/LGPL-3.0)
- `MIT` - [MIT License](https://opensource.org/licenses/MIT)
- `MPL-1.1` - [Mozilla Public License Version 1.1](https://www.mozilla.org/media/MPL/1.1/index.txt)
- `MPL-2.0` - [Mozilla Public License](https://www.mozilla.org/MPL/2.0/index.txt)
- `OSL-3.0` - [Open Software License 3.0](https://opensource.org/licenses/osl-3.0.php)
- `Other` - Non-standard license, usually unique to the project itself.
- `Sendmail` - [Sendmail License](https://www.sendmail.com/pdfs/open_source/sendmail_license.pdf)
- `SSPL-1.0` - [Server Side Public License](https://spdx.org/licenses/SSPL-1.0.html)
- `Unlicense` - [The Unlicense](https://unlicense.org/)
- `WTFPL` - [Do What the Fuck You Want to Public License](http://www.wtfpl.net/about/)
- `Zlib` - [Zlib/libpng License](https://opensource.org/licenses/Zlib)
- `ZPL-1.2` - [Zope Public License 1.2](http://zpl.pub/page/zplv12)
- `ZPL-2.0` - [Zope Public License 2.0](https://opensource.org/licenses/ZPL-2.0)

--------------------

## External Links

**[`^        返回顶部        ^`](#)**

- [Awesome Big Data](https://github.com/0xnr/awesome-bigdata) - Curated list of awesome big data frameworks, resources and other awesomeness.
- [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets) - List of high quality, topic-centric public data sources.
- [Awesome Sysadmin](https://github.com/awesome-foss/awesome-sysadmin) - Curated list of amazingly awesome open source sysadmin resources.
- Lists of software aimed at privacy and decentralization in some form: [PRISM Break](https://prism-break.org/en/), [privacytools.io](https://www.privacytools.io/), [Alternative Internet](https://redecentralize.github.io/alternative-internet/), [Libre Projects](https://libreprojects.net/)
- [Easy Indie App](https://easyindie.app) - Apps that can be self-hosted in a few clicks.
- Dynamic Domain Name services: [Afraid.org](https://freedns.afraid.org/domain/registry/), [Pagekite](https://pagekite.net/)
- Communities/forums: [/r/selfhosted](https://www.reddit.com/r/selfhosted), [IndieWeb](https://indieweb.org/)
- Mirrors: [GitHub.com](https://github.com/awesome-selfhosted/awesome-selfhosted), [Gitlab.com](https://gitlab.com/awesome-selfhosted/awesome-selfhosted)
- [Track Awesome Selfhosted](https://www.trackawesomelist.com/awesome-selfhosted/awesome-selfhosted/) - Get the latest updates of awesome-selfhosted.

--------------------

## Contributing

Contributing guidelines can be found in [.github/CONTRIBUTING.md](.github/CONTRIBUTING.md).

## Authors

The list of authors can be found in [AUTHORS.md](AUTHORS.md).

## License

This list is under the [Creative Commons Attribution-ShareAlike 3.0 Unported](LICENSE) License.
