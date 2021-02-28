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
When in qb, run `:adblock-update`

TODO: somehow add better list and  
some german stuff from ublock?  

#### Always use private mode  

When in qb, run `:set` to enter the settings page.  
Change the value of `content.private_browsing` from `false` to `true`.  

This will deactivate the recording of visited pages (history).  
I neither want nor need such a recording. I use bookmarks instead.  
To list, add or delete bookmarks, use the following commands:  
```
:bookmark-add    // add a bookmark
:bookmark-del    // delete a bookmark
:bookmark-list   // list bookmarks
```
When you type, qb will suggest urls from your bookmark list.  
That means, it is really easy to revisit your saved pages,  
while you won't need a history that you may want to delete.  


### Basic Individualization  

#### Simplify by autohide

I have no need to see tabs or the status bar when not currently in use.  
Therefore you can autohide them by default and set a duration of your choice.  
Whenever you switch your tabs or use the status bar they will be displayed.  

Enter the settings page.  
Change the value of `tabs.show` from `always` to `switching`.  
Change the value of `tabs.show_switching-delay` to your liking (1500 for me).  
Change the value of `statusbar.show` from `always` to `in-mode`.  

Your window is now completely clean and makes full use of your screen.  
But one more reason to learn the basic keybindings, which is rewarding.  

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
