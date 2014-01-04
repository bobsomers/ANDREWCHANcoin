ANDREWCHANcoin
================================

Website URL here.

Copyright (c) 2009-2013 Bitcoin Developers  
Copyright (c) 2011-2013 Litecoin Developers  
Copyright (c) 2014 ANDREWCHANcoin Developers  

What is ANDREWCHANcoin?
----------------

ANDREWCHANcoin is a joke cryptocoin based on Litecoin, which uses scrypt as a
proof-of-work algorithm.

Basic coin stats:
 * Scrypt based.
 * New blocks every 2 minutes.
 * Difficulty adjustment every 720 blocks (1 day).
 * Initial mining subsidy is 1,000,000 coins.
 * Subsidy halves every 106,500 blocks (~5 months).
 * Total of ~214,000,000,000 coins in ~4 years.
 * Largest transaction amount is 10,000,000,000 coins, for now.

More info about binary downloads once we have them here.

License
-------

ANDREWCHANcoin is released under the terms of the MIT license. See `COPYING`
for more information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

Testing
-------

Unit tests for the core code are in `src/test/`. To compile and run them:

    cd src; make -f makefile.unix test

Unit tests for the GUI code are in `src/qt/test/`. To compile and run them:

    qmake BITCOIN_QT_TEST=1 -o Makefile.test bitcoin-qt.pro
    make -f Makefile.test
    ./litecoin-qt_test

