<p align="center">
  <a href="#gh-light-mode-only">
    <img src="./src/assets/1.png" alt="logo" width="100%" height="auto" />
  </a>
  <a href="#gh-dark-mode-only">
    <img src="./src/assets/2.png" alt="logo" width="100%"; height="auto";/>
  </a>
</p>
<p align="center">An API that allows for instant access to a massive database of <br> infomation regarding the band Imagine Dragons!</p>
</p>
<p align="center">
  <a href="#about">About</a> •
  <a href="#prerequisites">The API</a> •
  <a href="#links">Links</a> •
  <a href="#credits">Credits</a>
</p>

# 👋 About
Created on April 24th, 2021 by [Unnecessary Libraries](https://github.com/unnecessarylibraries). ImDragonsAPI was created to give fans all in one place for a fast, and constantly updating database of data regarding the band [Imagine Dragons](https://www.imaginedragonsmusic.com/#/). Instantly giving results back after perfecting the codebase. Say goodbye to the pain staking process of copy and pasting Wikis!

# 💻 The API
ImDragonsAPI was also designed to be a beginner friendly tool for new asiring developers. A public rest API anyone can use to start gaining skills within backend development. Thats why we developed our database with a very simple to use structure. 

Examples projects you can try:
- Making a Discord Data bot that gives Information regarding the band
- Twitter bot that Tweets out upcoming band Events
- Imagine Dragons news website
- Retrieving music streaming services data with the API
- Creating a Imagine Dragons Theme Website to learn front-end and Back-end integration

**...and So much more.**

## Documentation
See our dedicated website for our documentation, or you can view our documentation files:
- [Website](https://docs.unnecessarylibraries.com/)
- [Files](https://github.com/unnecessarylibraries/ImDragonsAPI/tree/main/docs)

# 🚀 Usage
There are many different way to use and manipulate our API. Since its a open api, you can access it from about almost anywhere, As long as your enviorment/code supports HTTP requests.

Main API Endpoint
```
https://api.unnecessarylibraries.com/imdragons/v1
```
Example API Route of "**/collection/info/band**". 
```
https://api.unnecessarylibraries.com/imdragons/v1/collection/info/band
```

API Route Response in JSON
```json
{
  "BAND_INFO": {
    "details": {
      "origin": "Las Vegas, Nevada, United States",
      "genres": [
        "Alternative rock",
        "Indie rock",
        "Electronic rock"
      ],
      "labels": [
        "Interscope Records",
        "KIDinaKORNER"
      ],
      "members": [
        "Daniel Samardžić",
        "Dan Reynolds",
        "Ben McKee",
        "Wayne Sermon",
        "Daniel Platzman"
      ]
    },
    "socialmedia": {
      "twitter": "https://twitter.com/Imaginedragons",
      "youtube": "https://www.youtube.com/channel/UCpx_k19S2vUutWUUM9qmXEg",
      "apple": "https://music.apple.com/us/artist/imagine-dragons/358714030",
      "spotify": "https://open.spotify.com/artist/53XhwfbYqKCa1cC15pYq2q",
      "instagram": "https://www.instagram.com/imaginedragons/",
      "website": "https://www.imaginedragonsmusic.com/",
      "facebook": "https://www.facebook.com/ImagineDragons/",
      "email": "https://www.imaginedragonsmusic.com/#mailing-list"
    }
  }
}
```

## Supported Languages

| Language   | Name         | Version | Link  |
| ---------- | ------------ | ------- | ------|
| Javascript | ImDragons.JS | v1.0.2  | [Click Here](https://github.com/RobbiDev/imagine-dragons.js)|

Want to help epxand our supported libraries? Don't be afraid to develop your own library, or contribute to existing libraries. Look at our contributing policy to learn more about adding your own additions!

# Links
- [Github](https://github.com/unnecessarylibraries)
- [Unnecessary Libraries Discord](https://discord.gg/y8TYje4PXH)

# Credits
- [RobbiDev](https://github.com/pengyofficial) - Lead Programmer
- [Unnecessary Libraries](https://github.com/unnecessarylibraries) - Organizer
- [Imagine Dragons](https://www.imaginedragonsmusic.com/#/) - The Creator of it all


