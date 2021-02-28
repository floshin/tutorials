## qb setup on arch


### Install qutebrowser (qb)
```
sudo pacman -S qutebrowser
```

### Privacy settings 

#### Add improved adblocking
```
sudo pacman -S python-adblock
```
When in qb, run
```
:adblock-update
```
TODO: somehow add better list and  
some german stuff from ublock?  

#### Always use private mode  

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

This will deactivate the recording of visited pages (history).  
I neither want nor need such a recording. 

##### Use bookmarks instead

When I want to remember a page, I use bookmarks:  
```
:bookmark-add    // add a bookmark
:bookmark-del    // delete a bookmark
:bookmark-list   // list bookmarks
```
When you type, qb will suggest urls from your bookmark list.  
That means, it is really easy to revisit your saved pages,  
while you won't need a history that you may want to delete.  


### Basic Individualization  

#### Choose your search engine

Enter the settings page.
Change the value of  
```
url.searchengines
```
to your search engine of choice.   
I recommend ...  TODO  

#### Set a startpage of choice

Enter the settings page.  
Change the value of  
```
url.default_page
```
to an url of your choice.   
