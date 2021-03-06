In [this excellent video](https://www.youtube.com/watch?v=z1-yuolwrVs) 
a guy called Ahmed summarizies his reasoning behind choosing his operating system, 
that seem pretty much in accordance with mine. Although he speaks arabic, 
you'll get the picture by the sketches on his chalkboard:  

* It is in your interest to have an OS that is free and open source, not proprietary
* There is no reason to support a corporation, when you can support individuals instead  
* I want to choose the programmes that I use, why should the OS make this choice for me?  
* It should keep being as I want it to be, instead of changing according to every trend
* You as the user should have control over your system, not getting controlled by it
* Under your hands it should take the shape you wish instead of forcing its shape on you
* It should be up-to-date and enable you to automate updates w/o to break your system
* It should be easy to use, although youThus, bonus points if it...

 may need to learn something new at first

If you are concerned about security, which you should be on principle (because why 
wouldn't you prefer to have a more secure system?), you may also want to read what the 
well-known security researcher madaidan has to say about [choosing the right distro](https://madaidans-insecurities.github.io/guides/linux-hardening.html#choosing-the-right-distro).

Thus, bonus points if it...
* Does not use systemd
* Uses musl instead of glibc
* Uses LibreSSL instead of OpenSSL

Both come to the conclusion, that [Void](https://voidlinux.org/) may be the most viable choice. 
Only Void (or something like gentoo, in which you configure everything yourself) 
is fulfilling (almost) all the requirements above. Almost, because they switched 
from LibreSSL back to OpenSSL.

* It is relatively easy to setup(*)
* It is free and open source, developed by individuals
* It is lightweight and does not ship programmes you may not need
* It is rolling-release but thereby less likely to break than (even) arch
* Its package manager [xbps](https://docs.voidlinux.org/xbps/index.html) is probably the best
* It does not use systemd, but runit (in the future [it may use s6-rc](https://www.reddit.com/r/voidlinux/comments/lz84k6/66_and_s6rc_an_alternative_init_system_for/))
* It offers a musl build 

In this sense, Void is the current operating system of choice. 

(* I think it could be more user-friendly, while still being very simple, if it would offer an installation like ArchLabs, if it would make partitioning easier and more self-explanatory and by offering you an easy way to encrypt the system by default)
