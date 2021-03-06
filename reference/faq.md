---
description: >-
  Some of the most frequently asked questions regarding the bot, as well as the
  answers
---

# Frequently Asked

## Global Chat <a id="global-chat"></a>

### What is it? <a id="global-chat-what"></a>

The global chat is a channel connected to multiple different servers - any messages sent to a connected channel are forwarded through the bot to all the other connected channels. This can open up your server to a brand new world of possibilities in socializing and building an active community. Global Chat a fantastic way to meet and and talk to new people who you otherwise never would have met. 

### How do I connect? <a id="global-chat-how"></a>

To connect a channel to HaileyBot's Global Chat, simply type `$-link global` in the channel you want to link. The only requirement is that the server has at least 20 members \(bots don't count\). This requirement exists to prevent people from linking channels that will rarely or never get used, because it sucks up the bot's resources and makes it slower for everyone else.

### How do I disconnect? <a id="global-chat-how"></a>

If you no longer wish for your channel to be a part of the global chat, you can disconnect it simply by typing `$-unlink` in the linked channel.

## Verification System <a id="verification"></a>

### What is it? <a id="verification-what"></a>

The verification system requires that you meet certain requirements before being allowed to send links or attachments to the global chat.

### Why is it? <a id="verification-why"></a>

The verification system exists in order to prevent new users from joining and posting NSFW links and/or images in the global chat.

### How do I verify? <a id="verification-how"></a>

You will become verified upon reaching the 100 message milestone in global chat.

{% hint style="warning" %}
**Note:** Reaching 100 messages by spamming will result in your account being blocked from using the global chat
{% endhint %}

## Private Links

### What are they? <a id="private-links-what"></a>

Similar to the Global Chat, this feature allows you to connect multiple channels across different servers. The difference is that you aren't stuck using HaileyBot's main Global Chat; you can create your own cross-server communities, making them the way you want them to be. Private links use webhooks so that the messages that get sent to different servers look identical to the original.

### How do I set it up? <a id="private-links-how"></a>

To create a private link, first choose a name for the group of channels you're going to link. Then, type `$-link private name` in every channel you want to connect. For example, if you're linking the general chat of 2 or more servers, use `$-link private general`. If its the staff chat, you can do `$-link private staff`.

{% hint style="warning" %}
**Note:** To prevent naming conflicts, private link categories are individual for each user. This means that to successfully link 2 channels, the `$-link` command has to be issued by the _same_ user in both channels. If two separate users try linking to a category, it creates two separate categories, and the channels won't be linked to each other.
{% endhint %}

## Other Common Questions <a id="other"></a>

### What is Server TPS? <a id="tps"></a>

TPS stands for "ticks per second". This value represents how many operations per second the host computer is able to handle without any server-side latency. Most latency experienced while using HaileyBot is either network latency, or a result of [Discord's rate limits](https://discordapp.com/developers/docs/topics/rate-limits).

### Why don't custom emotes work in Global Chat? <a id="emotes"></a>

**TL;DR:** They actually do.

On Discord, bot accounts have the same emoji abilities as a Discord Nitro user. A bot can use custom emotes across different servers, outside of the server the emote originates from. However, just like a Discord Nitro user, a bot can't use a custom emote from a server the bot isn't in. Global Emotes work perfectly fine in Global Chat, as long as HaileyBot is in the emote's server. Unfortunately, there is no way around this limitation.

### Why is the Global Chat English only? <a id="english-only"></a>

There are people from all over the world connected to the Global Chat, so guidelines needed to be put in place in order to keep it true to is original purpose of providing a place to meet and connect with new people. English is the most common language in the world \([source](https://rebrand.ly/languages-by-country)\), and therefore is understood by more people than any other language. The Global Chat is for having conversations, which aren't possible if we don't understand each other.

