# Customer Support Guide
Welcome to the Customer Support guide. Commands that support members have access to are listed in this guidebook. **Your actions are recorded in #bot-log.**

If you have any questions about commands that are **not** referenced here, you may ask about it in a staff channel on DTel's HQ. Staff commands should **only** be used in either the staff channel or in direct messaging with the bot.

## How do I become a Customer Support?
The **only way** to become part of the Customer Support team is to fill out an application, located [here](https://discordtel.typeform.com/to/cR3ovo). Your application will put into the pool, but will only be looked at once a spot opens. The maximum amount of team members is currently **the integer closest to (server count / 100)** (Excluding Manager or higher). It may take **weeks or months ~~or years~~** for your application to be read. **Asking a staff member to read your application will result in an AUTOMATIC DENIAL.** During your wait, you should stay in DiscordTel HQ: Failure to remain in the server until your application being read will result in an automatic denial.

## Assigning a number
Usually, servers can get a number using `>wizard`. You may need to run `>assign <Channel_ID> <Number>` in these occasions:

* Moving a number from a channel to another (Run **after** de-assigning the original one. Remember to compensate for paid monthly charge. If the number itself is expired, ask a boss to run eval to charge any outstanding balance first.)
* Getting a second number for a server (If the server is big enough, boss approval required)
* `0800` (Boss approval required)

## Deassigning a number
`>deassign <Number>`. Use this command only if:

* The number is not callable;
* The number is mistakenly assigned;
* The owner requests for removal of their number;
* The users of this number abuse the system; (Blacklist their server/members first)
* The owner of the number wants it moved to another channel (Make sure you have the channel ID they want it moved to, and also transfer the months they paid for by refunding them credits, which is \# months x500).

## Number info
`>ninfo <Number>`

## Adding credits
Please ask a boss.

## Dealing with troll calls (Same applies to any kind of abuse)
*Sometimes* people can be annoying and just try to have fun. That is the case with troll calls.
**These** are the cases of **what are** and **what are NOT** troll calls:

* People calling, talking about something irrelevant to DiscordTel - Troll Call
* A person calls 611 but does not understand what it does - NOT a Troll Call
* Caller begins to say impolite/vulgar things to or about you - Troll Call
* Caller who is reporting a troller - NOT a Troll Call

If a troll call occurs, warn the user and give them a strike, in a format like this: `>strike <user id> <reason>`. The user will automatically be blacklisted after 3 strikes. If the bot failed to blacklist the user (The bot should tell you "They have been blacklisted." in the embed footer in response to your 3rd strike), or if the offense is relatively severe, you may directly blacklist the user by `>blacklist <user_id>`.

You can get the User ID from #bot-logs (it's at the end of the line):
![User ID](http://i.imgur.com/ntxEwAA.png)

If you want to **un-blacklist** someone, run the blacklist command *again* with the same user ID.

For a quick reference to decide what is trolling and what is not trolling, you may refer to this Wikipedia article on [Internet trolling](https://en.wikipedia.org/wiki/Internet_troll).
