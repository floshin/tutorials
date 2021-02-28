qb setup on arch
-------------------------

(1) Install qutebrowser (qb)
```
sudo pacman -S qutebrowser
```

(2) Basic Privacy settings 

* Add improved adblocking:
```
sudo pacman -S python-adblock
```
When in qb, run
```
:adblock-update
```
TODO: somehow add better list and  
some german stuff from ublock?  

* Always use private mode:  

When in qb, run  
```
:set
```
to enter the settings page. 
Change the value of  
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

(3) Basic Individualization  

* Choose your search engine:  

Enter the settings page.
Change the value of  
```
url.searchengines
```
to your search engine of choice.   
I recommend ...  TODO  

* Set a startpage of choice:  

Enter the settings page.  
Change the value of  
```
url.default_page
```
to an url of your choice.   
