---
title: The Survey System
weight: 20
---

If the Survey system is enabled for your server, you'll need to supply reasons with your kicks, bans, promotions, demotions, and timeouts. This list is configurable by your server's admins.

![Example of Survey](/img/examples/surveyr-example.png)

<!--more-->

{{< toc >}}

## Convenience note

If you're using Sangou's commands to ban, the reason provided after the ban command will be used as the ban reason in the survey log.

Sangou will also pull reasons from the audit log as well if you ban through methods other than the bot.

This applies to kicks and timeouts as well.

## Managing surveys

- `survey`/`s`<br>
Posts the 5 most recent surveys.

- `reason`/`r` [case ID or "l"]{-case ID for "l"} [reason]<br>
Records a reason for a survey.

- `censor`/`c` [case ID or "l"]{-case ID for "l"}<br>
Censors a survey's name.

- `dump`/`d` [case ID or "l"]{-case ID for "l"}<br>
Dumps user IDs for surveys. Users can use this too.

- `repost`/`re` [cateID or "l"]<br>
Reposts up to a certain case ID.<br>
Use if you accidentally deleted a case.

