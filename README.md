# libnmap

[![Build Status](https://travis-ci.org/savon-noir/python-nmap-lib.png)](https://travis-ci.org/savon-noir/python-nmap-lib)

## Code status
A few basic stuff need to be added (check TODO, please forkme and issue pull
requests)

## What

libnmap is a python toolkit for manipulating nmap. It currently offers the following modules:
- process: enables you to launch nmap scans
- parse: enables you to parse nmap reports or scan results (only XML so far) from a file, a string,...
- report: enables you to manipulate a parsed scan result and de/serialize scan results in a json format
- diff: enables you to see what changed between two scans
- common: contains basic nmap objects like NmapHost and NmapService. It is to note that each object can be "diff()ed" with another similar object.
- plugins: enables you to support datastores for your scan results directly in the "NmapReport" object from report module
    - mongodb: only plugin implemented so far, ultra basic, for POC purpose only
    - couchdb: todo
    - sqlalchemy: todo
    - elastic search: todo
    - csv: todo

How
===
Will be added very soon but I have to go get some sushis first :)