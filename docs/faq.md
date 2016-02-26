List of Frequently Asked Questions.

## Can I do an on-site election after the online election?

Yes, in fact it is rather common. Once the online election has finished, you export the census to check that, when someone tries to vote in the on-site election, this person hasn't previously voted in the online election, thus preventing double votes.

## How can I allow people without email or mobile phones to vote?

You can setup a physical stand supervised by an election administrator, to create a voting booth where the administrator or someone supervised by an administrator will use temporary emails  to let the voter use it.

This method can only be valid if the chosen authentication method is via email. If the authentication method is SMS, you can create a new election for these users and merge the results of both elections manually.

## I haven't received the SMS with the Authentication Code

Please check that:

* The correct mobile phone number is on the census.

* The user with that mobile phone number is enabled on the census.

* If you are using a hosted installation, you must have properly configured the sms section in config.yml in agora-dev-box.

## I haven't received the email with the Authentication Code

Please check that:

* The correct email is on the census.

* The user with that email is enabled on the census.

* If you are using a hosted installation, you must have properly configured the email section in config.yml in agora-dev-box. Specifically, apart from configuring the mail server, ensure that the 'backend' variable is 'email' and not 'console'.

## What support do you provide?

nVotes provides second level support. We provide support to election administrators. If you have doubts or you have found a problem or bug in the system, you can send a ticket to support on [this link](ttps://nvotes.com/help/support/) or send an email to [support@nvotes.com](support@nvotes.com) and we'll answer you as soon as possible.
