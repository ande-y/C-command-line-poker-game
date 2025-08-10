This is a texas holdem poker game implemented with only basic C++ concepts.
The game is contained within a single 700 line file. 
The game can be run by compiling then running the executable. G++ is preferred over Clang.

What's included:
  - poker hand/combination detection logic
  - bots with rudimentary decision making (to call, raise, fold, & go all in)
  - logic to deduct/calculate chips distributed to each player after a round
  - horrible code

Notable issues:
  - no option to do a "check"
  - some bots will continuously fold when there's few players remaining
  - 700 line file.
