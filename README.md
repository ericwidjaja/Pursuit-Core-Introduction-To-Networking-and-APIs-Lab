# Pursuit-Core-Introduction-To-Networking-and-APIs-Lab

# Part One

Status Code Scavenger Hunt!

Use Postman to find each of the following HTTP codes:


1. 200

```swift
    1. https://USPS.com
    2. Standard response for successful HTTP requests.
    3. n/a
 ```
 
1. 301
```swift 
    1. www.pathfinder. com
    2. website is not found because it has moved permanently
    3. n/a to fix sinc eth elink is no longer existed
```

1. 400

```swift 
    1. https://httpstat.us/400
    2. The server cannot or will not process the request due to an apparent client error
    3. Check the error in URL, clear your DNS's & Browser's caches, contact the website that host your webpage.
```

1. 401

```swift
    1. https://httpstat.us/401
    2. The request was valid, but the server is refusing action due to wrong authentication.
    3. Check your URL, enter the right login/user ID and password.
```

1. 403
```swift 
    1. https://httpstat.us/403
    2. the content is private, restricted, geographically restricted and also the IP address was blocked.
    3. Double check the url, clear your cache and or cookies.    
```

1. 404
```swift 
    1. https://github.com/alexpaul/SoftwareDevelopmentResource
    2. The requested resource could not be found but may be available in the future. Subsequent requests by the client are permissible.
    3. type the correct address - 'https://github.com/alexpaul/SoftwareDevelopmentResources'
 ```   
1. 418
```swift 
    1. https://httpstat.us/418
    2. It's an 1998 April's Fool Day joke
    3. n/a
 ```   
1. 500
```swift 
    1. https://httpstat.us/500
    2. Internal server error
    3. Reload the webpage, clear your browser's cache and cookies, refresh your webpage.
 ```   

For each of the questions below, write:

1. The website which generated the HTTP status code
2. A description of what the status code means
3. If an app you were writing encountered this status code, what would you do (if anything) to resolve any issues?


For reference, see:

https://en.wikipedia.org/wiki/List_of_HTTP_status_codes (Links to an external site.)
https://http.cat


# Part Two

API Scavenger Hunt!

For each of the questions below, identify a website and search query that will give you the appropriate JSON.  Paste the url and the json below.  Googling the category + API will generally take you to where you need.  Ex. https://lmgtfy.com/?q=cat+fact+api

1. A random cat fact

```swift

https://catfact.ninja/facts?limit=1

"fact": "Cats are North America’s most popular pets: there are 73 million cats compared to 63 million dogs. Over 30% of households in North America own a cat.",
"length": 151
```

1. A list of 150 random users in English.
```swift 

```
1. The current stock price of Microsoft. (IEX API)
```swift
https://www.nasdaq.com/symbol/msft


<!-- START page level head content -->
<title>MSFT Stock Quote - Microsoft Corporation Common Stock Price - Nasdaq</title>
<!-- aspx\SummaryQuote.aspx -->
<meta name="description" content="Stock&#32;quote&#32;for&#32;Microsoft&#32;Corporation&#32;Common&#32;Stock&#32;Common&#32;Stock&#32;(MSFT)&#32;with&#32;real-time&#32;last&#32;sale&#32;and&#32;extended&#32;hours&#32;stock&#32;prices,&#32;company&#32;news,&#32;charts,&#32;and&#32;research&#32;at&#32;Nasdaq." />
<meta name="robots" content="index,follow">
<link rel="canonical" href="https://www.nasdaq.com/symbol/msft" /> 
<link rel="alternate" media="only screen and (max-width: 640px)" href="https://m.nasdaq.com/symbol/msft" />
<link rel="alternate" href="/es/symbol/msft" hreflang="es-es" />
<link rel="alternate" href="/it/symbol/msft" hreflang="it-it" />
<link rel="alternate" href="/de/symbol/msft" hreflang="de-de" />
<link rel="alternate" href="/zh/symbol/msft" hreflang="zh-cn" />
<link rel="alternate" href="/fr/symbol/msft" hreflang="fr-fr" />
<link rel="alternate" href="/symbol/msft" hreflang="x-default" />
<meta property="og:title" content="Microsoft&#32;Corporation&#32;Common&#32;Stock (MSFT)" />
<meta property="og:type" content="website" />
<meta property="og:site_name" content="NASDAQ.com" />
<meta property="og:url" content="https://www.nasdaq.com/symbol/msft" />
<meta property="og:image" content="https://www.nasdaq.com/logos/fb/msft.gif" />

<script type="text/javascript">
var myPage = 'summaryquote'; //page var
sectionId = 'liQuotes'; //section tab
breadCrumbId = 'qQuotes'; //page
is_dartSite = "quotes";
is_dartZone = "sq";
var propVar = "SummaryQuotes"; //omniture var
var propVar15 = "Quotes";
googlechannel = 'Quotes,Summaryquote';
googlehints = 'stock market, stock investment, trading account, real time quotes, portfolio tracking, stock charts, options trading, Nasdaq Stocks, Nasdaq Companies, Company Profiles, stock research, shares outstanding, stock Dividends, Stock trading, online stock, stock price, stock symbol, common stock, stock analysis, Options Trading, stock information';

```
1. The 5 year history of Apple stock prices (IEX API)
```swift
https://www.nasdaq.com/symbol/aapl/historical


<!-- START page level head content -->
<title>Apple Inc. Common Stock (AAPL) Historical Prices &amp; Data - NASDAQ.com</title>
<!-- aspx/historical_quotes.aspx -->
<meta http-equiv="content-type" content="text/html; charset=utf-8" />
<meta name="description"
content="AAPL&#32;historical&#32;prices,&#32;AAPL&#32;historical&#32;data,Apple&#32;Inc.&#32;Common&#32;Stock&#32;historical&#32;prices,&#32;historical&#32;stock&#32;prices,&#32;historical&#32;prices,&#32;historical&#32;data" />

<link rel="canonical" href="https://www.nasdaq.com/symbol/aapl/historical" />

<script type="text/javascript">
myPage = 'historical_quotes';
sectionId = 'liQuotes';
breadCrumbId = 'qQuotes';
is_dartSite = "quotes";
is_dartZone = "historicalquotes";
propVar = "Historical Quotes";
googlechannel = 'Quotes';
googlehints = 'stock market, stock investment, trading account, real time quotes, portfolio tracking, stock charts, options trading, Nasdaq Stocks, Nasdaq Companies, Company Profiles, stock research, shares outstanding, stock Dividends, Stock trading, online stock, stock price, stock symbol, common stock, stock analysis, Options Trading, stock information';
/*
SRA ad definitions, this should always correspond with the ad calls on the page
if an ad is removed from the page, it should be removed from here as well
*/
var useSRA = true;
var premakeAds = [];

/*quote page ads*/
premakeAds.push({
'label': 'condition', 'expression': !/selectedsymboltype=[^(%2c)]*(%2c)*(Mutual%20Fund|Money%20Market|Index)/.test(document.cookie),
'true': { 'label': 'ad', 'size': '120x60', 'site': 'box_button', 'zone': is_dartZone }//quotebox ad, hide for certain market types
});
premakeAds.push({ 'label': 'ad', 'size': '120x60', 'site': 'leftnav_top', 'zone': is_dartZone });
premakeAds.push({ 'label': 'ad', 'size': '980x20,300x25', 'site': is_dartSite, 'zone': is_dartZone });
premakeAds.push({ 'label': 'ad', 'size': '88x31', 'site': is_dartSite, 'zone': is_dartZone });//additional 88x31
premakeAds.push({ 'label': 'ad', 'size': '300x250,300x600', 'site': is_dartSite, 'zone': is_dartZone });
//premakeAds.push({ 'label': 'ad', 'size': '120x60', 'site': 'newsbox', 'zone': is_dartZone });
premakeAds.push({ 'label': 'ad', 'size': '300x250,300x600', 'site': 'mop', 'zone': is_dartZone });
//premakeAds.push({ 'label': 'ad', 'size': '300x250,300x600,160x600', 'site': 'btf', 'zone': is_dartZone });
premakeAds.push({ 'label': 'ad', 'size': '1x1', 'site': 'btf', 'zone': is_dartZone });
premakeAds.push({ 'label': 'ad', 'size': '1x1', 'site': 'quotes', 'zone': 'gutter_left' });
</script>

<!--
~ Copyright (C) 2014-2015 Media.net Advertising FZ-LLC All Rights Reserved
-->
<script type="text/javascript">
window._mNHandle = window._mNHandle || {};
window._mNHandle.queue = window._mNHandle.queue || [];
medianet_versionId = "3121199";
</script>
<script src="//contextual.media.net/dmedianet.js?cid=8CU1CBY9H" async="async"></script>
<!-- END page level head content -->


<!--********************************* BEGIN includes/global-references.inc **************************-->
<!-- global stylesheets -->
<link rel="stylesheet" type="text/css" href="https://www.nasdaq.com/includes/global.min-04172019v1.css" />
<!--[if lt IE 9]>
<script src="https://www.nasdaq.com/includes/html5shiv-printshiv.js"></script>
<link rel="stylesheet" type="text/css" href="https://www.nasdaq.com/includes/global-ie8.min-11212015v1.css"/>
<![endif]-->

<!-- favicon and shortcut icons -->
<link rel="apple-touch-icon" href="https://www.nasdaq.com/images/Q_apple.png" />
<link rel="shortcut icon" href="https://www.nasdaq.com/images/qfav.ico" type="image/ico" />
<link rel="icon" href="https://www.nasdaq.com/images/qfav.ico" type="image/x-icon" />
<link rel="shortcut icon" href="https://www.nasdaq.com/images/qfav.ico" type="image/x-icon" />

<!-- scripts -->

<!-- Casale -->
<script src="https://js-sec.indexww.com/ht/headertag-nasdaq.js" async></script>

<!-- GPT -->
<script async="true" src="https://securepubads.g.doubleclick.net/tag/js/gpt.js"></script>

<script src="https://www.nasdaq.com/dynamic_includes/marketstatus.js"></script>
<script src="https://www.nasdaq.com/aspx/marketstatus.aspx"></script>

<script src="https://www.nasdaq.com/includes/jquery.min.js"></script>
<script src="https://www.nasdaq.com/includes/global.min-08132019v1.js?1"></script>
<script src="https://www.nasdaq.com/includes/cookie_policy.js?05232018v1"></script>

<!-- NASDAQ nasdaq.com DurationMedia -->
<script type='text/javascript' src='https://pr.realvu.net/flip/2/c=E420_f=site_si=952'></script>

<!-- the dynamic css container -->
<style type="text/css" title="dynamic"></style>
<script type="text/javascript">
//<![CDATA[
updateSiteTheme();
//]]>

```

1. All the Swift language repos on Github with Pursuit in their name
```swift
https://api.github.com/search/repositories?q=pursuit-core+language:swift&sort=stars&order=desc

{
"total_count": 45,
"incomplete_results": false,
"items": [
{
"id": 99703757,
"node_id": "MDEwOlJlcG9zaXRvcnk5OTcwMzc1Nw==",
"name": "Pursuit-Core-iOS",
"full_name": "joinpursuit/Pursuit-Core-iOS",
"private": false,
"owner": {
"login": "joinpursuit",
"id": 5825944,
"node_id": "MDEyOk9yZ2FuaXphdGlvbjU4MjU5NDQ=",
"avatar_url": "https://avatars2.githubusercontent.com/u/5825944?v=4",
"gravatar_id": "",
"url": "https://api.github.com/users/joinpursuit",
"html_url": "https://github.com/joinpursuit",
"followers_url": "https://api.github.com/users/joinpursuit/followers",
"following_url": "https://api.github.com/users/joinpursuit/following{/other_user}",
"gists_url": "https://api.github.com/users/joinpursuit/gists{/gist_id}",
"starred_url": "https://api.github.com/users/joinpursuit/starred{/owner}{/repo}",
"subscriptions_url": "https://api.github.com/users/joinpursuit/subscriptions",
"organizations_url": "https://api.github.com/users/joinpursuit/orgs",
"repos_url": "https://api.github.com/users/joinpursuit/repos",
"events_url": "https://api.github.com/users/joinpursuit/events{/privacy}",
"received_events_url": "https://api.github.com/users/joinpursuit/received_events",
"type": "Organization",
"site_admin": false
},
```

1. A list of all Pokemon
```swift
https://pokeapi.co/api/v2/pokemon

{
"count": 964,
"next": "https://pokeapi.co/api/v2/pokemon?offset=20&limit=20",
"previous": null,
"results": [
{
"name": "bulbasaur",
"url": "https://pokeapi.co/api/v2/pokemon/1/"
},
{
"name": "ivysaur",
"url": "https://pokeapi.co/api/v2/pokemon/2/"
},
{
"name": "venusaur",
"url": "https://pokeapi.co/api/v2/pokemon/3/"
},
{
"name": "charmander",
"url": "https://pokeapi.co/api/v2/pokemon/4/"
},
{
"name": "charmeleon",
"url": "https://pokeapi.co/api/v2/pokemon/5/"
},
{
"name": "charizard",
"url": "https://pokeapi.co/api/v2/pokemon/6/"
},
{
"name": "squirtle",
"url": "https://pokeapi.co/api/v2/pokemon/7/"
},
{
"name": "wartortle",
"url": "https://pokeapi.co/api/v2/pokemon/8/"
},
{
"name": "blastoise",
"url": "https://pokeapi.co/api/v2/pokemon/9/"
},
{
"name": "caterpie",
"url": "https://pokeapi.co/api/v2/pokemon/10/"
},

```
1. A list of all items in Fortnite
```swift
https://www.programmableweb.com/api/free-fortnite


```
1. A list of all Game of Thrones Episodes.
```swift
https://api.got.show/api/map/episodes

{
"message": "Success",
"data": [
{
"characters": [
"Viserys Targaryen",
"Catelyn Stark",
"Cersei Lannister",
"Jaime Lannister",
"Eddard Stark",
"Robert Baratheon",
"Jorah Mormont",
"Daenerys Targaryen",
"Jon Snow",
"Petyr Baelish",
"Arya Stark",
"Sansa Stark",
"Bran Stark",
"Robb Stark",
"Joffrey Baratheon",
"Tyrion Lannister",
"Jeor Mormont",
"Alliser Thorne",
"Jory Cassel",
"Barristan Selmy",
"Rodrik Cassel",
"Benjen Stark",
"Yoren",
"Renly Baratheon",
"Maester Aemon",
"Syrio Forel",
"Grenn",
"Irri",
"Pypar",
"Rakharo",
"Lancel Lannister"
],
"_id": "5cc0743604e71a0010b85729",
"director": "Tim Van Patten",
"airDate": "2011-04-24T04:00:00.000Z",
"totalNr": 2,
"season": 1,
"nr": 2,
"name": "The Kingsroad",
"predecessor": "Winter Is Coming",
"successor": "Lord Snow",
"createdAt": "2019-04-24T14:35:34.594Z",
"updatedAt": "2019-04-24T14:35:34.594Z",
"__v": 0
},
{
"characters": [
"Eddard Stark",
"Robert Baratheon",
"Jaime Lannister",
"Catelyn Stark",
"Cersei Lannister",
"Daenerys Targaryen",
"Jorah Mormont",
"Petyr Baelish",
"Viserys Targaryen",
"Jon Snow",
"Arya Stark",
"Sansa Stark",
"Robb Stark",
"Theon Greyjoy",
"Bran Stark",
"Joffrey Baratheon",
"Sandor Clegane",
"Bronn",
"Tyrion Lannister",
"Alliser Thorne",
"Jory Cassel",
"Rodrik Cassel",
"Yoren",
"Barristan Selmy",
"Janos Slynt",
"Renly Baratheon",
"Marillion",
"Samwell Tarly",
"Grenn",
"Pypar",
"Gregor Clegane",
"Irri",
"Doreah",
"Gendry",
"Hodor",
"Tobho Mott",
"Tommen Baratheon",
"Myrcella Baratheon",
"Lancel Lannister"
]
```

1. A list of all songs with "Love" in the title.
```swift
https://itunes.apple.com/search?term=love

{
"resultCount": 50,
"results": [
{
"wrapperType": "track",
"kind": "song",
"artistId": 42616562,
"collectionId": 715579496,
"trackId": 715581836,
"artistName": "Nat \"King\" Cole",
"collectionName": "Nat King Cole",
"trackName": "L-O-V-E",
"collectionCensoredName": "Nat King Cole",
"trackCensoredName": "L-O-V-E",
"artistViewUrl": "https://music.apple.com/us/artist/nat-king-cole/42616562?uo=4",
"collectionViewUrl": "https://music.apple.com/us/album/l-o-v-e/715579496?i=715581836&uo=4",
"trackViewUrl": "https://music.apple.com/us/album/l-o-v-e/715579496?i=715581836&uo=4",
"previewUrl": "https://audio-ssl.itunes.apple.com/itunes-assets/AudioPreview71/v4/42/6a/a3/426aa324-78dd-8667-2869-dbfbb469e983/mzaf_5521623155491639858.plus.aac.p.m4a",
"artworkUrl30": "https://is1-ssl.mzstatic.com/image/thumb/Music6/v4/50/b7/55/50b755d1-2721-ef0e-6898-c33d16be37f9/source/30x30bb.jpg",
"artworkUrl60": "https://is1-ssl.mzstatic.com/image/thumb/Music6/v4/50/b7/55/50b755d1-2721-ef0e-6898-c33d16be37f9/source/60x60bb.jpg",
"artworkUrl100": "https://is1-ssl.mzstatic.com/image/thumb/Music6/v4/50/b7/55/50b755d1-2721-ef0e-6898-c33d16be37f9/source/100x100bb.jpg",
"collectionPrice": 39.99,
"trackPrice": 1.29,
"releaseDate": "1992-11-02T12:00:00Z",
"collectionExplicitness": "notExplicit",
"trackExplicitness": "notExplicit",
"discCount": 4,
"discNumber": 4,
"trackCount": 24,
"trackNumber": 24,
"trackTimeMillis": 152533,
"country": "USA",
"currency": "USD",
"primaryGenreName": "Jazz",
"isStreamable": true
},
{
"wrapperType": "track",
"kind": "song",
"artistId": 368183298,
"collectionId": 1440881047,
"trackId": 1440881708,
"artistName": "Kendrick Lamar",
"collectionName": "DAMN.",
"trackName": "LOVE. (FEAT. ZACARI.)",
"collectionCensoredName": "DAMN.",
"trackCensoredName": "LOVE. (FEAT. ZACARI.)",
"artistViewUrl": "https://music.apple.com/us/artist/kendrick-lamar/368183298?uo=4",
"collectionViewUrl": "https://music.apple.com/us/album/love-feat-zacari/1440881047?i=1440881708&uo=4",
"trackViewUrl": "https://music.apple.com/us/album/love-feat-zacari/1440881047?i=1440881708&uo=4",
"previewUrl": "https://audio-ssl.itunes.apple.com/itunes-assets/AudioPreview118/v4/28/40/40/28404037-5570-0709-5601-7eff314e45eb/mzaf_6754627230951906996.plus.aac.p.m4a",
"artworkUrl30": "https://is1-ssl.mzstatic.com/image/thumb/Music128/v4/87/a6/e2/87a6e2e3-cdd2-a2fd-2de5-a7d7505b3225/source/30x30bb.jpg",
"artworkUrl60": "https://is1-ssl.mzstatic.com/image/thumb/Music128/v4/87/a6/e2/87a6e2e3-cdd2-a2fd-2de5-a7d7505b3225/source/60x60bb.jpg",
"artworkUrl100": "https://is1-ssl.mzstatic.com/image/thumb/Music128/v4/87/a6/e2/87a6e2e3-cdd2-a2fd-2de5-a7d7505b3225/source/100x100bb.jpg",
"collectionPrice": 9.99,
"trackPrice": 1.29,
"releaseDate": "2017-04-14T12:00:00Z",
"collectionExplicitness": "explicit",
"trackExplicitness": "explicit",
"discCount": 1,
"discNumber": 1,
"trackCount": 14,
"trackNumber": 10,
"trackTimeMillis": 213400,
"country": "USA",
"currency": "USD",
"primaryGenreName": "Hip-Hop/Rap",
"contentAdvisoryRating": "Explicit",
"isStreamable": true
},
```
1. All information about Petyr Baelish from the Game of Thrones books
```swift
https://www.anapioficeandfire.com/api/characters/823

{
"url": "https://www.anapioficeandfire.com/api/characters/823",
"name": "Petyr Baelish",
"gender": "Male",
"culture": "Valemen",
"born": "In 268 AC, at the Fingers",
"died": "",
"titles": [
"Master of coin (formerly)",
"Lord Paramount of the Trident",
"Lord of Harrenhal",
"Lord Protector of the Vale"
],
"aliases": [
"Littlefinger"
],
"father": "",
"mother": "",
"spouse": "https://www.anapioficeandfire.com/api/characters/688",
"allegiances": [
"https://www.anapioficeandfire.com/api/houses/10",
"https://www.anapioficeandfire.com/api/houses/11"
],
"books": [
"https://www.anapioficeandfire.com/api/books/1",
"https://www.anapioficeandfire.com/api/books/2",
"https://www.anapioficeandfire.com/api/books/3",
"https://www.anapioficeandfire.com/api/books/5",
"https://www.anapioficeandfire.com/api/books/8"
],
"povBooks": [],
"tvSeries": [
"Season 1",
"Season 2",
"Season 3",
"Season 4",
"Season 5",
"Season 6"
],
"playedBy": [
"Aidan Gillen"
]
}

```
1. All the movies Leonardo Dicaprio has acted in
```swift

https://itunes.apple.com/search?term=leonardo+dicaprio

{
"resultCount": 41,
"results": [
{
"wrapperType": "track",
"kind": "feature-movie",
"collectionId": 1151694663,
"trackId": 774084884,
"artistName": "Martin Scorsese",
"collectionName": "10 Years of iTunes Movies - Paramount",
"trackName": "The Wolf of Wall Street",
"collectionCensoredName": "10 Years of iTunes Movies - Paramount",
"trackCensoredName": "The Wolf of Wall Street",
"collectionArtistId": 1008915738,
"collectionArtistViewUrl": "https://itunes.apple.com/us/artist/paramount-home-entertainment-inc/1008915738?uo=4",
"collectionViewUrl": "https://itunes.apple.com/us/movie/the-wolf-of-wall-street/id774084884?uo=4",
"trackViewUrl": "https://itunes.apple.com/us/movie/the-wolf-of-wall-street/id774084884?uo=4",
"previewUrl": "https://video-ssl.itunes.apple.com/itunes-assets/Video111/v4/ff/b7/77/ffb777a8-04c0-56fe-2237-64c09352891e/mzvf_3469655200525770514.640x354.h264lc.U.p.m4v",
"artworkUrl30": "https://is3-ssl.mzstatic.com/image/thumb/Video/v4/f0/40/fb/f040fbc3-3217-5403-bf75-da0687ef9d8f/source/30x30bb.jpg",
"artworkUrl60": "https://is3-ssl.mzstatic.com/image/thumb/Video/v4/f0/40/fb/f040fbc3-3217-5403-bf75-da0687ef9d8f/source/60x60bb.jpg",
"artworkUrl100": "https://is3-ssl.mzstatic.com/image/thumb/Video/v4/f0/40/fb/f040fbc3-3217-5403-bf75-da0687ef9d8f/source/100x100bb.jpg",
"collectionPrice": 12.99,
"trackPrice": 12.99,
"trackRentalPrice": 3.99000,
"collectionHdPrice": 14.99000,
"trackHdPrice": 14.99000,
"trackHdRentalPrice": 3.99000,
"releaseDate": "2013-12-25T08:00:00Z",
"collectionExplicitness": "notExplicit",
"trackExplicitness": "notExplicit",
"discCount": 1,
"discNumber": 1,
"trackCount": 10,
"trackNumber": 3,
"trackTimeMillis": 10806388,
"country": "USA",
"currency": "USD",
"primaryGenreName": "Drama",
"contentAdvisoryRating": "R",
"shortDescription": "Revered filmmaker Martin Scorsese directs the story of New York stockbroker Jordan Belfort (Leonardo",
"longDescription": "Sex. Money. Power. Drugs. Brace yourself for an outrageous true story from legendary filmmaker Martin Scorsese that critics are calling \"a masterpiece for a new generation.” Leonardo DiCaprio delivers the best performance of his career as a young stockbroker hungry for a life of non-stop thrills, where corruption was king and more was never enough. His rise to power earned him the title The Wolf of Wall Street. Together, Scorsese and DiCaprio deliver a story of American excess that is an absolute blast from start to finish.",
"hasITunesExtras": true
},
{
"wrapperType": "track",
"kind": "feature-movie",
"trackId": 326460001,
"artistName": "Jaume Collet-Serra",
"trackName": "Orphan",
"trackCensoredName": "Orphan (2009)",
"trackViewUrl": "https://itunes.apple.com/us/movie/orphan-2009/id326460001?uo=4",
"previewUrl": "https://video-ssl.itunes.apple.com/itunes-assets/Video128/v4/9a/47/8d/9a478d0d-a017-ef61-a2b7-861c48871f6b/mzvf_589934001500238504.640x480.h264lc.U.p.m4v",
"artworkUrl30": "https://is4-ssl.mzstatic.com/image/thumb/Video6/v4/54/85/f1/5485f1d3-785d-8a5c-dabb-83ce05ac21d9/source/30x30bb.jpg",
"artworkUrl60": "https://is4-ssl.mzstatic.com/image/thumb/Video6/v4/54/85/f1/5485f1d3-785d-8a5c-dabb-83ce05ac21d9/source/60x60bb.jpg",
"artworkUrl100": "https://is4-ssl.mzstatic.com/image/thumb/Video6/v4/54/85/f1/5485f1d3-785d-8a5c-dabb-83ce05ac21d9/source/100x100bb.jpg",
"collectionPrice": 12.99,
"trackPrice": 12.99,
"trackRentalPrice": 3.99000,
"collectionHdPrice": 12.99000,
"trackHdPrice": 12.99000,
"trackHdRentalPrice": 3.99000,
"releaseDate": "2009-07-24T07:00:00Z",
"collectionExplicitness": "notExplicit",
"trackExplicitness": "notExplicit",
"trackTimeMillis": 7374213,
"country": "USA",
"currency": "USD",
"primaryGenreName": "Horror",
"contentAdvisoryRating": "R",
"longDescription": "The tragic loss of their unborn child has devastated Kate (Vera Farmiga) and John (Peter Sarsgaard), taking a toll on both their marriage and Kate's fragile psyche as she is plagued by nightmares and haunted by demons from her past. Struggling to regain some semblance of normalcy in their lives, the couple decides to adopt another child. At the local orphanage, both John and Kate find themselves strangely drawn to a young girl named Esther (Isabelle Fuhrman)...but Esther is not what she appears to be and, concerned for the safety of her family, Kate tries to get John and others to see past Esther's sweet facade. But her warnings go unheeded until it may be too late...for everyone."
}

```
