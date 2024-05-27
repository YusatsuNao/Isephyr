# ISEPHYR ![Static Badge](https://img.shields.io/badge/Version-isephyr%201.4%CE%B2-blue?style=flat)


Isephyr is a *__"GAME USER INTERFACE BASED PERSONALIZED APPLICATION"__*.

So, basically it's a launcher-like app similar to your app launcher for your game or your application in your phone but this taking one or more Game UI as reference for the design. Most of the part the UI copies lot of element from Gacha games, where you can see your *__Waifu__* in the home page and same as this one, you can set a custom interactive waifu, with a custom voice and expression
> ( well, of course if your waifu supports it though )

So yeah, it's basically a *__"WAIFU LAUNCHER!!"__*

This is also not a normal launcher where you just browing local html file or run application through a Electron.js web framework, there are lot of features and you can them check below. Well, some part still in BETA, I'm still figuring out how it works so yeah, this still in-development.

Because this application is running using web based program created using HTML, CSS and Javascript under Electron.js Framework. It's really easy to write / design the application from scratch.


## The Lists

- [Feature List](#Features)
- [Requirement](#Requirement)
- [Installation](#Installation)
- [Tutorial](#Tutorial)
- [Question](#Question)
- [Screenshots](#Screenshots)

## Feature List

#### ☆ Currently In Development
* [x] Partial DarkMode
* [ ] Full DarkMode
* [ ] Gacha Game Daily Reset / Patch Reset ![Static Badge](https://img.shields.io/badge/mini%20module-blue?style=flat)
* [ ] Next Airing Anime [ 24Hr/1D Span ]
* [ ] Currency Update ![Static Badge](https://img.shields.io/badge/mini%20module-blue?style=flat)
* [ ] Genshin Grinding List ![Static Badge](https://img.shields.io/badge/mini%20module-blue?style=flat)
* [x] World Clock
* [ ] Seamless World Clock
* [ ] Pagination for Anime / Bookmark Database
* [ ] BETTER UI for Bookmark Page
* [ ] Sorting Database from A - Z
* [ ] Interactive Live2D Character
* [ ] Calendar Module
* [ ] Custom Calculator [ Normal | Currency | Mass | Length | Temperature | Power | Data ]
* [ ] Color Pallete
* [ ] WebptoJPG
* [ ] Image to Base64
* [ ] JSON Editor / Extractor
* [ ] HTML Editor / Extractor
* [ ] Gantt Project

------

#### ★ Available Features

| Feature Name | Description | Related NPM | Module Name |
|:--------------:|:--------------:|:--------------:|:--------------:|
| Anime Database | Anime Database is where you can check your Anime lists locally and interact with it. | none | module_db_Anime<br/>![Static Badge](https://img.shields.io/badge/Integrated-blue?style=flat) |
| Waifu Database | The list of waifu you can have in this Application, at max you can show 12 of them. | SQLite3 | module_db_waifu<br/>![Static Badge](https://img.shields.io/badge/Integrated-blue?style=flat) |
| Genshin Database | Just a Locally Installed Genshin Database, you can check lot of materials, character, information data etc in here | none | module_db_genshin<br/>![Static Badge](https://img.shields.io/badge/External-purple?style=flat) |
| A4 Projects | This is a private module | none | module_db_A4<br/>![Static Badge](https://img.shields.io/badge/External-purple?style=flat) |
| Bookmark Database | This is where you can save all of your internet bookmark and track the progress | SQLite3 | module_db_bookmark<br/>![Static Badge](https://img.shields.io/badge/External-purple?style=flat) |
| <i style="color:red;">Lyrics Database</i> | This is the database of your saved music lyrics, find and show lyrics more easier | SQLite3 | module_db_lyrics<br/>![Static Badge](https://img.shields.io/badge/External-purple?style=flat) ![Static Badge](https://img.shields.io/badge/BETA-orange?style=flat) |
| <i style="color:red;">Save File Database</i> | This is the a database of your Game Save File, just in case | SQLite3 | module_db_save<br/>![Static Badge](https://img.shields.io/badge/External-purple?style=flat) ![Static Badge](https://img.shields.io/badge/BETA-orange?style=flat) |


#### ★ Page Structure
| Main File | First Page | Second Page | Third Page
|:--------------:|:--------------|:--------------|:--------------|
| Main.js > Login Page | ✴️ Dashboard | ▶ World clock  |
|  | | ▶ Log Page |
|  | | ▶ ??? Page |
|  | | ▶ ChatGPT Page |
|  | | ▶ Design Page |
|  | ✴️ Now Page |
|  | ✴️ Profile Page |
|  | ✴️ Shortcut Page |
|  | ✴️ Database Page | ▶ Anime Database | ❇️ Editor ![Static Badge](https://img.shields.io/badge/BETA-orange?style=flat) |
|  | | ▶ Waifu Database |
| | | ▶ Genshin Database |
| | | ▶ A4 Projects |
| | | ▶ Bookmark Database | ❇️ Editor |
| | | ▶ Lyrics Database |
| | | ▶ Save File Database|
| | ✴️ Settings Page |


## Requirement

List of NPM Requirement to make this app work

> npm install electron-context-menu [ Electron Context Menu ]()<br/>
> npm install fs *"and/or"* npm install fs-extra [ FS or File System ]()<br/>
> npm install howler [ Howler for Audio ]()<br/>
> npm install path [ Path ]()<br/>
> npm install sqlite3 [ Sqlite3 ]()<br/>
> npm install electron --save-dev [ Electron.js Main Module ]()

> npm install dev electron-builder [ Electron Builder if needed ]()

## Installation

![Static Badge](https://img.shields.io/badge/in%20Dev-orange?style=flat) Current not available


## Question

![Static Badge](https://img.shields.io/badge/in%20Dev-orange?style=flat) Current not available

## Screenshots

<p align="center">
	<img src="temp/SS1.jpg" alt="Main Homepage">
	<br>
	<em>Main Homepage</em>
</p>
<p align="center">
	<img src="temp/SS2.jpg" alt="Main Homepage with Character L2D Active">
	<br>
	<em>Main Homepage with Character L2D Active</em>
</p>
<p align="center">
	<img src="temp/SS3.jpg" alt="World Clock Page">
	<br>
	<em>World Clock</em>
</p>
<p align="center">
	<img src="temp/SS4.jpg" alt="Database List Page">
	<br>
	<em>Database Page</em>
</p>
<p align="center">
	<img src="temp/SS5.jpg" alt="Waifu List Page">
	<br>
	<em>Waifu List Page</em>
</p>
<p align="center">
	<img src="temp/SS6.jpg" alt="Anime List Page">
	<br>
	<em>Anime List Page</em>
</p>
<p align="center">
	<img src="temp/SS7.jpg" alt="Bookmark Page">
	<br>
	<em>Bookmark Page</em>
</p>
<p align="center">
	<img src="temp/SS8.jpg" alt="Settings Page">
	<br>
	<em>Settings Page</em>
</p>

------
