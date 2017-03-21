1.The need for python version:

	Python-3.5.2 or upper



2.The need for support library:

	import re
	import requests
	import sys
	import queue
	import threading
	import getopt
	import sqlite3
	import random
	import urllib.parse
	import time



3.The need for database:

	Sqlite3-3.11.0 or upper



4.Other requirements:

	Need to build folder named by "url"
	Need to build text file named by "url.txt" to store sites with not any empty row



5.Example:
	
	Spider for url  -version-1.0.3 --Written by Wu Jiayuan
		
		-h   Print the information of help
		-f   specified site file was crawling
		-k   specified keyword in url
		-t   specified the count of threads
		-l   specified by crawling site depth
		-r   specified the frequency of crawling
		-m   specified the mode of store 'text' or 'db'
		
	Exampe:python3 Spider.py -f url.txt



6.Notice for default value:

	hreads		=>	"1"
	keyword		=>	""
	site file	=>	"./url.txt"
	level		=>	"2"
	rate		=>	"100"

