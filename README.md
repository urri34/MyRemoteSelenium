# RemoteSelenium

Contains the python scripts I use to open a Chrome Seleniumn driver forever. Connect to this opened chrome and load a webpage

## OpenSeleniumForEver.py:

It opens a chrome selenium session with selenium and just keep it open. It stores all necessary data in order to connect to this chrome in a local SQLite file.

## LoadForEveredSelenium.py

It connects to an already opened chrome selenium session (based in data stored in the SQLite file) and load google webpage.
