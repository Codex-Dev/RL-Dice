[![github](https://img.shields.io/github/license/timothymtorres/RL-Dice.svg)](https://choosealicense.com/licenses/mit/)
[![tags](https://img.shields.io/github/tag/timothymtorres/RL-dice.svg?label=version)](https://github.com/timothymtorres/RL-Dice/tags)
[![commit](https://img.shields.io/github/last-commit/timothymtorres/rl-dice.svg)](https://github.com/timothymtorres/RL-Dice/commits/master)
[![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/timothymtorres/rl-dice.svg)](http://isitmaintained.com/project/timothymtorres/rl-dice "Average time to resolve an issue")
[![GitHub issues](https://img.shields.io/github/issues/timothymtorres/rl-dice.svg)](https://github.com/timothymtorres/RL-Dice/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/timothymtorres/rl-dice.svg)](https://github.com/timothymtorres/RL-Dice/pulls)

RL-Dice
=======

A robust module to roll and manipulate roguelike dice.  This has also been included in [rotLove](https://github.com/paulofmandown/rotLove) roguelike toolkit which I highly recommend if you plan on making a roguelike.

Consult the [online documentation](https://timothymtorres.github.io/RL-Dice) for the API and usage examples.  

The dice module provides the following:

* Dice notation strings - used to create or roll dice instances
* Dice number/faces - can be increased or decreased
* Dice bonus - can be increased or decreased
* Dice rerolls - can reroll and filter out via highest or lowest results 
* Dice sets - can return multiple results
* Dice pluralism - enable bonus or rerolls to individual dice or to all dice 
* Dice caching - reuses dice tables for faster performance

Unit Testing
------------

A LuaUnit test is setup in the tests folder.  There are 15 different tests that check that the metamethods, new instances, dice cache, and notation are all functioning.  To run these tests simply navigate to the test folder on your shell, and execute the command `lua dice_test.lua -v` to see the results.  
