## THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS :

**What Are Cookies?**

Cookies are text files with small pieces of data — like a username and password — that are used to identify your computer as you use a computer network. Specific cookies known as HTTP cookies are used to identify specific users and improve your web browsing experience.

**But they have three potentially dealbreaking downsides:**

1- Cookies are included with every HTTP request, thereby slowing down your web    application by needlessly transmitting the same data over and over

2- Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)

3- Cookies are limited to about 4 KB of data — enough to slow down your application , but not enough to be terribly useful


**INTRODUCING HTML5 STORAGE**

**Web Storage* :

it was a part of HTML5 BUT NOW sometimes known as DOM storage (Document Object Model storage), provides web apps with methods and protocols for storing client-side data. Web storage supports persistent data storage, similar to cookies but with a greatly enhanced capacity[ and no information stored in the HTTP request header.


**Storage size**

Cookies are restricted to 4 kilobytes. Web storage provides far greater storage capacity:
**Opera* 10.50+ allows 5 MB
**Safari*  8 allows 5 MB
**Firefox*  34 allows 10 MB (formerly 5 MB per origin in 2007)
**Google* Chrome allows 10 MB per origin
**Internet Explorer* allows 10 MB per storage area

**USING HTML5 STORAGE** 

simply it's a process of storeing info based on a named key , the you can retrievet again .

