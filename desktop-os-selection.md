In [this excellent video](https://www.youtube.com/watch?v=z1-yuolwrVs) 
a guy called Ahmed summarizies his reasoning behind choosing his operating system, 
that are pretty much in accordance with mine. Although he speaks arabic, 
you'll get the picture by the sketches on his chalkboard:  

* It is in your interest to have an OS that is free and open source, not proprietary
* There is no reason to support a corporation, when you can support individuals instead  
* I want to choose the programmes that I use, why should the OS make this choice for me?  
* It should keep being as I want it to be, instead of changing according to every trend
* You as the user should have control over your system, not getting controlled by it
* Under your hands it should take the shape you wish instead of forcing its shape on you
* It should be easy to use, although you may need to learn something new at first
* It should be up-to-date and enable you to automate updates w/o to break your system

If you are concerned about security, which you should be on principle, 
you may also want to read what the well-known security researcher madaidan 
has to say about [choosing the right distro](https://madaidans-insecurities.github.io/guides/linux-hardening.html#choosing-the-right-distro)

Thus, bonus points if it...
* Does not use systemd
* Uses musl instead of glibc
* Uses LibreSSL instead of OpenSSL

Both come to the conclusion, that [Void](https://voidlinux.org/) may be the most viable choice. 
Only Void (or something like gentoo, in which you configure everything yourself) 
is fulfilling (almost) all the requirements above. Almost, because they switched 
from LibreSSL back to OpenSSL.

* It is easy to setup  
* It is free and open source, developed by individuals
* It does not ship all kinds of programmes that you may not need
* It is rolling-release, thereby much less likely to break than arch
* Its package manager [xbps](https://docs.voidlinux.org/xbps/index.html) is probably the best
* It does not use systemd, but runit
* It offers a musl build 

