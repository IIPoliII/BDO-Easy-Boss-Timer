BDO-Easy-Boss-Timer (on discord)

------
A script that give you an info about the boss 15 minutes before it spawns on discord
------

I will do a really short readme there is nothing hard if you have more questions contact me on discord Poli#9036

So this was the easiest way to create a basic bdo timer boss for my team what is boring with it is when the boss timers change for now it's up to date

Firstly create a webhook on your server on discord. 

Go in Server-Settigns -> Webhooks -> Create a webhook

Here choose some logical name or not, then choose the room where you want the timer to send you notifications

And take the URL of the webhook (save it somewhere for later)

Now go on your linux machine launch `crontab -e` (if you don't have crontab install it)

and paste the code from here 
(depending on where you will paste the discord send message script adapt the code as your wish, i recommand you to use notepad ++ to remplace)

Now simply close and save

Now copy the code of this script and open a text editor in your linux machine (here we will use nano with the default path) `nano /root/discord` 

Now that you copied the code change `YOUR URL HERE` to your webhook url that we took at first.

Save your work and run a `chmod +x discord` and done !

Now you will recive a notification 15 minutes before the bosses (make attention maybe this script is not with the actual times)