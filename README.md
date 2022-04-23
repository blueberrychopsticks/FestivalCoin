# TARGET DATE = Lolla = July 28

# TLDR

User downloads our app and uses it to record video at festival (blogging,showing a performer,etc)
We embed QR codes in creative ways in video (that will link the video recording to the user to the NFT to the Tweet)
Any time someone retweets that user's video, they get a share of the pool of money that has developed from people purchasing downstream NFTs that contain clips of the Festival ==> (this will require a little bit of thought about how to develop a "pool" of funds. Easiest option is for sponsers to put together something like 1 BTC. More on this below [0]
Festival sponsor, developers, artist, clip uploader person are all notified immediately and can optionally opt in (with a PRESET CUTOFF BUDGET) to purchase derivatives of all minted NFTs. 
WHY would anyone want to mint Festival Coin? These NFTs are expected to grow in value as people realize their value. The value I imagine is short lived to the duration of the festival or at least it will peak shortly after the festival (or perhaps around some of the headliners as people expect many more people to view the headlines than lower tier artists [we could even play with the dynamics and promote lower tier artists])
NFT Derivatives can be minted by users (regardless of whether they attended the festival or not) from within the webpage that the QR code in the video clip links to. That webpage will contain another QR code that will perform the "Derivative Minting Process" for the downstream user

> user attending concert (in this case, lola)
>$ user purchases ticket, lodging, travel $

User spends a good amount of money on their ticket, their flights, their lodging, etc in hopes of having a memorable and safe experience at a festival with friends both old and unknown (as of yet)

Lets find a way to make attending festivals and being a good festival goer very lucrative to the user

@ User is at Artist and Artist is about to perform their set
Once Artist begins their set, the fun begins

< User downloads our FestivalCoin application. For more details on what exactly the app does, look in the FestivalCoin.md spec file in this directory

> upon opening our app for the first time, user is presented with a quick, 10 second explanation of what the app does

> after user goes through 10 second explanation, they can get started recording clips of the festival/sets


************************************************************************
************************************************************************
************************************************************************
HERES WHERE THE UNIQUE BITS START
************************************************************************
************************************************************************
************************************************************************

> cut in throughout the video is a qr code that links to the video being recorded via an NFT. That NFT is immediately minted to the User upon uploading the video. QR code links to our site with a listing of metadata about that recording, including the transaction on Solscan, maybe the artist recorded, how long into their set it was, and generic position of the user in the crowd. This information will not be PII because due to the user recording the video and uploading it, they are already identifying the fact that they were there. 

DIAGRAM
V = video frames
Q = qr code frames

VVVVVVVQQQVVVVVVVVVQQVVVVVVVVVVVVQQQQ
_______'''_________''____________''''


QR codes can be more quickly interspersed if they aren't noticeable

QR code will also be statically embedded in the video in a fashion that moves around as the video plays

If we point the QR code at the token address, we can allow the user to choose what URL users who scan the QR code are taken to. This should be aredefined list of URLs we generate in order to limit malicious behavior




0: This pool is not the only amount of money that is funding the downstream earnings. We only need enough to develop a "critical mass" for the festival so that people care enough to initially particpate. Then, as the NFT network (FestivalCoin) grows in value (and perhaps even eventually reaches saturated equilibrium), the Festival Coin Foundation can become responsible for hosting this technology at various festivals at no charge to the vendor, eventually making a free advertising campaign for how cool the festival was, how great the shows were, how clean the venue, how friendly the people there, etc
