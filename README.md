<img src="https://github.com/unnecessarylibs/ImDragonsAPI/blob/main/img/ImDragonsAPI-logo.png" alt="logo">

<p align="center">
  <a href="#about">About</a> •
  <a href="#prerequisites">API</a> •
  <a href="#links">Links</a> •
  <a href="#credits">Credits</a>
</p>

# About

Imagine-Dragons API (or **"ImDragonsAPI"**) creaated on **April 24th, of 2021**. Is a Open API created by [Unnecessary Libraries](https://github.com/unnecessarylibs) that allows for indexing of a massive collection of Data regarding the band **[Imagine Dragons](https://www.imaginedragonsmusic.com/#/)**. Created as a side Project from [RobbiDev](https://github.com/pengyofficial) which is the Creator of Unnecessary Libraries (or **UNLIBs**). Allows for making **HTTPs request** to the API and returning a large amount of JSON data about the band. Data is so Diverse, you can get the littliest of data from about just anything. 

<!-- ### Usage Example: 
Complex: lets say you wanted exact lyric at timestamp **2:00** on the song "Believer". YOU CAN! 
Or lets just say you want something simple. Like "What album did believer release on?" YOU CAN! -->

# The API
This Section talks about how the API is Orgaznized, and Used. These details can be skipped over. But if your a new Developer learning APIs. I **suggest** you read!

## Structure
ImDragonsAPI is simple to use and has an easy-to-understand structure. The data is sorted by two different types of categories: "collections" and "individuals." A collection is where a lot of detailed JSON is sorted. Collections contain multiple data objects in one file. An example  of this would be the album collection. It contains every album the band has ever released and is very detailed. On the other hand, "individuals" are the opposite. They are single JSON files that contain only one or two objects. An example of an individual would be a song like "Thunder," and the second object would contain all the lyrics.

## Manipluating the API
As of right now. The API only supports Indexing and sifting though the data. The API doesn't support no **POST/request** at the moment and is quite simple as of now. Later features are still being tested on, But for now, its a simple **GET/request** that returns a JSON object. Those objects can either be indexed manually by you.(If you like the custom method) Or you can use a API supported "Indexer". A simple class function that does all the indexing for you.

Main API Endpoint
```
https://api.unnecessarylibraries.com/imdragons/
```

Example API Route of "**/imdragons/data/band**". 
```
https://api.unnecessarylibraries.com/imdragons/data/band
```

## Documentation 
```
Still in Development! 
Estimated Release: February 2023 (Updated on 1/4/23: On track)
```


## Why?

**ImDragonsAPI was created primarily to develop new development skills.** I used this project to help develop a better understanding of backend processes. In return, I made a simple-to-use API for anyone to use and learn too.

You can use this API for any purpose you want. Some examples you can try, are as follows: 
- A Discord bot that gives Information regarding the band
- Creating connections with music streaming services like Spotify, Itunes, and Pandora 
- Making fan-made Wikipedia for front-end learning too
- **...and So much more. Just use that amazing imagination!**

Our main target audience was mainly directed towards developers who were starting to enter the backend world. Creating a simple, easy-to-use library that can help grow upon that entry. We also wanted to provide developers who are Imagine Dragons fans with a better way to obtain all things Imagine Dragons. Giving developers access to any data or information they would ever need about the band.

## Supported Languages

The list below includes libraries that are directly supported by the API. Since we just started, we only have one for now. Don't be afraid to assist us by developing your own library, using your programming language of choice! Just check out our contributing policy to learn more about adding your own library!

Currently Support Languages

- Javascript: [ImDragons.JS](https://github.com/RobbiDev/imagine-dragons.js)

Libraries Under Development: 

- Python: (Planned)
- TypeScript: (Planned)


# Links

- [Github](https://github.com/RobbiDev/imagine-dragons.js)
- [npm](https://www.npmjs.com/package/imagine-dragons.js)
- [Unnecessary Libraries Discord](https://discord.gg/y8TYje4PXH)

# Credits

- [RobbiDev](https://github.com/pengyofficial) - Lead Programmer
- [Unnecessary Libraries](https://github.com/unnecessarylibs) - Organizer
- [Imagine Dragons](https://www.imaginedragonsmusic.com/#/) - The Creator of it all


## Contriubting
Anyone can Contribute to the API and all the JSON data has been open sourced for edits and additions. 

### Notice:
We respectfully ask anyone who uses our data to credit us! 

We've spent countless hours compiling the data and are very proud of it. You can download it and use it in your own projects, but please credit us. We also perfer if you use our API instead of just copying and pasting the JSON data.