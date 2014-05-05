#Meetup-Twitter-Scraper

A simple scraper for getting the Twitter handles of everybody in a Meetup.com group page.

##Setup

First, make sure you have Ruby 1.9+ and Bundler installed on your computer. Next, run:

```bash
bundle install
```

##Usage

Run from the command line. Takes two arguments: the group's member page URL and the output file (will be newline delimited).

Ex:
```bash
ruby scrape.rb 'http://meetup.com/{group-name}/members' 'output.txt'
```

##Disclaimer

Don't do anything stupid or irresponsible. The default is a 1 second pause between each request, but don't overload Meetup.com (or Twitter) with excess requests and/or bandwidth usage. Always hack responsibly.
