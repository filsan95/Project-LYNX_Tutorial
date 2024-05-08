# LYNX - A GUIDE TO SETUP FOR MACS

## Introduction
Lynx is a text-based browser, meaning that it does not display images or video content, which can be assessed through the terminal. So why would you want to use Lynx, as opposed to the modern graphic web browsers (ie. Opera, Mozilla, Chrome etc.)?
1. Because it is light and fast
2. Because it bypasses all of the advertising material (which are graphical in nature)
3. Because it looks super rad to surf the web using a terminal
<p> This document serves as a brief guide on how to set-up and use the Lynx browser. To learn morn about Lynx checkout this <a href='https://en.wikipedia.org/wiki/Lynx_(web_browser)'>Wikipedia</a> article for a quick read, or visit the <a href='https://lynx.invisible-island.net/'> Lynx </a> website to find information on releases, and additional documentation.

## Set-up Guide
1. Install the Lynx browser via terminal
   
	```
	brew install lynx
	```
     If you do not have homebrew install on your device, follow the step in the link provided: https://brew.sh

2. On your terminal, check where your Lynx file is located
	```
	which lynx
	```
     Output:
	  ```
	 /usr/local/bin/lynx
	  ```

## Browsing Guide
1. Run the Lynx browser
   
     For a quick search run: (Note: This method only works when searching for specific websites, and does not hold for natural language search)
	  ```
	  lynx <insert web address or website name w/o the brackets>
	  ```
     Alternatively, run the line below and press 'g' on your keyboard to make a search. For instance, you can visit Duck Duck Go or Google simply by typing in Duck Duck Go or Google after the 'URL to open:' prompt.

	  ```
	  lynx
	  ```

## Granting Cookie Access
One reoccuring issue you will encounter are a series of prompts asking for permission on cookies for every search. This is because most modern website on the web require or use cookies. Given that the default setting for LYNX is to disable cookies, to bypass the persistant prompts, and for ease of use, it is highly recommended to permananlty enable cookies on your browser. To do so, take the following steps. 

 

