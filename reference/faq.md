---
description: >-
  Some of the most frequently asked questions regarding the bot, as well as the
  answers
---

# Frequently Asked

##  Verification System <a id="verification"></a>

### What is it? <a id="verification-what"></a>

The verification system requires that you meet certain requirements before being allowed to send links or attachments to the global chat.

### Why is it? <a id="verification-why"></a>

The verification system exists in order to prevent new users from joining and posting NSFW links and/or images in the global chat.

### How do I verify? <a id="verification-how"></a>

You will become verified upon reaching the 100 message milestone in global chat.

{% hint style="warning" %}
Reaching 100 messages by spamming will result in your account being blocked from using the global chat
{% endhint %}

## End User License Agreement \(EULA\) <a id="eula"></a>

### What is it? <a id="eula-what"></a>

The [EULA](../legal/eula.md) is a legal agreement between you and the bot developer stating that you won't violate Discord's [Terms of Service](https://discordapp.com/terms) \(ToS\) through global chat. If you do, it will be a breach of a legal document, and you can be punished by the full extent of the law.

### Why is it? <a id="eula-why"></a>

The [EULA](../legal/eula.md) exists to ensure the safety of the bot. The global chat feature sends your messages to every other connected channel, so if you send a [not-safe-for-work](https://en.wikipedia.org/wiki/nsfw) \(NSFW\) link/image, the bot will send it to channels that most likely aren't marked as NSFW. This is a violation of Discord's [ToS](https://discordapp.com/terms), and if a user reports the bot's message, Discord staff might shut down the bot account.

### How do I accept? <a id="eula-how"></a>

The easiest way to accept the [EULA ](../legal/eula.md)is through the `$-eula` command. This command outputs an invite link; following the link will take you directly to the [EULA ](../legal/eula.md)channel on the bot's support server. Even if you're already in the server, clicking on the link will take you to the correct channel. From there, its as simple as reading the agreement, then adding a check mark reaction.

![](../.gitbook/assets/eula.png)

## Global Ban List <a id="ban-list"></a>

### What is it? <a id="ban-list-what"></a>

The Global Ban List is a list of user IDs who have been banned in accordance with HaileyBot's [Global Ban Policy](gbp.md).

### How do I implement it? <a id="ban-list-how"></a>

You can set up HaileyBot to automatically warn you when a member joining your server has violated the Global Ban Policy, as well as warning you when an existing member in your server has been added to the Global Ban List.

For a more direct approach, you can use the `$-ban` command to sync the Global Ban List with your server, which will prevent all globally banned users from being able to join your server.

![](../.gitbook/assets/warn-ban.png)

## Other Common Questions <a id="other"></a>

### What is Server TPS? <a id="tps"></a>

TPS stands for "ticks per second". This value represents how many operations per second the host computer is able to handle without any server-side latency. Most latency experienced while using HaileyBot is either network latency, or a result of [Discord's rate limits](https://discordapp.com/developers/docs/topics/rate-limits).

### Why don't custom emotes work in Global Chat? <a id="emotes"></a>

**TL;DR:** They actually do.

On Discord, bot accounts have the same emoji abilities as a Discord Nitro user. A bot can use custom emotes across different servers, outside of the server the emote originates from. However, just like a Discord Nitro user, a bot can't use a custom emote from a server the bot isn't in. Global Emotes work perfectly fine in Global Chat, as long as HaileyBot is in the emote's server. Unfortunately, there is no way around this limitation.

### Why is the Global Chat English only? <a id="english-only"></a>

There are people from all over the world connected to the Global Chat, so guidelines needed to be put in place in order to keep it true to is original purpose of providing a place to meet and connect with new people. English is the most common language in the world \([source](https://rebrand.ly/languages-by-country)\), and therefore is understood by more people than any other language. The Global Chat is for having conversations, which aren't possible if we don't understand each other.

