# Prototype

### iOS Application 
- can record short bursts of video
- can mint a Festival NFT for that user prior to beginning that video &&& embed a QR code pointing at our website (which will contain metadata about the NFT, the clip, etc) within the video itself
- once clip is recorded, upload to video directly to Twitter as well (perhaps no need for s3?)

### Twitter Bot
- Each NFT will have associated with it a random, short hashtag
- Develop a Twitter bot to listen for likes and RTs of Tweeted clips of the Festival (using the assigned hashtag)
- Safeguard against reuploads as we will have the list of earliest uploads of videos with certain QR codes that I believe will be unhackable (TM obviously) and will ignore Tweets posting videos that have already been posted.
^^ I would STRONGLY like to reiterate that this is the first open source and easy to understand video authenticity (first uploader has authority)
- Send the poster of a video rewards upon Twitter responding well to the clip they uploaded

### Website
- Build website that will be responsible for displaying metadata to Twitter through the Twitter Cards / ogg API
- Users who post clips will be able to view that clip and share their clip with others through their web page
- Friends of original uploading User can mint derivative NFTs that point back at the original clip and will have a page setup on our site where they can do the same. 
- Any time someone mints from a downstream user, rewards are generated in some kind of geometric proportion all the way back to the genesis NFT holder - the NFT that was associated with the original clip. It is a "blockchain" after all


# Post Prototype

Begin getting real world feedback with prototype, develop features that will make festivals safer for concert goers, more rewarding for vendors, cleaner, and in general a more enjoyable experience for all.

A quick overview of some ideas include:
- EMERGENCY clips can be posted to avoid situations such as Travis Scott 2021 in Texas 
-- Users can bounty approximately $20 (or whatever they choose) to call emergency and if it turns out someone is actually in danger will receive 10x their bounty. If it turns out there was a hoax, that user will forfeit any funds that they haven't already withdrawn. Emergency and safety is no joke.

- Artists that are recorded can earn royalties from clips of themselves; moreso if they're wearing specially branded swag that can be identified by a camera as coming from our studio

- We can make it very easy for vendors to be paid in Sol, USD, or Festival Coin, with mining rewards if they generate a certain amount of sales (fairly low, somehow related to their fiat earnings) with Festival Coin. 

- Way more but I'm very tired now and going to bed

