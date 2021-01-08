# dsm
Public release of public data from Discord Scam Monitor.

The data is formatted in a format similar to CSV. I had no idea which format I should use to release the data, but this is at least universal and easy to read.

Each column is split using ;;, in name changes, each variable in the whole object is split using a single semicolon.

There was some other data, such as debugging, lister/saver information, or notes. I'm not going to share this data, as it's not necessary. Vouches/reputation is also not included.

## Server
Server Name  
Server ID  
Owner Name (at the time of saving)  
Owner ID  
Invite Link (discord.gg/)  
Minimum Invites (**0** - doesn't have invite rewards, **-1** - other type of scam)  
Rewards Available  
Channels Screenshot Link  
Invite Rewards Screenshot Link  
Is Legit (Scam = 0, Legit = 1)  
Created On (Unix)  

## Server Name Change
Server ID  
Every registered name change: New Server Name;Changed On (Unix, Date of updating)  

## User
User Name (current)  
User ID  
Is Legit (Scam = 0, Legit = 1)  
Created On (Unix)  

## User Name Change
User ID  
Every registered name change: New User Name;Changed On (Unix, Date of updating)  

## Bot
Bot Name  
Bot ID  
Created On (Unix)  
