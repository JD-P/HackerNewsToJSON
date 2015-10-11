# Hacker News to JSON #

Synchronize saved stories on Hacker News with Pinboard.in.

The script parses the saved stories page on HN (http://news.ycombinator.com) and, for each link on each page of the saved stories history it outputs an entry to a JSON document with information taken from the Hacker News API. (https://github.com/HackerNews/API)

The script is meant to be launched from the command line

Originally developed on iPad by Luciano Fiandesio with the awesome Pythonista (http://omz-software.com/pythonista/)
and modified for JSON output by John David Pressman.

## How to use ##

`python hn2json.py [hn user] [hn password] [JSON filename]`

## TODO ##

- Actually save stories to a JSON format.
- Use the HN API
- Parse also the second page of HN saved stories
- Better handling of the script's input parameters
