# raven
raven is a Linkedin information gathering tool that  can be used by pentesters to gather information about an organization employees using Linkedin.

Please do not use this program to do stupid things. The author does not keep any responsability of what damage has been done by this program.

USE IT AT YOUR OWN RISK.

# Installation

* Run setup.sh as root
* Adjust Linkedin credentials in raven.py

# Documentation

Usage of this is application is pretty simple.
It requires at least three parameters. The first one is the company name , the second one is the country initials and the domain name

# Usage

usage: raven.py [-h] -c COMPANY -s STATE -d DOMAIN [-p PAGES]

Raven - LinkedIn Information Gathering Tool


      -c COMPANY, --company COMPANY       Input the Company name. Ex: Pizzahut
                        
      -s STATE, --state STATE             Input the State initials. Ex: uk , al , etc...
                        
      -d DOMAIN, --domain DOMAIN          Input the domain name. Ex: gmail.com
                        
      -p PAGES, --pages PAGES             Number of google pages to navigate. Ex: 3
                        

For example , if the company that you want to search is Evil Corp and the state is Albania the parameters would be:


    python raven.py -c 'Evil Corp' -s al -d evilcorp.al

If you are not sure what the state is you can put www .

You can also specify how many pages of Google Search you want to search  with the -p parameters

    python raven.py -c 'Evil Corp' -s al -d evilcorp.al -p 3

The command above will search for results on 3 first pages of google.

# Features

* Automatically check found emails in haveibeenpwned.com
* Output in CSV format (For using with GoPhish)

# Screenshots

Screenshot - 1

![ScreenShot](https://raw.githubusercontent.com/0x09AL/raven/master/screenshots/screenshot-01.png)


Screenshot - 2

![ScreenShot](https://raw.githubusercontent.com/0x09AL/raven/master/screenshots/screenshot-02.png)


Screenshot - 3

![ScreenShot](https://raw.githubusercontent.com/0x09AL/raven/master/screenshots/screenshot-03.png)


Screenshot - 4

![ScreenShot](https://raw.githubusercontent.com/0x09AL/raven/master/screenshots/screenshot-04.png)


Screenshot - 5

![ScreenShot](https://raw.githubusercontent.com/0x09AL/raven/master/screenshots/screenshot-05.png)
