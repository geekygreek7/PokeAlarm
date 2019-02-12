![PokeAlarm](https://i.imgur.com/JN85gpz.png)

[![Donate to original repo](https://img.shields.io/badge/Donate-Patron-orange.svg)](https://www.patreon.com/bePatron?u=5193416)
![Python 2.7](https://img.shields.io/badge/python-2.7-blue.svg)
![license](https://img.shields.io/github/license/PokeAlarm/PokeAlarm.svg)

PokeAlarm is a highly configurable application that filters and relays alerts about Pokemon Go to your favorite online service, allowing you to be first to know of any rare spawns or raids.

### What's in this specific fork?
Excuse my mess as this is my first fork and really my first git repo I've ever done. 
This version of PokeAlarm is my own optimized version for RDM and includes some of my current alarms and filter examples that many have asked for (including the great league and ultra league filters). 

Aside from that there are edits from the original branch that make it possible to work with RDM including edits to the following files:  
-data/base_stats.json  
-locales/en.json  
-PokeAlarm/Events/MonEvent.py  
-PokeAlarm/Manager.py  

## How to Install:
1. brew install python@2 (v2.7 - if you don't have it already)  
2. pip2.7 install -r requirements.txt --upgrade  
3. Edit your config file and rename it 'config.ini'. (This includes creating your specific alarms/filters and adding them to your config, editing the geofence.txt file if you decide to use a geofence, etc).  

That's it! 




## What exactly is PokeAlarm?
PokeAlarm is an easy to use yet highly configurable webserver designed to receive webhook data (via POST requests) from a scanner. PokeAlarm then filters data, and relays it into one of your favorite online services such as Discord, Twitter, and more. With PokeAlarm, you'll instantly know about every rare spawn or legendary raid that spawns on your scanners. It's highly configurable, allowing the user to define custom messages and filter alerts based on numerous criteria.

## Looking for Help?

#### Wiki
Head on over to the [**PokeAlarm Wiki**](http://pa.readthedocs.io/en/master/) to find detailed instructions on setting up and configuring PokeAlarm. You can find the table of contents on the right!

#### PokeAlarm Discord
Before visiting your discord channel, check both the [Wiki](http://pa.readthedocs.io/en/master/) and the [FAQ](https://github.com/PokeAlarm/PokeAlarm/wiki/faq). If you still can't find what you are looking for, try our [**Discord channel**](https://discord.gg/S2BKC7p) - but make sure you read the **#rules** channel or risk getting banned!

#### Github
Have an idea for a new feature? Think you found a bug? Head over to our [Github](https://github.com/PokeAlarm/PokeAlarm/issues/new) and open an 'Issue' ticket. Make sure to follow the template completly, or else your issue will be closed without comment.

## Want to contribute?
Besides financial support, you can also do your part to help PA grow. Feel free to submit PR's to our [Github](https://github.com/PokeAlarm/PokeAlarm/issues/new). You can also suggest changes to the Wiki on our [Wiki Github](https://github.com/PokeAlarm/PokeAlarmWiki). If you find a mistake but don't have the skill to fix it, feel free to open an 'Issue' on the appropriate Github page.
