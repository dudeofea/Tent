Tent
====

Progress 0%

About
-----

So far this is just an idea that I'm building so that I can make freelance websites the way I want to make them.
I don't believe in charging for software that I've already written, or put in other terms, I don't believe in selling a "template" website, or developing on a paid website template.
I just want to get paid to write code, new code, useful code, code that ties together things that already exist into a viable product.

Each user/client is different, while they may all want wheels which we are doubtful to reinvent, that doesn't mean we should design a single wheel built to handle all terrains and temperatures but not any specific terrain or temperature. Users have different needs, and a lot of the time we can over-generalize a problem to save on money, time or effort.

In short, this is a CMS that forces all publicly hosted websites derived from this one, to share their source. It is licensed under the AGPL, which behaves like the GPL with the addition that network protocols (such as HTTP) count as distributing the software. So, all websites derived from this one, must share their source when hosted.

If someone has noticed a flaw in my logic or thinks that the way I licensed this project is not advisable, please send me a message as it would be greatly appreciated!

If you think this is frivolous, facetious, or fastuous please send me a message as well as I appreciate the company

Licensing
---------

This project is licensed under the AGPL with the following added conditions:

* All derivations of this project that host a website, must share their source code through the /_source endpoint (if your base URL is http://catsndogs.com, then http://catsndogs.com/_source must return the website's source code in full) **with the exception of non-text content (images, video, etc) which is not required to be shared**. The /_source endpoint is already provided for you for your convenience
* All plugins (code modules added to this website that could not function without this website and whose purpose is use with this website) that are developed for this website must be GPL licensed (any version of GPL / LGPL / AGPL) **with the exception of non-text content which may be licensed under any license the author wishes**
* To make things clearer, text content in a plugin like CSS, JS, HTML (or anything which will be compiled to CSS, JS, HTML) must be GPL licensed
* Text content (ad copy), and non-text content in plugins can be bundled separately or stored elsewhere before rendering

Support
-------

Feel free to fork this repo, modify it even. I will accept any pull request right away unless I feel it goes against the "core values" of this app, in which case I will kindly ask for you to refactor your changes into an optional build flag / config option and then I will merge it. You probably put a lot of effort into that pull request so you probably don't want strangers bickering about your code that you gave away for free. Pull requests will be unmerged and removed if later deemed harmful to the app (ex: an injected vulnerability or hack). I will not remove "healthy" or non-harmful pull requests without consulting you first about what to do (ex: If a new version of the app breaks things, or users have complained about the feature, etc).

I offer no support aside from documentation bundled with the app, if you'd like me to work on a certain feature, please pay me. Otherwise I am under no obligation to fix anyone's problems or implement any features in any order.