What?
=====

NoneToken is a ERC-20 Token with a totalSupply of 0.
It was mainly created because of an issue with ShapeShift: https://github.com/walleth/walleth/issues/94#issuecomment-398040161

Why?
====

In the ShapeShift case mentioned above this token can be useful to state somewhere that you don't want to select a coin.
But it can also be useful for testing.
It might even discover some division by zero bugs when developers think: ```totalSupply``` will never be 0 as this makes no sense - even though it is possible.

And last but not least this token is interesting from a philosophical point of view as this token is most rare and most evenly/fairly distributed ;-)

Deployment
==========

 * Rinkeby: 0x6475A7FA6Ed2D5180F0e0a07c2d951D12C0EDB91
 * Main: 0x643B6870beabee941B9260a0A878bcF4A61Fb0f1
 * Ropsten: 0xFD5a69A1309595FF5121553F52C8A5B2B1B31031
