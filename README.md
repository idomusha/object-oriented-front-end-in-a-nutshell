# Object-oriented front-end in a nutshell

### A repository of the presentation slides.

## Presentation

[See object-oriented front-end in a nutshell](http://idomusha.github.io/object-oriented-front-end-in-a-nutshell/)

## Export slides as PDF

### Install
Download DeckTape source:
````
curl -L https://github.com/astefanutti/decktape/archive/v1.0.0.tar.gz | tar -xz --exclude phantomjs
````

Change into the decktape directory:
````
cd decktape-1.0.0
````

Download PhantomJS executable:

DeckTape currently depends on a forked version of PhantomJS. What follows is a list of pre-compiled binaries for various platforms.
````
# Windows (MSVC 2013), for Windows Vista or later, bundles VC++ Runtime 2013
curl -L https://github.com/astefanutti/decktape/releases/download/v1.0.0/phantomjs-msvc2013-x86.exe -o phantomjs.exe
# Mac OS X (Cocoa), 64-bit, for OS X 10.6 or later
curl -L https://github.com/astefanutti/decktape/releases/download/v1.0.0/phantomjs-osx-cocoa-x86-64 -o phantomjs
# Linux (static build), 64-bit, requires fontconfig (CentOS) or libfontconfig (Debian, Ubuntu)
curl -L https://github.com/astefanutti/decktape/releases/download/v1.0.0/phantomjs-linux-x86-64 -o phantomjs
````
Place the executable into the root of the repository

Set the execute permission (non-Windows OS binaries only):
````
chmod +x phantomjs
````

### To generate PDF presentation

Change into the decktape directory:
````
cd decktape-1.0.0
````

Launch the export command (replace the source URL and the destination path):
```
./phantomjs decktape.js generic https://webslides.tv test.pdf
```

* * *

All presentations use [WebSlides](https://github.com/webslides/WebSlides) from [@jlantunez](https://twitter.com/jlantunez)
