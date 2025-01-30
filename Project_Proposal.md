# CSTP 2204 IT Project

### Description
This is our project proposal document where we will layout two possible ideas to explore. 

## Contributors
- Arlexan [@Thatbox1](https://github.com/ThatBox1)
- Artem [@Artemgood477](https://github.com/Artemgood477)
- Ben [@benjaminjamesweb](https://github.com/benjaminjamesweb)
- Max [@xameryn](https://github.com/xameryn)
- Travis [@Travis975](https://github.com/Travis975)

## Main Idea
Project Name: FileNest

- A self-hostable cloud storage for you and your friends with Discord compatibility.

### Description
The user will be able to set up a cloud server on their own local machine to store files and from 

there they can easily share with friends. Either through embedded on discord or access to users' 

collection. The plan would be to make the graphic user interface in REACT + JS that the user would

run in browser to use application. The main aspect we are wanting to achieve is discord compatibility 

which would allow Oauth with discord and embedding media links similar to youtube media. 

Will allow for easy sharing of videos and other media since discord has a limit for file sharing. 


### Features

- User hardware dependent 

- Cloud limited to user  

- video embed support for discord (basically a YouTube player when a video link from the server is sent) 

- User has basic CRUD capabilities 

- Make collections to store media (images, videos, audio, etc.) 

- Set collection visability 

- Sign in with discord (will need discord to use app) 

- REACT GUI

### Potential Issues
- Port Forwarding for sharing the local server

## Secondary Idea
Project Name: NearReel

- An area based application to connect people in their given area and share short videos like a TikToks.

### Description
A TikTok-like social media website where users can view/post short videos (<5 seconds).

The most unique feature of the app is that it’s location-based (like Tinder), so users can 

only view content from their area (they can specify the radius from <50m to <15km). 

The benefit of this is that users see/interact with local content, so using the app

connects them more to their real-life surroundings. The app would be coded in React. It would be

a web app (in other words a website), only accessible through the browser (not the app store).

However, responsive CSS would allow for the website to be used on mobile screens, iPad screens,

and laptop screens, making it somewhat "cross-platform" (even if it’s web only). Cloud services 

like Amazon S3 could be used for storing the videos. To keep our Amazon bill low (or ideally non-existent),

we might make it so that videos are converted to 144p when uploaded. The 5 second limit also helps with this.  

### Features
- Typical user secure sign up/log in 

- The “feed” (a TikTok-like timeline of short-form videos from other users) 

- Each video (or “post”) displays the poster’s username (which can be clicked on to view their profile/all videos) 

- Videos also have typical information like captions, hashtags, likes, comments 

- Every user has a personal (public) page where their videos can be viewed (as well as info like bio, number of subscribers, number of posts, etc.) 

- Users can follow other users 

- Users can message other users 

- Users can set their radius (like Tinder). However, the max radius should still be small (e.g. <15km). 

- All posts display the location of the video/picture in question. Clicking on that should take you to a map showing the location as a pin 

- Potentially: you can browse videos by map? 

- Potentially: all posts and time-based as well as location-based (so you only see videos from the last 48 hours, for example)? 

- Potentially: AI is used for giving priority to the most viral/interesting/personalized content – also for weeding out/flagging spam/inappropriate content? 

### Potential Issues