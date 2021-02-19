---
layout: default
title: Integrations
nav_order: 2
has_children: true
permalink: /Integrations
---

# Integrations!
{: .no_toc }

<span class="fs-5">[Docs Home](https://docs.pulseproject.io){: .btn }</span><br><br>
<span class="fs-4">[Website](https://pulseproject.io){: .btn .btn-outline }</span>
<span class="fs-4">[Invite](https://pulseproject.io/invite){: .btn .btn-outline }</span>
<span class="fs-4">[Terms](https://pulseproject.io/terms){: .btn .btn-outline }</span>
<span class="fs-4">[Privacy](https://pulseproject.io/privacy){: .btn .btn-outline }</span>

---

<div class="menu">
  <div class="options">
  
    <div class="option">
      <div class="optiontitle">
        <img class="sourceimage" src="https://storage.googleapis.com/koodos-web/kody_logo.png" alt="" style="width:75px;height:75px;">
        <div class="optiontitletext">
          <b>Koodos</b>
        </div>
      </div>
      <div class="optioncontent">
        <div class="optioncontentsections">
          <div class="optioncontentsection">
          <a target="_blank" href="https://koodos.com">Visit Website</a>
          <br>
          <br><b><u>Supported Media Sources</u></b>
          <br><a>☑ YouTube</a>
          <br>
          <br><b><u>Supported Media Types</u></b>
          <br><a>☑ Videos</a>
          <br><a>☑ Livestreams</a>
        </div>
        <div class="optioncontentsectiondescription">
          <br>
          <br><b><u>Description</u></b>
          <br>Koodos is an SMS based platform, where you can share and discover music through emojis! ✨ 
          Top curations can get featured as a song of the day. These songs are what you can play through Pulse! 
          You can check out these songs with the commands listed below (d=day, w=week, m=month: 
          <br>
          <br>Example 1: <c><a>?sotd</a></c>
          <br>Example 2: <c><a>?sotw</a></c>
          <br>Example 3: <c><a>?sotm</a></c>
          <br>
          <br>The responses by the bot give you a command you can use to enque the tracks. 
          Though, the date arument is optional if you plan on playing the current date. 
          However, if you wish to view a past song, past week of songs, or past month of songs, 
          you can always specify a date with the given format below (the "ago" is optional): 
          <br>
          <br>Example 1: <c><a>?sotd 3 days ago</a></c>
          <br>Example 2: <c><a>?sotd 2 weeks</a></c>
          <br>Example 3: <c><a>?sotd 1 m</a></c>
          <br>
          <br>You can also use any combination of the date format, as long as the order is Year, then Month, then Day: 
          <br>
          <br>Example 1: <c><a>?sotm YYYY-MM-DD</a></c>
          <br>Example 2: <c><a>?sotm YY/M/D</a></c>
          <br>
          <br>You may also notice, that the command to play any of these featured songs, 
          is as simple as adding the enque option you prefer before the command. 
          This is applicable for all forms, and will enque the track(s) with the enque type. 
          <br>
          <br>Example 1: <c><a>?p sotd 2 m</a></c>
          <br>Example 2: <c><a>?pn sotd 21-1-1</a></c>
          <br>Example 3: <c><a>?pf sotd 2020/09/30</a></c>  
          <br>
          <br>It's even possible to play the URL as well!
          <br>
          <br>Example 1: <c><a>?p https://koodos.com/sotd?date=2020-11-09</a></c>
          <br>
          <br>To learn more about Koodos, Visit the website located at the top of this section!
        </div>
        </div>
      </div>
    </div>
  
    <div class="option">
      <div class="optiontitle">
        <img class="sourceimage" src="https://img.talkandroid.com/uploads/2015/05/iheartradio-logo.png" alt="" style="width:75px;height:75px;">
        <div class="optiontitletext">
          <b>iHeartRadio</b>
        </div>
      </div>
      <div class="optioncontent">
        <div class="optioncontentsections">
          <div class="optioncontentsection">
          <a target="_blank" href="https://www.iheart.com">Visit Website</a>
          <br>
          <br><b><u>Supported Media Types</u></b>
          <br><a>☑ Live Radio</a>
        </div>
        <div class="optioncontentsectiondescription">
          <br>
          <br><b><u>Description</u></b>
          <br>The current iHeartRadio implementation only supports Live radio stations for the time being. 
          To play a station from iHeartRadio, you need to navigate to the radion station and copy the URL, or the share link URL.
          The format if the radio station should have "/live" followed by the id "/hits-973-5906/" as shown in the example below.
          If your URL doesn't look like this, you have the wrong URL.
          <br>
          <br>Example 1: <c><a>?play https://www.iheart.com/live/hits-973-5906/</a></c>
        </div>
        </div>
      </div>
    </div>
  
    <div class="option">
      <div class="optiontitle">
        <img class="sourceimage" src="https://cdn0.iconfinder.com/data/icons/internet-2020/1080/Applemusicandroid-256.png" alt="" style="width:75px;height:75px;">
        <div class="optiontitletext">
          <b>Apple Music</b>
        </div>
      </div>
      <div class="optioncontent">
        <div class="optioncontentsections">
          <div class="optioncontentsection">
          <a target="_blank" href="https://music.apple.com">Visit Website</a>
          <br>
          <br><b><u>Supported Media Types</u></b>
          <br><a>☑ Songs</a>
          <br><a>☑ Albums</a>
          <br><a>☑ Playlists</a>
        </div>
        <div class="optioncontentsectiondescription">
          <br>
          <br><b><u>Description</u></b>
          <br>To play any of the supported media types, just copy the share link URL of the media, and use it with any of the enque commands. 
          ONLY share-links are supported! 
          Please note, that because the Apple Music API doesn't have a way to identify track information in user-made playlists, only apple-premade playlists are supported. 
          Until Apple fixes their API, there is nothing more that can be done about this issue.
          <br>
          <br>Example 1: <c><a>?play https://music.apple.com/us/album/the-boy-who-died-wolf/1149445034</a></c>
        </div>
        </div>
      </div>
    </div>
  
    <div class="option">
      <div class="optiontitle">
        <img class="sourceimage" src="https://cdn2.iconfinder.com/data/icons/social-icons-33/128/Spotify-256.png" alt="" style="width:75px;height:75px;">
        <div class="optiontitletext">
          <b>Spotify</b>
        </div>
      </div>
      <div class="optioncontent">
        <div class="optioncontentsections">
          <div class="optioncontentsection">
          <a target="_blank" href="https://www.spotify.com">Visit Website</a>
          <br>
          <br><b><u>Supported Media Types</u></b>
          <br><a>☑ Songs</a>
          <br><a>☑ Albums</a>
          <br><a>☑ Playlists</a>
        </div>
        <div class="optioncontentsectiondescription">
          <br>
          <br><b><u>Description</u></b>
          <br>To play any of the supported media types, just copy the URL or URI of the media, and use it with any of the enque commands.
          If you have your Spotify account linked to your Discord account, and Spotify is visible as an activity, 
          Pulse can retrieve the track you're currently listening to and enque it accordingly.
          <br>
          <br>Example 1: <c><a>?enque</a></c>
        </div>
        </div>
      </div>
    </div>
  
    <div class="option">
      <div class="optiontitle">
        <img class="sourceimage" src="https://i2.wp.com/www.goldinlisa.com/wp/wp-content/uploads/2018/01/deezer-logo-circle.png" alt="" style="width:75px;height:75px;">
        <div class="optiontitletext">
          <b>Deezer</b>
        </div>
      </div>
      <div class="optioncontent">
        <div class="optioncontentsections">
          <div class="optioncontentsection">
          <a target="_blank" href="https://www.deezer.com">Visit Website</a>
          <br>
          <br><b><u>Supported Media Types</u></b>
          <br><a>☑ Tracks(Songs)</a>
          <br><a>☑ Albums</a>
          <br><a>☑ Playlists</a>
        </div>
        <div class="optioncontentsectiondescription">
          <br>
          <br><b><u>Description</u></b>
          <br>To play any of the supported media types, just copy the URL or share link URL of the media, and use it with any of the enque commands.
          <br>
          <br>Example 1: <c><a>?play https://deezer.page.link/ozTr8ZqzHqnBV1aZ6</a></c>
          <br>Example 2: <c><a>?play https://www.deezer.com/us/album/116822402?utm_campaign=clipboard-generic&utm_source=user_sharing&utm_medium=desktop&utm_content=playlist-8569166722</a></c>
        </div>
        </div>
      </div>
    </div>
  
    <div class="option">
      <div class="optiontitle">
        <img class="sourceimage" src="https://cdn3.iconfinder.com/data/icons/popular-services-brands/512/youtube-256.png" alt="" style="width:75px;height:75px;">
        <div class="optiontitletext">
          <b>YouTube</b>
        </div>
      </div>
      <div class="optioncontent">
        <div class="optioncontentsections">
          <div class="optioncontentsection">
          <a target="_blank" href="https://www.youtube.com">Visit Website</a>
          <br>
          <br><b><u>Supported Media Types</u></b>
          <br><a>☑ Videos</a>
          <br><a>☑ Playlists</a>
          <br><a>☑ Mixes</a>
          <br><a>☑ Livestreams</a>
          <br><a>☑ Searching</a>
        </div>
        <div class="optioncontentsectiondescription">
          <br>
          <br><b><u>Description</u></b>
          <br>To play any of the supported media types, copy the URL (Or share link) of the media, and use it with any of the enque commands. 
          You can also type anything you want to be search. All searches will be performed on this platform by default. 
          Please also note, that this will be the default platform for other media sources that can't have their audio accessed directly.
          <br>
          <br>Example 1: <c><a>?play https://www.youtube.com/watch?v=dQw4w9WgXcQ</a></c>
          <br>Example 2: <c><a>?play Rick Astley - Never Gonna Give You Up</a></c>
        </div>
        </div>
      </div>
    </div>
  
    <div class="option">
      <div class="optiontitle">
        <img class="sourceimage" src="https://cdn3.iconfinder.com/data/icons/popular-services-brands-vol-2/512/twitch-256.png" alt="" style="width:75px;height:75px;">
        <div class="optiontitletext">
          <b>Twitch</b>
        </div>
      </div>
      <div class="optioncontent">
        <div class="optioncontentsections">
          <div class="optioncontentsection">
          <a target="_blank" href="https://www.twitch.tv">Visit Website</a>
          <br>
          <br><b><u>Supported Media Types</u></b>
          <br><a>☑ Livestreams</a>
        </div>
        <div class="optioncontentsectiondescription">
          <br>
          <br><b><u>Description</u></b>
          <br>To play any of the supported media types, copy the URL of the stream, and use it with any of the enque commands. 
          <br>
          <br>Example 1: <c><a>?play https://www.twitch.tv/pewdiepie_hyper</a></c>
        </div>
        </div>
      </div>
    </div>
  
    <div class="option">
      <div class="optiontitle">
        <img class="sourceimage" src="https://cdn0.iconfinder.com/data/icons/shift-logotypes/32/Vimeo-256.png" alt="" style="width:75px;height:75px;">
        <div class="optiontitletext">
          <b>Vimeo</b>
        </div>
      </div>
      <div class="optioncontent">
        <div class="optioncontentsections">
          <div class="optioncontentsection">
          <a target="_blank" href="https://www.twitch.tv">Visit Website</a>
          <br>
          <br><b><u>Supported Media Types</u></b>
          <br><a>☑ Videos</a>
        </div>
        <div class="optioncontentsectiondescription">
          <br>
          <br><b><u>Description</u></b>
          <br>To play the supported media type, copy the URL of the video, and use it with any of the enque commands. 
          <br>
          <br>Example 1: <c><a>?play https://vimeo.com/148751763</a></c>
        </div>
        </div>
      </div>
    </div>
  
    <div class="option">
      <div class="optiontitle">
        <img class="sourceimage" src="https://cdn4.iconfinder.com/data/icons/social-flat-rounded-rects/512/bandcamp-256.png" alt="" style="width:75px;height:75px;">
        <div class="optiontitletext">
          <b>BandCamp</b>
        </div>
      </div>
      <div class="optioncontent">
        <div class="optioncontentsections">
          <div class="optioncontentsection">
          <a target="_blank" href="https://www.bandcamp.com">Visit Website</a>
          <br>
          <br><b><u>Supported Media Types</u></b>
          <br><a>☑ Tracks</a>
          <br><a>☑ Albums</a>
        </div>
        <div class="optioncontentsectiondescription">
          <br>
          <br><b><u>Description</u></b>
          <br>To play any of the supported media types, copy the URL of the media, and use it with any of the enque commands. 
          <br>
          <br>Example 1: <c><a>?play https://dirtyghosts.bandcamp.com/album/let-it-pretend?from=hp</a></c>
        </div>
        </div>
      </div>
    </div>
  
    <div class="option">
      <div class="optiontitle">
        <img class="sourceimage" src="https://cdn0.iconfinder.com/data/icons/most-usable-logos/120/SoundCloud-128.png" alt="" style="width:75px;height:75px;">
        <div class="optiontitletext">
          <b>SoundCloud</b>
        </div>
      </div>
      <div class="optioncontent">
        <div class="optioncontentsections">
          <div class="optioncontentsection">
          <a target="_blank" href="https://www.soundcloud.com/">Visit Website</a>
          <br>
          <br><b><u>Supported Media Types</u></b>
          <br><a>☑ Tracks</a>
          <br><a>☑ Playlists</a>
        </div>
        <div class="optioncontentsectiondescription">
          <br>
          <br><b><u>Description</u></b>
          <br>To play any of the supported media types, copy the URL of the media, and use it with any of the enque commands. 
          <br>
          <br>Example 1: <c><a>?play https://soundcloud.com/cj50058/whoopty-1</a></c>
        </div>
        </div>
      </div>
    </div>
  
    <div class="option">
      <div class="optiontitle">
        <img class="sourceimage" src="https://image.winudf.com/v2/image/aW8uZ2V0eWFybi55YXJuX2ljb25fMTUxMjAyMzA3OF8wNTI/icon.png?w=170&fakeurl=1" alt="" style="width:75px;height:75px;">
        <div class="optiontitletext">
          <b>GetYarn</b>
        </div>
      </div>
      <div class="optioncontent">
        <div class="optioncontentsections">
          <div class="optioncontentsection">
          <a target="_blank" href="https://www.getyarn.io">Visit Website</a>
          <br>
          <br><b><u>Supported Media Types</u></b>
          <br><a>☑ Videos</a>
        </div>
        <div class="optioncontentsectiondescription">
          <br>
          <br><b><u>Description</u></b>
          <br>To play any of the supported media types, copy the URL of the media, and use it with any of the enque commands. 
          <br>
          <br>Example 1: <c><a>?play https://www.getyarn.io/yarn-clip/c8b6499c-40e3-435e-b5f2-c41e464144a6</a></c>
        </div>
        </div>
      </div>
    </div>
  
    <div class="option">
      <div class="optiontitle">
        <img class="sourceimage" src="https://cdn2.iconfinder.com/data/icons/miscellaneous-7/100/durable-256.png" alt="" style="width:75px;height:75px;">
        <div class="optiontitletext">
          <b>Direct Media Links</b>
        </div>
      </div>
      <div class="optioncontent">
        <div class="optioncontentsections">
          <div class="optioncontentsection">
          <a>No Website Availible</a>
          <br>
          <br><b><u>Supported Media Types</u></b>
          <br><a>☑ MP3</a>
          <br><a>☑ FLAC</a>
          <br><a>☑ WAV</a>
          <br><a>☑ Matroska/WebM (AAC, Opus or Vorbis codecs)</a>
          <br><a>☑ MP4/M4A (AAC codec)</a>
          <br><a>☑ OGG streams (Opus, Vorbis and FLAC codecs)</a>
          <br><a>☑ AAC streams</a>
          <br><a>☑ Stream playlists (M3U and PLS)</a>
          
        </div>
        <div class="optioncontentsectiondescription">
          <br>
          <br><b><u>Description</u></b>
          <br>To play any of the supported media types, copy the URL of the media, and use it with any of the enque commands. 
          <br>
          <br>Example 1: <c><a>?play https://example.com/example.mp3</a></c>
        </div>
        </div>
      </div>
    </div>
    
    
  </div>
</div>

<style>

body {
display: block;
  color: #fff;
  background-color: #38383b;
  font-family: Arial;
  font-size: 20px;
  width: 100%;
  margin: 0px;
  margin: auto;
}

.menu {
  font-size: 20px;
  display: block;
  width: 100%;
  margin: auto;
  
}
.options {
  float: left;
  display: block;
  width: 100%
}
.option {
  overflow: hidden;
  text-align: left;
  width: 100%;
  margin: 10px 0px;
  border-radius: 10px;
  color: #fff;
  background-color: #222;
  box-shadow: 0 1px 5px 0 rgba(0, 0, 0, 0.2), 0 1px 5px 0 rgba(0, 0, 0, 0.2);
  transition: ease-in-out 0.2s;
}
.optionactive, .option:hover {
  width: 100%;
  background-color: #000;
  box-shadow: 0px 0px 0px black;
}

.optiontitletext {
  margin-top: auto;
  margin-bottom: auto;
  padding: 2% 100% 2% 15px;
  min-width: max-content;
}
.sourceimage {
  border: none;
  border-radius: 75px;
  margin: auto;
}
.optiontitle {
  width: 100%;
  margin: auto;
  padding: 20px;
  text-align: left;
  cursor: pointer;
  line-height: 15px;
  display: inline-flex;
}
.optioncontent {
  padding: 20px;
  display: none;
  cursor: default;
  overflow: hidden;
  line-height: 30px;
  overflow-wrap: break-word;
}
.optioncontentsections {
  display: inline-flex;
}
.optioncontentsection {
  display: block;
  margin: 15px;
  min-width: max-content;
}
.optioncontentsectiondescription {
  display: block;
  margin: 15px;
  width: 100%;
}
a {
  color: #bbb;
  text-decoration: none;
}
c {
  color: #faa;
  font-weight: normal;
  font-family: Courier New;
}
d {
  color: #ffa;
  font-weight: normal;
}

@media only screen and (max-width: 1050px) {
  .optioncontentsections {
    display: block;
  }
}

</style>

<script>
function onlyEnableCategories(ids) {
  var cats = document.getElementsByClassName("option");
  for(i = 0; i < cats.length; i++) {
    cats[i].style.display = "none";
  }
  for(i = 0; i < ids.length; i++) {
    var elms = document.getElementsByClassName(ids[i]);
    for (n = 0; n < elms.length; n++) {
      elms[n].style.display = "block";
    }
  }
}

var titles = document.getElementsByClassName("optiontitle");
for (i = 0; i < titles.length; i++) {
  titles[i].addEventListener("click", function() {
    this.parentElement.classList.toggle("optionactive");
    var content = this.nextElementSibling;
    if (content.style.display === "block") {
      content.style.display = "none";
    } else {
      content.style.display = "block";
    }
  });
}
var activeSelection = "";
function setSelection(selection) {
  if (activeSelection === selection) {
    return;
  }
  
  activeSelection = selection;
  
  var sels = document.getElementsByClassName("selection");
  for(i = 0; i < sels.length; i++) {
    sels[i].classList.remove("activeSelection");
  }
  document.getElementById(selection).classList.add("activeSelection");
  var toShow = ["settings", "other", "wrapper", "requesting", "info", "player", "queue"];
  if (selection !== "all") {
    toShow = [selection];
  }
  onlyEnableCategories(toShow);
}

setSelection("all");
</script>
