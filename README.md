<img src="./webroot/rooster.png" href="http://icons8.com/" alt="Gale Application Server" width="128"/>

# Gale Samples Repository
 Sample scripts to exercise [Gale](https://github.com/elasmojs/gale). Gale is a small footprint, batteries included Javascript application server built with Rust. It comes along with an out of box Javascript support along with default set of commonly used APIs. It is currently just a single executable of about ~6 MB in size with zero dependencies.

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
