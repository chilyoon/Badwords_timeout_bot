# timeout
"timeout" is a discord bot to timeout (an) annoying user(s) of a certain channel.


## How To Use
In any text channel, type in:

```$timeout @user1 @user2 ...```

to timeout all the listed users. This message is automatically and immediately replaced with ```[VOTE HERE] Timeout @user1 @user2 ...``` message to assure the anonymity and start the vote.

Every member in the text channel can participate in the vote by leaving reaction on this message.

## Plan for 0.1.1 Update
* Send additional message if timeout was applied successfully.
* "timeout" should not be able to timeout itself.

## Version 0.1.0
* Implementation of basic features.
* Minimum number of vote to initiate timeout is fixed to 3.
* Timeout duration is fixed to 60 seconds.
