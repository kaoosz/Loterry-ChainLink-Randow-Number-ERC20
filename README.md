
Ethereum Daap
used Solidity,Truffle,React js,JavaScript,React Bootstrap,Html5m,css,IPFS
and some Truffle tests.

Openzzeplin ERC20,Chainlink Oracle Randow Number

summary

This is a project that uses chain link oracle to 100% safely bring a random number
when all tickets are sold, he calls this "Chain Link Oracle" contract and brings that number.
After 300 seconds, you can claim your reward.
You get an ERC20 coin as a reward..
When the winner asks for his reward automatically after the system resets and is ready for the next lottery

..

This part that connect, you need to wait 2 to 3 seconds to load,
it needs to call the blockchain and query to bring up the information.
You can buy as many Tickets as you want.
When all tickets are purchased, the contract automatically calls the Chain link contract pays 0.1 LINK token as a fee which is requested by Chain link for providing a secure form of "Random Number".

https://user-images.githubusercontent.com/39299613/175029491-01db5ef3-ca86-42cc-9a64-24775f334c56.mp4

When all tickets are sold, you can see the Claim tab change and show the winning wallet.
To claim your reward, you must wait 300 seconds, why so long?
You get an ERC20 coin as a reward
Each blockchain has a certain time to process Transactions
Rinkeby network 2 to 5 minutes
Kovan 2 minutes

Note: if you are going to test this code, first look at the response time in the Chain link documentation, each network has different times to bring a "Random Number"

When you claim your reward automatically, it will reset the tickets and be ready for a new lottery…




https://user-images.githubusercontent.com/39299613/175038455-78076a28-41d4-4c87-91d0-f2302cf9ccd9.mp4

