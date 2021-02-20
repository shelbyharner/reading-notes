# Read 13 - Local Storage

## THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS

  - Web applications don't typically have persistent local storage. They can use cookies but there are complications. 
    - cookies included with HTTP requests slow down the application from sending the same data over and over, also the data is unencrypted
    - cookies are limited to about 4KB of data

  - Ultimate goal for storage is to have: 
    - a lot of storage space
    - on the client
    - persistent beyond page refreshing
    - not transmitted on the server

  - Early on, Internet Explorer was the most mainstream browser. (before browser wars)
    - Microsoft created DHTML behaviors, one of which included was userData. 
    - userData lets web pages store up to 64KB of data per domain
  
  - Adobe created Flash 6 - aka local shared objects - allows Flash objects to store up to 100KB of data per domain
  - An early prototype of Flash to JS bridge was called AMASS, but was limited by Flash
    - Flash 8 then came out and this option became better and faster
    - AMASS was rewritten and was integrated into the Dojo Toolkit

  - Google then launched "gears", an open source plug-in that aimed at providing more compatible storage options.
  - Many of these early options either only worked with a single browser or required a plug-in

  - HTML5 storage (or web storage/local storage/DOM storage) is a way for a webpage to store key information within the client web browser.
    - Data persists like cookies, even when you navigate away from the page
    - Data is never transmitted to the remote server, unless done manually
    - Implemented natively in web browsers, so is available when third party plug-ins are not
    - Written in JS as "localStorage" object
      - http://diveinto.html5doctor.com/detect.html#modernizr

  - HTML5 storage is based on key/value pairs
    - store and retrieved by the same key word
    - data can be anything supported by JS (string, boolean, integer, float)
    - data is stored as a string
  - localStorage.setItem - to store an item
  - localStorage.getItem - to retrieve an item
  - clear() to remove all items from storage
  - You can track changes using a StorageEvent object