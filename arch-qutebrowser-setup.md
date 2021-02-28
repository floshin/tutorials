qb setup on arch
-------------------------

(1) Install qutebrowser (qb):
```
sudo pacman -S qutebrowser
```

(2) Add improved adblocking:
```
sudo pacman -S python-adblock
```
When in qb, run
```
:adblock-update
```
TODO: somehow add better list and  
some german stuff from ublock?  


(3) Always use private mode:  

When in qb, run  
```
:set
```
change 
```
content.private_browsing
```
from false to true.  

Doing so will deactivate recording of visited pages (history).  
I neither want nor need such a recording. When I want to  
remember a page, I use bookmarks to save them:  
```
:bookmark-add    // add a bookmark
:bookmark-del    // delete a bookmark
:bookmark-list   // list bookmarks
```

(4) Choose your search engine:  
TODO

(5) Set a startpage of choice:  
TODO

