# Dialing Guide
You can dial a specific number using `>dial <number>`, or a random number from the phonebook using `>rdial`.

## Call commands
* `>pickup`, `>hangup`: I guess I don't need to explain.
* `>hold`: Puts the call on hold. Everything you said after the command will not be relayed over, unless you remove the hold by executing `>hold` again.
* `>transfer <number>`: Transfer the call to another number. This is equivalent to you executing `>hangup` and the otherside executing `>dial <number>`.
