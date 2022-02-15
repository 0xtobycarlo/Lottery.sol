# lottery.sol

Concept for a lottery system in Solidity. Could be tweaked to host a system for redistributing profits after an NFT project/airdrop/whitelist.

1 ETH must be spent to enter the lottery, and the admin cannot participate to appreciate fairness. 

Minimum 3 'players' required for the contract to start the process.

The winner of the lottery is selected at random: winner = players[random() % players.length];    |    
and recieves the remaining balance: winner.transfer(getBalance());

Could be implemented for users/addresses who participated in an NFT whitelist/airdrop to incentivise participation in return for larger social scope.
