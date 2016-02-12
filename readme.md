# SANS CTI 2016 Presentation: Community Intelligence & Open Source Tools: Building an Actionable Pipeline

## Summary

Every vendor will tell you the solution to stopping the most basic to the most
advanced threats is simple: buy their offering. While vendor services can be
useful, and sometimes COTS tools are efficent, there are alternatives. Free or
almost free threat intelligence services are popping up constantly and seemingly
every day there's a new promising open source tool.

So what does it take to build intelligence-driven incident response with open
source tools and community threat information? We'll walk through the process
of integrating community threat information with Facebook's osquery in the
detection and investigation phases of an incident as well as a few important open
source projects. Additionally we'll talk about contributing back to the community,
both tools and information, and how we can build a sustainable ecosystem.

## Technology

This presentation was built to be presented with [DeckSet](http://www.decksetapp.com/) using the Fira white theme. It can be viewed as presented in [the PDF](./sans_cit_2016.pdf).

## Outline

### Introduction
- Me
- History
- GitHub
- Problem Statement

### Body
- Direction
- Collection: Twitter, Email, Feeds, Ongoing Incidents, Manual (Google Alerts & Scumblr)
- Exploitation: Jager & Cacador
- Analysis: Threat Note, Maltego, & FIR
  - Enrichment: Whois, PassiveTotal, Shodan, & VirusTotal
- Dissemination:
  - Now: Manual
  - Soon: Reports/Investigations, osquery, Bro, Hubot, Applications
- Feedback: :boom:

### Conclusion
- Lessons
  - Integration
  - High Value Investments
  - Learn to Code
  - Unix Philosphy
  - Open Formats
- Future Goals
- Questions

## Tools
- Netflix/Scumblr
- sroberts/jager
- sroberts/cacador
- defpoint/threat_note
- Paterva Maltego
- certsocietegenerale/FIR
- github/Hubot
- bro/bro
- facebook/osquery

## Service
- VirusTotal
- Shodan
- PassiveTotal
