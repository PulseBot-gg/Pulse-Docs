---
layout: default
title: Commands
nav_order: 2
permalink: /commands
---

<span class="fs-5">[Docs Home](https://docs.pulseproject.io){: .btn }</span><br><br>
<span class="fs-4">[Website](https://pulseproject.io){: .btn .btn-outline }</span>
<span class="fs-4">[Invite](https://pulseproject.io/invite){: .btn .btn-outline }</span>
<span class="fs-4">[Terms](https://pulseproject.io/terms){: .btn .btn-outline }</span>
<span class="fs-4">[Privacy](https://pulseproject.io/privacy){: .btn .btn-outline }</span>

---

# Commands
{: .no_toc }

<div class="menu">
  <span class="selectionsBoarder">
    <h4 class="sectionsTitle">Command Categories</h4>
    <div class="selectionsEdge">
      <div class="selections">
        <div id="all" class="selection" onClick='setSelection("all");' style="cursor: pointer;">
          All
        </div>
        <div id="other" class="selection" onClick='setSelection("other");' style="cursor: pointer;">
          Misc.
        </div>
        <div id="wrapper" class="selection" onClick='setSelection("wrapper");' style="cursor: pointer;">
          Wrappers
        </div>
        <div id="info" class="selection" onClick='setSelection("info");' style="cursor: pointer;">
          Info
        </div>
        <div id="connecting" class="selection" onClick='setSelection("connecting");' style="cursor: pointer;">
          Connecting
        </div>
        <div id="requesting" class="selection" onClick='setSelection("requesting");' style="cursor: pointer;">
          Requesting
        </div>
        <div id="player" class="selection" onClick='setSelection("player");' style="cursor: pointer;">
          Player
        </div>
        <div id="queue" class="selection" onClick='setSelection("queue");' style="cursor: pointer;">
          Queue
        </div>
      </div>
    </div>
  </span>

  <div class="options">
    <div class="option other">
      <div class="optiontitle">
        <b>Help</b>
      </div>
      <div class="optioncontent">
        Returns a help message with useful links and suggestions.
      </div>
    </div>
    <div class="option other">
      <div class="optiontitle">
        <b>Config</b> <a>(Listing#) (Value)</a>
      </div>
      <div class="optioncontent">
        Command that configures how the bot will interact with the server.
        <br>
        <br>Permission: <c>MANAGE_SERVER</c>
        <br>Aliases: <a>Configuration, Settings, Conf, Con</a>
      </div>
    </div>
    <div class="option other">
      <div class="optiontitle">
        <b>Lyrics</b> <a>(Search)</a>
      </div>
      <div class="optioncontent">
        Links to the lyrics of the playing track or requested search.
        <br>
        <br>Aliases: <a>Lyric, Lyr, Ly</a>
      </div>
    </div>
    <div class="option other">
      <div class="optiontitle">
        <b>Sotd (Date)</b>
      </div>
      <div class="optioncontent">
        Displays the song of the day! If the request is made before 12PM EST, this will return the sotd of the day before. 
        <br>
        <br><d>To view more information about the SOTD feature, the Date or Time Frame argument, or Koodos in general, check out the Koodos section on the Integrations page!</d>
      </div>
    </div>
    <div class="option other">
      <div class="optiontitle">
        <b>Sotw (Date)</b>
      </div>
      <div class="optioncontent">
        Displays the songs of the past week! If the request is made before 12PM EST and includes the current date, this will return the sotd of the day before as the latest song. 
        <br>
        <br><d>To view more information about the SOTD feature, the Date or Time Frame argument, or Koodos in general, check out the Koodos section on the Integrations page!</d>
      </div>
    </div>
    <div class="option other">
      <div class="optiontitle">
        <b>Sotm (Date)</b>
      </div>
      <div class="optioncontent">
        Displays the songs of the past month! If the request is made before 12PM EST and includes the current date, this will return the sotd of the day before as the latest song. 
        <br>
        <br><d>To view more information about the SOTD feature, the Date or Time Frame argument, or Koodos in general, check out the Koodos section on the Integrations page!</d>
      </div>
    </div>
    <div class="option wrapper">
      <div class="optiontitle">
        <b>Play</b> <a>(Media)</a>
      </div>
      <div class="optioncontent">
        As a wrapper command, this command acts as an alias to the commands listed below, and determines which command to execute based off of arguments provided, and the bot's current activity. For more info on playing media, please read the "Playing Media" section on the <a href="https://pulseproject.io/usage">Usage</a> page.
        <br>
        <br>Executes: <a>Resume, Enque</a>
      </div>
    </div>
    <div class="option wrapper">
      <div class="optiontitle">
        <b>P</b> <a>(Media)</a>
      </div>
      <div class="optioncontent">
        As a wrapper command, this command acts as an alias to the commands listed below, and determines which command to execute based off of arguments provided, and the bot's current activity. For more info, please read the "Playing Media" section on the <a href="https://pulseproject.io/usage">Usage</a> page.
        <br>
        <br>Executes: <a>Pause, Resume, Enque</a>
      </div>
    </div>
    <div class="option wrapper">
      <div class="optiontitle">
        <b>Que</b> <a>(Media or Page#)</a>
      </div>
      <div class="optioncontent">
        As a wrapper command, this command acts as an alias to the commands listed below, and determines which command to execute based off of arguments provided, and the bot's current activity. For more info, please read the "Playing Media" section on the <a href="https://pulseproject.io/usage">Usage</a> page.
        <br>
        <br>Aliases: <a>Q</a>
        <br>Executes: <a>Queue, Enque</a>
      </div>
    </div>
    <div class="option info">
      <div class="optiontitle">
        <b>Status</b>
      </div>
      <div class="optioncontent">
        Returns a timings report of the bot’s connection to Discord services, as well as some useful suggestions and links.
        <br>
        <br>Aliases: <a>Connection, Latency, Stat, Ping, Lag</a>
      </div>
    </div>
    <div class="option info">
      <div class="optiontitle">
        <b>NowPlaying</b>
      </div>
      <div class="optioncontent">
        Returns a formatted and detailed message of the currently playing track and current player status.
        <br>
        <br>Aliases: <a>Timestamp, Stamp, Song, Info, Time, Np</a>
      </div>
    </div>
    <div class="option info">
      <div class="optiontitle">
        <b>Queue</b> <a>(Page#)</a>
      </div>
      <div class="optioncontent">
        Returns a formatted message of the next tracks in the queue. There may be multiple pages.
        <br>
        <br>Applicable Wrapper Commands: <a>Que, Q</a>
      </div>
    </div>
    <div class="option connecting">
      <div class="optiontitle">
        <b>Connect</b>
      </div>
      <div class="optioncontent">
        Connects the bot to your channel. The bot will not leave others if DJ restriction is enabled, unless the requester is a DJ.
        <br>
        <br><d>This command can be DJ restricted.</d>
        <br>Aliases: <a>Join</a>
      </div>
    </div>
    <div class="option connecting">
      <div class="optiontitle">
        <b>Disconnect</b>
      </div>
      <div class="optioncontent">
        Disconnects the bot from your server. The bot will not leave others if DJ restriction is enabled, unless the requester is a DJ.
        <br>
        <br><d>This command can be DJ restricted.</d>
        <br>Aliases: <a>Leave, Quit, Dis, Dc</a>
      </div>
    </div>
    <div class="option requesting">
      <div class="optiontitle">
        <b>Enque</b> <a>&lt;Media&lt;</a>
      </div>
      <div class="optioncontent">
        Enques the searched or linked media at the end of the queue. If no media is specified, the bot will attempt to use the requester's Spotify rich presence. For more info, please read the "Playing Media" section on the <a href="https://pulseproject.io/usage">Usage</a> page.
        <br>
        <br>Aliases: <a>Enque, En, Eq</a>
        <br>Applicable Wrapper Commands: <a>Play, P, Que, Q</a>
      </div>
    </div>
    <div class="option requesting">
      <div class="optiontitle">
        <b>EnqueFirst</b> <a>&lt;Media&lt;</a>
      </div>
      <div class="optioncontent">
        Enques the searched or linked media at the start of the queue. If no media is specified, the bot will attempt to use the requester's Spotify rich presence. For more info, please read the "Playing Media" section on the <a href="https://pulseproject.io/usage">Usage</a> page.
        <br>
        <br><d>This command can be DJ restricted.</d>
        <br>Aliases: <a>EnqueFirst, Enf, Eqf, Pf</a>
      </div>
    </div>
    <div class="option requesting">
      <div class="optiontitle">
        <b>EnqueNow</b> <a>&lt;Media&lt;</a>
      </div>
      <div class="optioncontent">
        Enques the searched or linked media immediately, and adds any additional items at the start of the queue. If no media is specified, the bot will attempt to use the requester's Spotify rich presence. For more info, please read the "Playing Media" section on the <a href="https://pulseproject.io/usage">Usage</a> page.
        <br>
        <br><d>This command can be DJ restricted.</d>
        <br>Aliases: <a>EnqueNow, Enn, Eqn, Pn</a>
      </div>
    </div>
    <div class="option player">
      <div class="optiontitle">
        <b>Pause</b>
      </div>
      <div class="optioncontent">
        Pauses playing media.
        <br>
        <br><d>This command can be DJ restricted.</d>
        <br>Aliases: <a>Pse, Ps</a>
        <br>Applicable Wrapper Commands: <a>P</a>
      </div>
    </div>
    <div class="option player">
      <div class="optiontitle">
        <b>Resume</b>
      </div>
      <div class="optioncontent">
        Resumes paused media.
        <br>
        <br><d>This command can be DJ restricted.</d>
        <br>Aliases: <a>Pse, Ps</a>
        <br>Applicable Wrapper Commands: <a>Play, P</a>
      </div>
    </div>
    <div class="option player">
      <div class="optiontitle">
        <b>Stop</b>
      </div>
      <div class="optioncontent">
        Stops currently playing media, and clears the previous and future queues.
        <br>
        <br><d>This command can be DJ restricted.</d>
        <br>Aliases: <a>Stp</a>
      </div>
    </div>
    <div class="option player">
      <div class="optiontitle">
        <b>Volume</b> <a>(Level)</a>
      </div>
      <div class="optioncontent">
        Returns the current volume, or sets the volume to the specified level.
        <br>
        <br><d>This command can be DJ restricted.</d>
        <br>Aliases: <a>Vol, V</a>
      </div>
    </div>
    <div class="option player">
      <div class="optiontitle">
        <b>Replay</b>
      </div>
      <div class="optioncontent">
        Restarts the currently playing track.
        <br>
        <br><d>This command can be DJ restricted.</d>
        <br>Aliases: <a>Restart, Re</a>
      </div>
    </div>
    <div class="option player">
      <div class="optiontitle">
        <b>Seek</b> <a>&lt;Time&gt;</a>
      </div>
      <div class="optioncontent">
        Seeks to the specified time in the song.
        <br>
        <br><d>This command can be DJ restricted.</d>
        <br>Aliases: <a>S</a>
      </div>
    </div>
    <div class="option player">
      <div class="optiontitle">
        <b>Fastforward</b> <a>(Time)</a>
      </div>
      <div class="optioncontent">
        Fastforwards the song by 10 seconds, or by the time specified.
        <br>
        <br><d>This command can be DJ restricted.</d>
        <br>Aliases: <a>Ff</a>
      </div>
    </div>
    <div class="option player">
      <div class="optiontitle">
        <b>Rewind</b> <a>(Time)</a>
      </div>
      <div class="optioncontent">
        Rewinds the song by 10 seconds, or by the time specified.
        <br>
        <br><d>This command can be DJ restricted.</d>
        <br>Aliases: <a>Rw</a>
      </div>
    </div>
    <div class="option queue">
      <div class="optiontitle">
        <b>Clear</b>
      </div>
      <div class="optioncontent">
        Clears the future queue.
        <br>
        <br><d>This command can be DJ restricted.</d>
        <br>Aliases: <a>Empty, Cl</a>
      </div>
    </div>
    <div class="option queue">
      <div class="optiontitle">
        <b>ForceSkip</b>
      </div>
      <div class="optioncontent">
        Forcibly skips to the next track.
        <br>
        <br><d>This command can be DJ restricted.</d>
        <br>Aliases: <a>ForceNext, Fs, Fn</a>
      </div>
    </div>
    <div class="option queue">
      <div class="optiontitle">
        <b>SkipTo</b> <a>&lt;Position In Queue&lt;</a>
      </div>
      <div class="optioncontent">
        Skips to a position in the queue.
        <br>
        <br>Aliases: <a>GoTo, St, Gt</a>
      </div>
    </div>
    <div class="option queue">
      <div class="optiontitle">
        <b>Skip</b>
      </div>
      <div class="optioncontent">
        Adds a vote to skip to the next track.
        <br>
        <br>Aliases: <a>Next, N</a>
      </div>
    </div>
    <div class="option queue">
      <div class="optiontitle">
        <b>Previous</b>
      </div>
      <div class="optioncontent">
        Moves back to the previous played track in the current session.
        <br>
        <br><d>This command can be DJ restricted.</d>
        <br>Aliases: <a>Prev, Last, Back, Pr</a>
      </div>
    </div>
    <div class="option queue">
      <div class="optiontitle">
        <b>Repeat</b>
      </div>
      <div class="optioncontent">
        Toggles repeating of tracks from Off->Track->Queue->Off respectively repeating.
        <br>
        <br><d>This command can be DJ restricted.</d>
        <br>Aliases: <a>Loop, L</a>
      </div>
    </div>
    <div class="option queue">
      <div class="optiontitle">
        <b>Shuffle</b>
      </div>
      <div class="optioncontent">
        Shuffles the future queue.
        <br>
        <br><d>This command can be DJ restricted.</d>
        <br>Aliases: <a>Shuf, Mix, Sh</a>
      </div>
    </div>
    <div class="option queue">
      <div class="optiontitle">
        <b>Flip</b>
      </div>
      <div class="optioncontent">
        Flips the future queue.
        <br>
        <br><d>This command can be DJ restricted.</d>
        <br>Aliases: <a>Flop, Fl</a>
      </div>
    </div>
    <div class="option queue">
      <div class="optiontitle">
        <b>Move</b> <a>&lt;Item#&gt; &lt;Position#&gt;</a>
      </div>
      <div class="optioncontent">
        Moves an item in the future queue from one position to another.
        <br>
        <br><d>This command can be DJ restricted.</d>
        <br>Aliases: <a>M</a>
      </div>
    </div>
    <div class="option queue">
      <div class="optiontitle">
        <b>Remove</b> <a>&lt;Item#&gt;</a>
      </div>
      <div class="optioncontent">
        Removes an item from the future queue.
        <br>
        <br><d>This command can be DJ restricted.</d>
        <br>Aliases: <a>Rem, R</a>
      </div>
    </div>
  </div>
</div>

<style>

/*body {
  color: #fff;
  background-color: #38383b;
  font-family: Arial;
  font-size: 20px;
}*/

.menu {
  color: #fff;
  font-size: 20px;
  display: flex;
  font-family: Arial;
  font-size: 20px;
}
.sectionsTtitle {
  margin: 5px;
}
.selectionsBoarder {
  display: block;
  float: left;
  margin: 25px;
  width: 27%;
  height: fit-content;
  padding: 15px;
  border-radius: 15px;
  background-color: #44434d;
  text-align: center;
  box-shadow: 0 8px 8px 0 rgba(0, 0, 0, 0.4), 0 6px 20px 0 rgba(0, 0, 0, 0.2);
}
.selectionsEdge {
  width: 100%;
  display: flex;
}
.selections {
  width: 100%;
  display: block;
}
.selection {
  display: block;
  margin: 5px 0px;
  padding: 10px;
  border-radius: 3px;
  color: #fff;
  background-color: #222;
  box-shadow: 0 5px 5px 0 rgba(0, 0, 0, 0.2), 0 5px 5px 0 rgba(0, 0, 0, 0.2);
  transition: ease-in-out 0.2s;
}
.activeSelection, .selection:hover {
  background-color: #000;
  box-shadow: 0px 0px 0px black;
}
.options {
  float: left;
  display: block;
  margin: 25px;
  width: 73%
}
.option {
  overflow: hidden;
  text-align: left;
  width: 100%;
  margin: 5px 0px;
  border-radius: 10px;
  color: #fff;
  background-color: #44434d;
  box-shadow: 0 1px 5px 0 rgba(0, 0, 0, 0.2), 0 1px 5px 0 rgba(0, 0, 0, 0.2);
  transition: ease-in-out 0.2s;
}
.optionactive, .option:hover {
  background-color: #000;
  box-shadow: 0px 0px 0px black;
}
.optiontitle {
  padding: 20px;
  text-align: left;
  cursor: pointer;
  line-height: 15px;
}
.optioncontent {
  padding: 20px;
  display: none;
  cursor: default;
  overflow: hidden;
  line-height: 30px;
}
a {
  color: #bbb;
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

/*@media only screen and (max-width: 1050px) {*/
  .menu {
    flex-direction: column;
    width: auto;
  }
  .selectionsBoarder {
    display: block;
    width: auto;
  }
  .selections {
    display: inline-flex;
    width: auto;
    flex-wrap: wrap;
    justify-content: center
  }
  .selection {
    width: auto;
    margin: 15px;
  }
  .options {
    width: auto;
  }
/*}*/
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
  var toShow = ["other", "info", "connecting", "requesting",  "player", "queue", "wrapper"];
  if (selection !== "all") {
    toShow = [selection];
  }
  onlyEnableCategories(toShow);
}

setSelection("all");
</script>
