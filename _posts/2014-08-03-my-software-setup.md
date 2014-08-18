---
layout: post
title: My hardware and software setup
---

I am new to the magical world of Terminal / UNIX, software development, web design, etc. There are so many resources it can be hard to know where  to start. I will document my setup, resources, and journey. Hopefully you find this useful!

---

##Hardware:
I think quality tools you use all day, every day are worth every dollar. Great tools make your work joyful. Apple products do this for me, although they cost a lot of money.

+ [15" Macbook Pro Retina](http://www.apple.com/macbook-pro/): I purchased a lightly used 2012 MBPr for $1450 off eBay. This was the best money I ever spent. The MBPr has a great balance of portability, computing power, and display awesomeness. However, the battery life is sub-par. Later this year, Apple may be releasing a 12" Macbook Air with Retina, which will be a more ideal laptop for my needs. I installed the OS X Yosemite Public Beta (maybe unwise to do on one's primary machine), but so far so good.
+ [Keyboard cover - $10](http://www.amazon.com/gp/product/B007FL6100/ref=oh_aui_detailpage_o04_s00?ie=UTF8&psc=1): this washable cover prevents your keyboard from getting smudged over time.
+ [Incase Sling Sleeve Deluxe](http://goincase.com/shop/incase-sling-sleeve-deluxe-for-macbook-pro-15): carries just what I need (MBPr, iPad, moleskine notebook, pens, papers) in a slim form factor. I would not buy a bigger or smaller bag. The material is not high-end, but neither is the price.
+ [iPhone 5S](https://www.apple.com/iphone-5s/): I went iOS over Android due to the superior medical app ecosystem, and prevalence of iMessage among my friends. Plus, I really like the aesthetics of iOS 7, and app integration with OS X. This will only improve with OS X Yosemite.
+ [iPad Mini Retina](https://www.apple.com/ipad-mini/): This lets me quickly sketch concepts using []() and send image files. It is also a great PDF reader when I ride the shuttle between Emory & Tech, fly on the plane, or just want to read outside of my office. I wish I got 32GB memory though. 16GB fills up fast with lots of apps.
+ [Dell UltraSharp 2408WFP 24" monitor](http://www.cnet.com/products/dell-ultrasharp-2408wfp/): Having at least one large external display is essential for the technical academic: helps productive coding, manuscript writing, reading, etc.
Pro tip from [mattmight](http://www.twitter.com/mattmight): Buy multiple laptop chargers. Leave one at your office, one at home, etc. It can actually [make economic sense](http://matt.might.net/articles/artificial-scarcity/) if the cost of packing up your charger exceeds the cost of buying another one.

##Terminal tools & modifications:
+ [TotalTerminal](http://totalterminal.binaryage.com/): TotalTerminal is a great plugin for Terminal.app. Make a full-screen Terminal pop up with a custom hotkey combo.
+ [Solarized](http://ethanschoonover.com/solarized): a sixteen color palette (eight monotones, eight accent colors) designed for use with terminal and gui applications.

Pimp your terminal using [@jgmalcolm's](http://www.twitter.com/jgmalcolm) config files. This will align text in readable columns, and add color. Open Terminal, cd into your *repos* folder (you need GitHub installed), and enter these commands:

```
    $ git clone git://github.com/jgmalcolm/config.git
    $ cd config
    $ ./update
    $ source ~/.bashrc
```

Finally, go to *gitconfig* in the newly created *config* folder and edit James' [user] name and email to your own.

##Text editors:
+ [Atom](http://atom.io): "A hackable text editor for the 21st Century", built by the talented wizards at GitHub. I like the tabs and customizability. Solarized Dark (see above) is easier on my eyes.

##File uploading & collaborative programming:
+ [CyberDuck](https://cyberduck.io/?l=en): for FTP and WEBDav
+ [GitHub](github.com): You can use either the terminal or the desktop app. If you [register with a .edu email address](https://education.github.com/), you can get a free upgrade to an academic account which enables private repos for collaborating.

##Note-taking, Scheduling, & Email:
+ [EverNote](https://evernote.com/): Saves notes to the cloud, syncs between all my devices, and lets me drop almost any document or picture in a note. I have folders for research, startup work, and medicine, with project subfolders within.
+ [Reminders](http://support.apple.com/kb/HT4970): If I need to do something later, and cannot do it immediately, I add it to Reminders, which nicely syncs between all my devices.
+ [Sunrise Calendar](http://sunrise.am): I like this more than Google Calendar or Calendar.app for OS X because it feels more responsive, adds icons based on meeting key words ("dinner" has a little fork, knife, and plate), and adds pictures of the other people on your calendar events. Free for OS X and iOS.
+ [Mailbox (only for iOS)](http://www.mailboxapp.com/): I love this app for several reasons. Mailbox has a nice design. If you sign up, you get free Dropbox space. It lets you boomerang emails to handle later. A clean inbox (even with emails incoming later) is great for OCD people. If you achieve inbox 0, you get to see a nice picture! Finally, it only handles Gmail and iCloud. This helps me because I really dislike using my Emory or Georgia Tech emails. Anything outside of Gmail causes unnecessary fragmentation. Because I prioritize Gmail, users who contact my other email addresses receive "negative feedback" via delayed responses. That, plus replying to all emails from my Gmail account, plus a request to send future correspondence to Gmail, reduces unwanted emails to my other accounts.
+ [Gmail](www.gmail.com): Professor Might illustrates why Gmail is an optimum email client in [this great post](http://matt.might.net/articles/productivity-tips-hints-hacks-tricks-for-grad-students-academics/).

##PDF management
+ [Mendeley](http://mendeley.com/): Mendeley is a free reference manager and academic social network. Make your own fully-searchable library in seconds, cite as you write, and read and annotate your PDFs on any device.