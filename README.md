chesi, a SHA-256 crypto-currency, is based on Bitcoin version 0.8, with super random blocks.

The following specifications are implemented:
	- Each normal block has 1024 coins
	- 30 seconds block time
	- Difficulty retargets every 60 blocks (approximately 30 mins). 
	- mining payout will be halved every 3 months (259,200 blocks)
	- Expected total mined coins will be 675,925,530 coins (not including 1 coin/block maintenance)
	- 4 confirmations for transaction (2 mins)
	- 70 confirmations for minted blocks
	- The minimum payout will be maintained at 1 coin/block.
	
	- Random bonus blocks are:
		- 1/10 chance (about every 5 mins) for one 2048-coin block (2^11 coins) 
		- 1/100 chance (about every hour) for one 8096-coin block (2^13 coins) 
		- 1/10000 chance (about every 3.5 days) for one 65536-coin block (2^16 coins) 

Ports:
- Connection: 13434
- RPC: 13435

To encourage early adopters, the first week after launched will be bonus week:
	- First two days: 5X
	- Next 2 days: 3X
	- Next 3 days: 2X

The official website is: asiccoin.info (under construction).


License
-------

chesi is released under the terms of the MIT license. See `COPYING` for more

