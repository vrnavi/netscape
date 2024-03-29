---
title: The Tossing System
weight: 10
---

Tossing is a very advanced system in which tossed users speak privately with the Staff members of a server.

<!--more-->

{{< toc >}}

## Tossing overview

"Tossing" is the act of stripping a user of all of their roles, and replacing it with one single role that forbids speaking in the entire server, save for one channel that gets created on-the-fly for one on one discussions between the offending user and the Staff team.

It's useful for defusing tense situations and removing problematic users from situations fast.

In addition, Sangou can archive these sessions for you, whether on Google Drive or saved as a file on the platform itself.

To use this, the `staffchannel` setting and `toss` category in the server configuration must be filled out. `drivefolder` is optional, but enables archives to be automatically uploaded to a Google Drive folder. Please ask in the support server if you'd like to use a `drivefolder`.

## Tossing rundown

Here is a brief rundown from the OneShot Discord Server's Staff Handbook:

> When tossing a user (or, users), it is heavily advised to do so away from the public chats, to prevent any boiling over. Think of the "ooh, someone's in trouble!" thing, that's rather hard to quell. It's recommended to perform tosses in `#old-factory`.
> 
> To perform a toss, you'll need to either mention a user, or use their IDs. IDs are much preferred, and you'll need Developer Mode enabled for them. `Settings > Advanced > Developer Mode`. You can also use usernames, if that is easier for you.
> 
> Once you have their name, mention, or ID, simply use `pls toss USER`. If you are tossing multiple users, separate them with spaces, such as `pls toss USER1 USER2`.
>
> When tossing a user, `@Sangou` will create a new "session" for you, in `🚷 Lower Tower`, with a max of four sessions open at a time. The tossed user (or users) will be pinged, and given a timer to respond. When they do, or when the timer expires, you will be pinged.
>
> Depending on the user, you'll take your next courses of action in the session channel. If they are uncooperative, they likely aren't a good fit for the server. Use your best judgement here.
> 
> If you need to add more users to the session, simply use `pls toss` again within the session channel, and they will be added.
> 
> When you're done (and you haven't kicked or banned them), you can use `pls untoss USER` to untoss the user and return them to the public chats. If you run `pls untoss` by itself, it will untoss every user.
> 
> Once you've done that, you'll need to close the channel. To do this, simply run `pls close`, and the channel will be closed and deleted for you.
> 
>In the event that the bot complains about nobody being in the toss cache, run `pls archive USER`, and delete the channel manually.

## Tossing commands

- `toss` [target] {target 2, target 3...}<br>
Tosses a target, creating a new session.<br>
If performed in a Toss channel, will add the user(s) to the session.

- `untoss` {target/"all"} {target 2, target 3...}<br>
Untosses a target, restoring their roles and removing them from the session.

- `close`<br>
Archives a session and removes the channel for you.

- `sessions`/`tossed`<br>
{{< hint type="warning" title="Keep in mind">}}
If this command shows users in a session, yet users are not tossed, this is a known bug.<br>
Please contact renavi, or the person hosting the bot.<br>
To mitigate this issue, always use the untoss command.
{{< /hint >}}
Shows the currently active sessions, and the users in them.
