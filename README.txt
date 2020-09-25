Okayokay, the code here is gonna look pretty complicated. That's because I made it in an engine called Discord Bot Studio, so it doesn't work as directly as a normally coded discord bot. (I'm lazy).

If you don't trust the integrity of the files, I can get you in contact with the person who made DBS, and do other assorted verification things, if you'd like. I'm new to sharing my files with others, as normally I host it on my own computer. That doesn't really work, considering it's not on 24/7, though.

To run the bot, you'll need to take it out of the .zip and run the bot.js file inside. It's got node.js dependencies, but I doubt you don't already have node installed, lol.

Other than that, I don't have the bot set up with a complete economy system, as you wanted to see the files before you went any further. Not exactly the best thing for me, considering DBS runs off the role names.
It also lacks a %help command, currently, as I wanted to get the economy set up beforehand, so I could write out the help command correctly. I know, I'm not being professional and it seems really unfinished.

It currently has
%kick [user] (Kick members permission required on the user's end)
%ban [user] (ban members permission required on the user's end)
%clear [number of messages] (Manage messages permission required on the user's end)

%echo [string]
makes tsukasa repeat what comes after the command word.

%pseudokick [user]
Just a shits and giggles command, makes it look like the user has been kicked, but does nothing.

%balance
shows the user's balance

%pay [amount] [reciever]
sends an amount of money to a reciever. 

%botrule
setincrement [number] |||| Changes how much money is earned per message; must be set upon joining server.
welcomechannel [channel] |||| Changes the channel Tsukasa greets new members in.
