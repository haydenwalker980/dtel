# Customer Support Guide
Welcome to the Customer Support guide. This guide contains info about the commands that you (presuming that you're CS) can use. **Your actions are recorded in #bot-log.**

If you have any questions about commands that are **not** mentioned here, you may ask about it in a staff channel on DTel's HQ. Staff commands should **only** be used in either the staff channel or in direct messaging with the bot.

## How do I become Customer Support?
The **only way** to join the CS team is to fill out the [application form](https://dtel.typeform.com/to/wHjMpX). Your application will put into the pool, but will only be looked at once a spot opens. The maximum amount of team members is currently **the number closest to (server count / 100)** (excluding supervisor or higher). It may take **weeks or months ~~or years~~** for your application to be read. **Asking a staff member to read your application will result in an AUTOMATIC DENIAL.** During your wait, you should stay in the DTel HQ. Failure to remain in the server until your application is read will result in an automatic denial.

## Assigning a number
Usually, servers can get a number using `>wizard`. You may need to run `>assign <Channel_ID> <Number>` in these occasions:

* Moving a number from a channel to another (unless the number is VIP, in which case use >reassign.) Run **after** de-assigning the original one. Remember to compensate for any paid months. If the number has expired, use >addcredit to charge any outstanding balance first (make sure to specify that it's a negative amount of credits.)
* Getting more then 3 numbers (must get approval from boss.)
* `0800` (supervisor approval required.) (Note: we're no longer selling them)

## Deassigning a number
`>deassign <Number>`. Use this command only if:

* The number is not callable;
* The number has been mistakenly assigned;
* The owner requests for removal of their number (make sure to use `>permcheck <caller's discord ID>`);
* The users of this number abuse the system; (blacklist their server/members first)
* The owner of the number wants it moved to another channel (make sure you have the channel ID they want it moved to, and also transfer the months they paid for by refunding the credits (# months x 500))

## Info about things
We currently have info commands for:

* users (`>uinfo <user id/mention>`)
* numbers (`>ninfo <number>`)
* calls (`>cinfo <call id, see #bot-log>`)
* and mailbox messages (`>minfo <number/channel of the mailbox> <message id, run >mailbox to get it>`).

## Adding credits
Please ask a boss. The command is >addcredit, but you ***must*** consult a boss.

## Dealing with troll calls (or any kind of abuse)
*Sometimes* people can be annoying and just trying to have fun. That is the case with troll calls.
**These** are the cases of **what are** and **what are NOT** troll calls:

* People calling and talking about something irrelevant to DTel - Troll Call
* A person calls 611 but does not understand what it is/does - NOT a Troll Call, inform them then hang up
* Caller begins to say impolite/vulgar things to or about you - Troll Call
* Caller who is reporting a troller - NOT a Troll Call

If a troll call occurs, warn the user and give them a strike (`>strike <user id> <reason>`.) The user will automatically be blacklisted after 3 strikes. If the bot failed to blacklist the user (if the bot doesn't say "They have been blacklisted." in the embed footer in response to your 3rd strike), or if the offense is severe enough you may directly blacklist the user (`>blacklist <user id>`.)

(You can get the user ID from #bot-logs (it's at the end of the line):
![User ID](http://i.imgur.com/ntxEwAA.png) or by enabling Discord's Developer Mode and right clicking/tapping on the user's profile and selecting "Copy ID".)

If you want to **un-blacklist** someone, run the blacklist command *again* with the same user ID.

For a quick reference to help you decide what is and what isn't trolling, you may refer to the Wikipedia article on [Internet trolling](https://en.wikipedia.org/wiki/Internet_troll).

## Backdooring
Sometimes you may need extra proof for a troll call report. Or maybe you need to join a server to help a user out. In any case, you can use `>backdoor <number/channel id>` to get an invite.

## Broadcasting
If you're trying to help someone out or want to tell them something, and you can't/don't want to call someone + they dont have a mailbox set up, you can use `>broadcast <numbe/channel id> <message>` to send them a message. Only use this for CS purposes.

## Busy-ness
We use a system of a user being "busy" when they use certain commands to avoid conflicts. Usually a user becomes un-busy when the command is "done". However, sometimes a user gets stuck in the busy state. You can run `>unbusy <user id/mention>` to free them up. If commands still don't work for them, contact a boss.
