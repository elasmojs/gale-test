<img src="./webroot/rooster.png" href="http://icons8.com/" alt="Rooster Personal Web Server" width="128"/>

# Rooster Test Repository
 Test scripts to exercise [Rooster](https://github.com/elasmojs/rooster). Rooster is a personal web server with Rust. This is an experimental project created as an attempt to scratch a personal itch but with growing ambitions. It is currently a single executable of about ~3 MB in size.

## Installation
- Windows 64
	- Just clone and double click the rooster-win64.exe
	- /testfolder
		- test of a folder enabled with default 'index.html'
	- /folderwithnodefault
		- test of a folder without default 'index.html' 
	- /testscripts/testsimple
		- tests a simple server script which returns sum of two numbers as a JSON response
	- /testscripts/testlibcall
		- tests a simple server script which uses a library call to ./lib/calc.js
	- /testscripts/testexternallib
		- testa a server script which loads multiple standard third party javascript libraries
