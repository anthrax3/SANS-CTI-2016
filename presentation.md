![](imgs/iStock_000009299805Large_for_cyber1.jpg)
## [fit] Community Intelligence
## [fit] & Open Source Tools
### [fit] __Building an Actionable Pipeline__

---

# Intro

---

![](imgs/2bd8171083c29e756504eb93e74143ae.jpg)
# Me__:__
## Scott J Roberts
## @sroberts
#### _Han Solo is my Spirit Animal_

^ Most places at least.

---

## _What do CTI industry analysts say?_
![inline](imgs/rick.png)

> "When it comes to eating @sroberts is a thought leader up & to the right on all quadrants!"

~ [@rickhholland](https://twitter.com/rickhholland/status/694704632677933057)

---

## DFIRing Since __2006__
## CTIing Since __2007__
## Deving Since __2009__

---

![inline](imgs/hail-octdra.png)

---

![inline 100%](http://chiphouston.com/wp-content/uploads/2015/03/work_in_progress_by_dejco-d3hd34u.png)

---

![](imgs/tinker-tailor-soldier-spy-file-room.jpg)
## The Problem

### We are spinning up considerable new telemetry using open source tools and we need to feed those tools with actionable __intelligence__.

---

![](imgs/macbook.jpg)

# The __Other__ Problem

![inline](imgs/Screen Shot 2016-01-31 at 3.54.55 PM.png)

---

# _Pocket_
![](imgs/Screen Shot 2016-02-03 at 1.27.51 AM.png)

---

# _Chat_
![](https://s3.amazonaws.com/testlio/wp-content/uploads/2015/01/slack-1024x1024.png)

---

![](http://psdcovers.s3.amazonaws.com/wp-content/uploads/2014/05/NOTEBOOK001r.jpg)
# Note Books

---

# And all the other sources...

---

![original](imgs/palantir.png)
![](http://i.imgur.com/aKnW6bl.gif)

# __$$$$__

---

## [fit] So I did what anyone with a little Python experience does
## [fit] __I built my own...__

---

## [fit] And I built my own again...
## [fit] _And another time..._
## [fit] In the end I built about __5 or 6__...

---

## [fit] _They all sorta sucked..._ :cry:

---

![](http://cdn.zmescience.com/wp-content/uploads/2015/01/Thomas-Edison.jpg)

> "I have not failed. I have found I've just found 10,000 ways that won't work."
## ~ Thomas Edison

---

![](imgs/dr-strangelove-ken-adam-film-set-war-room.jpeg)
## [fit]◉ __Direction__

---

![](imgs/adc23d3d-350f-441a-9301-25e534bf4156.jpg)
# [fit]Breath __vs.__ Depth

---

## [fit] __OSX__, __Linux__, & __GitHub__
## [fit] centric threats

---

![](imgs/pg-46-espionage-getty.jpg)
## [fit]◉ __Collection__

---

## Twitter
## Email Lists
## Feeds
## Ongoing Incidents
## Manual

^ Google Alerts, Scumblr

---

![](imgs/456034813.jpg)
## [fit]◉ __Exploitation__

---

## [fit] _To Use a Technical Term_
## [fit] Indicator Extraction
## [fit] __sucks__...

---

## [fit] But we did it __anyway__...[^1]

[^1]: YOLO!!!

---

## [fit] Jager & Caçador [^2]

[^2]: _Look it means hunter in Portuguese._

---

![inline](imgs/Screen Shot 2016-02-03 at 8.29.52 AM.png)

---

# Command
```
$ pbpaste | cacador | jq '.[]'
```

---

# Output
![inline](imgs/Screen Shot 2016-02-03 at 8.28.06 AM.png)

---

# Tada!!!

![inline](imgs/Screen Shot 2016-02-03 at 9.11.20 AM.png)

---

![](imgs/scada.jpg)
## [fit]◉ __Analysis__

---

## Threat Note

![](imgs/Screen Shot 2016-02-03 at 9.15.51 AM.png)

---

![](imgs/Screen Shot 2016-02-03 at 9.21.18 AM.png)

---

![](imgs/Screen Shot 2016-02-03 at 10.48.42 AM.png)

---

![](imgs/Screen Shot 2016-02-03 at 10.48.37 AM.png)

---

![](imgs/Screen Shot 2016-02-03 at 9.21.50 AM.png)

---

![](imgs/Screen Shot 2016-02-03 at 9.22.00 AM.png)

---

![](imgs/Screen Shot 2016-02-03 at 9.21.22 AM.png)

## _**Enrichments**_
### Whois
### PassiveTotal
### Shodan
### VirusTotal

![](imgs/Screen Shot 2016-02-03 at 9.29.55 AM.png)

---

![](imgs/Screen Shot 2016-02-03 at 9.29.55 AM.png)

---

![](imgs/Screen Shot 2016-02-03 at 9.30.21 AM.png)

---

## [fit] Maltego
![](imgs/Screen Shot 2016-02-03 at 9.47.06 AM.png)

---

# [fit] Fast
# [fit] Incident
# [fit] Response
![](imgs/incident_details.png)

---

![](imgs/IntelligenceNetworks.jpg)
## [fit]◉ __Dissemination__

---

# __Now__
## Manual

---

## __Soon:tm:__
### osquery & Bro Intelligence
### Chat with Hubot
### Intelligence Reports
### Application Integration

---

![](imgs/o-ECONOMIC-ESPIONAGE-facebook.jpg)
## [fit]◉ __Feedback__

---

# [fit] _The Result_

---

![](http://media3.giphy.com/media/GLdnQcaK0taZW/giphy.gif)

---

##__*The _(REAL)_ Result*__
### A (somewhat) automated system providing centralized _threat data_ & _intelligence management_ made up of a __single source of truth supported by purpose built collection, processing, and analysis integrations__.

---

# [fit] _Lessons_

---

# [fit] This isn't __easy__
# [fit] _But **parts** are._

---

## [fit] Threat Intel Tools Work
## [fit] When They're __Integrated__
## ~
## [fit] collection __|__ analysis __|__ dissemination

---

![](imgs/ac9585a9dfb1448cb087e3771249d106.jpg)
# [fit] _High Value Investments_

### __Tool:__ Paterva Maltego ~ $760
### __Service:__ PassiveTotal ~ $??
### __Learning:__ Introducing Python ~ $33

---

![](http://netdna.webdesignerdepot.com/uploads/2012/11/code.jpg)
# [fit] Learn to __Code__

---

![](https://upload.wikimedia.org/wikipedia/commons/8/8f/Ken_Thompson_\(sitting\)_and_Dennis_Ritchie_at_PDP-11_\(2876612463\).jpg)
# [fit] __Unix Philosophy__
### Small is beautiful
### Make each program do one thing well
### Portability over efficiency
### Store data in flat files
### Make every program a filter

---

![](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c9/JSON_vector_logo.svg/2000px-JSON_vector_logo.svg.png)
# [fit] Data formats matter less than format openness
# [fit] CSV __&__ JSON

---
![](imgs/enemy-of-the-state-51ccb1c120329.jpg)
## [fit] _Perfect_
## __Is the Enemy Of__
## [fit] _Good_

---

![](imgs/dn28374-1_800.jpg)
## __*The Future:*__
### Scaling Up Collection & Storage
### Expanded Threat_Notes APIs & Integrations
### Reputation & Fuzzy Indicators

---

# __*Links*__
github.com/defpoint/threat_note  
github.com/certsocietegenerale/FIR
github.com/sroberts/jager
github.com/sroberts/cacador
github.com/kbandla/APTnotes
github.com/armbues/ioc_parser
github.com/ivanlei/threatbutt

---

## __*Thanks*__
#### _Threat Note:_ @brianwarehime
#### _FIR:_ @thomchop_
#### _APTNotes:_ @kbandla
#### _Jager:_ @kylemaxwell, @kbandla, & @deadbits

---

## [fit] __*Questions???*__

### ~

### @sroberts
### http://sroberts.github.io
