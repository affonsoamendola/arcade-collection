# arcade-collection

Definition of a file structure and Ideas regarding my collection of arcade/pinball/computer related photos and data.
So, I have this huge hard-drive filled with photos of old arcade machines and pinball, and all sorts of related stuff. Most of it isn't mine, but is collected material from random parts of the web.

And I need to figure out a way of storing all of it in a sane manner.

Or to at least organize in a manner where similar stuff is close together.

The goal of this is to make all things related to a specific 
"THING" easily accessible.

The definition of THING varies a bit, but in the current case is arcade machines or consoles or game companies or pinball or magazines or computers (Proposals for more stuff is requested)

This is mostly for MAME reasons but not only, there is also random arcade company related stuff that dont quite fit in with MAME Artwork reasons

An important requirement is that the organizing must come from the file structure.
-An open-source, free-software database MIGHT be a better solution, in the case for cross-referencing photos that include Multiple arcade machines for exemple, but the categorizing would be INSANE.
--I am thinking of writing a software to make categorization easier. Maybe even leverage the WONDERS of machine learning to try and tell which arcade machines appear in which images. If thats not possible or a stupid idea, a guided manual categorization system should be simple enough to write. 
---Like a thing that show you an image and simply asks you which arcade machines appear there, and you just write and press enter, and it shows you the next one. Will try and time stuff to see how long it would take on average to categorize everything.

Basically there is more than MAME artwork here. so yeah.

MAME Shortnames are really useful, So I might be sticking to them.

Right now the file structure looks as follows:

Research:
|
|-antique 		Old stuff that cant really be considered arcade
|                 machines
|-arcade  		Photos, flyers, videos, scans, audio of arcade 
|				  machines
|-audio   		Unknown or non arcade audio
|-console 		Photos, flyers, videos, scans, audio of video-game 
|                 consoles
|-data    		Lists and Spreadsheets and random data about Arcade
|                 machines or consoles
|-docs	  		Old documents from weird places (like Atari)
|-magazines 	Magazine Scans
|-mame-art 		Random mame-related art (Mostly of MAME logos)
|-non-specific 	Non-specific stuff
|-photos 		Photos of random stuff
|-pinball		Photos, flyers, videos, scans audio of pinball 
|                 machines
|-scans 		Scans for random stuff
|-unsorted 		Still Unsorted stuff.
|-video 		Viddeos of random stuff.


Yeah. AS YOU CAN SEE, it fucking sucks.

I'm not really sure how to organize this stuff in a sane and logical way. 

But there are some problems: 

MVS stuff, go into arcade or console? I believe they can both be played on the arcade and on the console.
But there is stuff thats OBVIOUSLY arcade specific, so they MUST go into arcade.

Antique should really exist? There is stuff in there that is proto-pinball or proto-arcade.
There isnt really a criteria for what I would consider Antique.
-I propose the PONG CRITERIA(tm) which states that if it's older than 1972, its antique.
However the criteria is a bit vague, and I think it might be better as a subset of arcade or pinball 
    arcade
	|-antique
	...
	pinball
	|-antique
	...

Audio, Photos, Videos, Scans folders should be sub-folder categories or not exist AT ALL.
The goal of this is to make all things related to a specific arcade machine or pinball machine easily accessible.
So fragmenting stuff like this is inadvisable.

Misc folders might be nescessary but used VERY sparingly.
I prefer to have a logical empty path to a single file than a misc folder filled with random crap.
Maybe even have empty folders for things that are notoriously missing media (Like having a folder for the perfect LD rip of dragon's lair (Haven't they finally got a good rip of that like earlier this year or am I way to high?))


I do apologize for taking stuff from other repositories of similar stuff. There really wont be much original stuff here (apart from my own and friends pictures of stuff (About 500mb, maybe more?)) 
But the main reason I do this is because I really dont like how stuff is organized in some of those, I mean, there are repeated photos everywhere.

Also in a few of those, there is edited images mixed with original photos, in a way that might be hard to tell if a photo is original.
In case I am suspicious of a certain image I will separate it in a possibly-edited folder.

But unfortunately it means that image authenticity might not be guaranteed (Is that how you write that word? Fuck it.).
In a possible database-cross-referenced-everything future, there might be a DEFINITELY-REAL or DEFINITELY-FAKE or maybe-fake? flag that tells you some of that. But still future stuff.

Still, I thank you all for your service in historical preservation. And I promise to try and credit everyone involved.


This is a VERY ambitious project.
It has been attempted before.
It MIGHT fail miserably.
But fuck it, We'll do it live.

Remember to Be Excellent to Each Other.
And to suggest a name for this MONSTROUS project.
