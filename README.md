# cbsync
[`cbsync`](https://github.com/sandorex/cbsync.git) is a CLI utility / daemon *(optional)* that allows user to sync browser's data (cookies, bookmarks, history, and more..) to any other browser without using browser's builtin sync cause as **we all know they suck**

`cbsync` allows you to save browser data wherever you want, for example
- Your local server, take the data in your own hands
- External storage, take your browser on the go!
- Version control, rollback your data anytime you want!
- Dropbox, a free and elegant replacement for Chrome sync
- AWS, why not?
- Some combination of the above, *the world is your oyster*

This project heavily relies on [`ebd`](https://github.com/sandorex/ebd) library

# The Motivation
The motivation of this project is to allow people to use any browser they want, or even all of them!  
I won't judge, i just hate the reliance on single browser cause of the sync feature

I have been using Brave on and off for a while but i can't completely switch to it cause the sync is terrible and just device to device, i have a lot of bookmarks saved and i can't simply get rid of it

# Other Solutions
### [xBrowserSync](https://github.com/xbrowsersync/app)
The problem is the same but the solution is different, `cbsync` works by directly reading from / writing to browser files so the browser does not need to be even installed

# License
Licensed under [Apache License 2.0](LICENSE)
