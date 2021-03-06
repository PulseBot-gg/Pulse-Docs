---
layout: default
title: FAQ
nav_order: 4
permalink: /faq
---

<span class="fs-5">[Docs Home](https://docs.pulsebot.gg){: .btn }</span><br><br>
<span class="fs-4">[Website](https://pulsebot.gg){: .btn .btn-outline }</span>
<span class="fs-4">[Invite](https://pulsebot.gg/invite){: .btn .btn-outline }</span>
<span class="fs-4">[Terms](https://pulsebot.gg/terms){: .btn .btn-outline }</span>
<span class="fs-4">[Privacy](https://pulsebot.gg/privacy){: .btn .btn-outline }</span>

---

# FAQ
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## What is Pulse?

 - Please read [here](https://docs.pulsebot.gg/#what-is-pulse).

<br>

## How can I use Pulse?

 - Please read [here](https://docs.pulsebot.gg/#adding-pulse).

<br>

## What is the Pulse server for?
 - Monitoring Pulse’s status.
 - Viewing the latest Pulse updates and features.
 - Making suggestions.
 - Getting support.
 - Visiting the community.

<br>

## How do I use Pulse or it’s features?

 - Please read [here](https://docs.pulsebot.gg/#adding-pulse).

<br>

## What permissions does Pulse use, and why?

These are the bare-minimum permissions Pulse requires to operate normally. If you are experiencing problems with pulse, or are unsure if your server/channels are configured correctly, its suggested that you use the [administrator invite](https://pulsebot.gg/invite) for Pulse. Pulse has a built-in text-channel-locking configuration that you can set up to restrict access. Please note that Pulse needs to be disconnected from your server before using the administrator invite for the changes to take affect.

 - <u><b>Read Messages/View Channels</b></u> -> To receive commands in a text channel.
 - <u><b>Send messages</b></u> -> To send messages.
 - <u><b>Manage Messages</b></u> -> Embed suppression, user-command management.
 - <u><b>Embed Links</b></u> -> Formatted embed messages.
 - <u><b>Read Message History</b></u> -> Required for ❌ self-message deletions to work.
 - <u><b>Add Reactions</b></u> -> Required for ❌ self-message deletions to work.
 - <u><b>Connect</b></u> -> To connect to the voice channel.
 - <u><b>Speak</b></u> -> To play music in the channels.

<br>

## Why should I donate, and how?

 - Since Pulse is a free-to-use bot, donations are not required. That does not mean that the bot is free to host for the creator of the project. Your donation will help keep Pulse alive. If you would like to contribute, you can donate [here](https://pulsebot.gg/donate).

<br>

## What do I get for donating?

 - At the moment, you get no additional features or perks for donating to the Pulse Project, as the project itself was founded on the basis that a free, feature-packed bot should be available to everyone. We suggest you purchase a premium membership instead.

<br>

## How do I change the channel Pulse messages in?

 - Pulse uses a unique channel tracking system. When you issue a command to pulse, it outputs it’s response to that channel. If the command is successful, it’s output channel will be set to the current channel. If the command fails, it will continue outputting to the previous channel if it exists. If no previous channel exists anymore, it will output to the new channel.
<br>
<br>
If you wish to restrict Pulse to one channel only, you can set the channel using the configuration command. If the configured output channel gets deletes, that configuration value will be reset.

<br>

## How are permissions determined?

 - Pulse has a few basic commands that all users have access to like play, queue, and lyrics. Commands that modify the playing track or queue can be restricted by enabling the usage of the DJ role. If you wish to allow others to modify the bot’s configuration, they must have the MANAGE_SERVER permission.

<br>

## How many votes are needed in order to skip a track?

Currently, the bot requires the majority 2/3 of the members in the channel besides any bots, to pass a skip.
<br.
<br>
If someone leaves the channel, their vote gets removed from the active vote to skip. Additionally, when someone leaves the current channel, the votes to skip gets re-evaluated, and skips to the next track automatically if there are enough votes.

<br>

## What types of limits does the bot have?

 - None at the moment, but in the future, any limitations put in place are there to provide the best experience for other servers. Other than that, if the bot can do it reasonably, it will.
<br>
<br>
 If you believe any of the limitations are too strict or that there is a missing limitation impairing your experience because of others, feel free to Contact us.

<br>

## Can Pulse play 24/7?

 - YES!
<br>
<br>
By default this comes disabled in order to save on resources. This means that Pulse will pause when it's alone and after 15 minuites of inactivity, being paused, or being alone, Pulse will automatically disconnect from the server. However, 24/7 can easily be enabled via the config command! This will disable any disconnect timers, and disable Pulse from pausing when it's alone. For more information, run: `?config 247`

<br>
<br>

## I'm setting the bot's command prefix, but it isn't working!

 - Try a different command!
<br>
<br>
The configuration command's prefix is the only command where the prefix won't change (besides the help command, the prefix for help is both the default prefix, and custom prefix). This was done for scenarios where one Pulse prefix is set to another Pulse bot's prefix, resulting in both bots being locked together. This will ruin the user experience, especially when trying to reset one bot's prefix, but instead will set both, in addition to other commands.

<br>

# Couldn't find what you're looking for?

 - Feel free to [contact](https://pulsebot.gg/contact) us.
