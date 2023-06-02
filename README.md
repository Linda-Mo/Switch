# Switch
what is Switch?
Switch is an instant messaging application that gives people a good access to connect with friends and family. It is a social media Android app that uses Theta Network to allow users to post, share , like, comment, and displays videos,  images etc. It also allows user chat with each other and share media.

## The source code and APK are sent to Theta email address given at devpost

## Inspiration
Theta network and Telegram inspired me to create a social media app that uses Theta video API, Theta Edge store to allow users to view and display media through their phone and allow them to share,post,like,and comment on media from other users. It is an app that allows access to Theta media.
## What it does
Switch is a social media app that uses Theta and firebase. It allows users to communicate with each other, sharing photos and videos. It allows users to to see,like,share,and comment on videos posted. It allows posts of short and long videos with images. It allows user to create status stories using either Theta video or media from phone devices
User information and media urls are all store in firebase to allow easy access to information but media like videos are stored and retrievd on Theta network. The app also allows users to view announcements from admin. Users can also connect their Switch account to other mobile devices. Switch also allows users to call each other through phone call or video call. It allows users to save messages, delete message, reply to messages or report users who violate our terms and conditions. It is a platform that connects people through out the world.

## How we built it
Switch is built using Android studio, the programming languages are java and kotlin, and the database used are Theta network and firebase 

## Challenges we ran into
Challenges we ran into are the Theta video SDK for Android. The video view (exoplayer) that was used there is an old version and most of it functionality are deprecated. Using that player was difficult since I wanted to pre-load videos before display them, and using those functions in an adaptor proved to be quite challenging since a had to initialise and release the video player.  The problem with initialising and release the player caused the video player not to load videos properly.

## Accomplishments that we're proud of
I am proud that I got this opportunity to create an app that uses Theta network and learn how to use Theta network and how to use their SDK to call and display. 

## What we learned
I learned about how to use Theta video SDK, Thetha Edge store, and Theta live streaming. How to create an app that can retrieve media from Theta network 

## What's next for Switch
To-do list for Switch
1. Complete Theta Edge node (retrieve both umages and videos)
2. Add NFT smart contracts
3. Create an access to Thetha wallet to view your balance etc
4. Using the latest exoplayer to load videos
5. Display status stories using Theta videos and images
6. Complete chat, make voice notes, make video and phone calls

There is still alot to accomplish
