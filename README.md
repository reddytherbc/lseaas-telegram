# LSEAAS Telegram Group

The LSEAAS Telegram group is administered using [Miss Rose](https://missrose.org/). This document covers the key features used.

## Connecting to chats

To avoid sending commands into the group and creating spam while others are talking, configuration commands can be set via a separate channel.

To do this, send `/connect <group-id>` to Miss Rose on a private chat. The `group-id` for the LSEAAS Telegram group is `-602644603`. If the connection is successful, any commands sent to Miss Rose on the private chat will be applied to the group.

## Set language

Language was set to British English using: `/setlang en-gb`.

## Admin logging

To keep a record of admin actions, the `LSEAAS Admin Log` channel was set up.

## Reports

The option for users to report unwelcome members was enabled using `/reports on`.

## Welcome message

```
/setwelcome Welcome {username} to {chatname}! Please briefly introduce yourself to the group and share with us what you're keen to get out of the LSEAAS community. Happy to have you and look forward to seeing you soon!

[LSEAAS Website](buttonurl://www.lsesingapore.org)
```

## Human verification

To verify that new users are human, require humans to unmute themselves by clicking a button.

`/welcomemute on`

## Cleaning unnecessary messages

Remove Telegram service messages such as `So and so joined the group via invite link` using `/cleanservice on`.

Remove old welcome messages using `/cleanwelcome on`.

## Blacklist words and phrases

List of vulgarities added using `/addblacklist "<vulgarity>"`.

List of swear words taken from [bannedwordlist.com](http://www.bannedwordlist.com/).

## Antiflood measures

Following commands used to mute users who send more than 10 messages in a row for 10 minutes:
- `/setflood 10`
- `/setfloodmode tmute 10m`

## Block spammers

The `Shieldy` bot was added to provide a CAPTCHA service that prevents spammy bots from joining.