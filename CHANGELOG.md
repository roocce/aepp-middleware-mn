#CHANGELOG
##aeternity blockchain explorer


###Version 1.3.11
    Mobile-first design layout (for _small devices_)
    
    Added folder for styles organization

    Changed address page structure

    Swapped shortened address and full address display positions

    Added main menu hiding

    Added style classes to spans and transferred them to parent td

    Added transaction type classes and transferred them to the parent tr

    Added fonts


###Version 1.3.10
    Hyperlinked .chain, Formatted name_fee.

    You can now search .chain from the dashboard

###Version 1.3.9
    Improvements to time display

    Consolidation of checks for strings and hyperlinks of blocks and tags

###Version 1.3.8
    Handling autotables better, hyperlinking things.

    Also fixed a few data links to make it more resiliant and a few quality
    of life changes.

###Version 1.3.7
    Alternating colors on auto tables

###Version 1.3.6
    Table reformating, number formatting
    
    Typo correction

###Version 1.3.5
    Added support for mh_ and changed the table formater.

###Version 1.3.3
    Added block number support in the main search bar.

###Version 1.3.2
    Added handling for an inconsistent state
    
    ... this state made calculating data from blocks unable to continue.
    Removed all transactions related to that block and requeued it for the
    system to be able to catch up.

###Version 1.3.1
    Made the search bar accept enter to redirect.

###Version 1.3.0
    Fixed bug that showed error message before redirect happened

    Fixed a skip bug in the transaction details

###Version 1.2.2
    Added interactions for the search bar, still missing enter support.
    
    Added decoding of the payload in transactions details.

###Version 1.2.1
    Added decoding of payload text in transaction list for addresses

###Version 1.2.0
    Replaced all references to a full qualified domain to itself

    Explorer minor bug fixes

###Version 1.1.0
    Hotfix: removed a localhost reference in txadd.js

###Version 1.0.8
    Explorer update

###Version 1.0.7
    Updated Readme file

###Version 1.0.6
    Added count for range of transactions

###Version 1.0.5
    Added error handling for JSON parsing

###Version 1.0.4
    Added key and cert to config

###Version 1.0.3
    Added more endpoints and features

###Version 1.0.2
    Added dependencies and ignore file.

###Version 1.0.1
    Updated readme
    
    Added section for known differences and clarification on how to install dependencies.

###Version 1.0.0
    Initial commit

