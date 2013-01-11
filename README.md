mtgox-php-tradebot
==================

Tradebot daemon for MtGox Written in PHP

Disclaimer
==========

This software does not come with any gaurantees at all, use at your own risk.

I have not made any money using this script due to the constant fine tuning done but it should work in theory.
If you have any complaints or criticism about the bot please contribute them in a positive manner by actually 
contributing to this project. If you would like to show your appreciation just send me a donation 
(remember I've lost money during the fine tuning of this bot).


Getting Started
===============

Dependencies
* PEAR Package System_Daemon
* PHP5 CLI
* MtGox Account

To get started simply get your API access key and secret from the mtgox website and enter them 
in the `config.json` file where it says key and secret under the mtgox object.

once you've configured your bot go to your terminal and drop into the bot directory and run the follwing command

`$ php daemon.php`

This will spawn the daemon install a service and start writing to a log file. After running this for the first time 
you will now be able to stop and start the service as any other system daemon by using the following commands.

`$ service mtgox start`
to start
and
`$ service mtgox stop`
to stop

WARNING: you may get a ton of PEAR warnings just disregard these. 

Donations
=========

Gimme your monies!

bitcoin address: 1J4muBrfJrkr7tjeDuPTwBGgaG5wASWtYn

Thank you.
