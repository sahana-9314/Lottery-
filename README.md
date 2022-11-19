# Lottery-
Lottery contract using Blockchain 
In the project, the two main entities involved are buyers,who buy the lottery tickets and a manager who is the organizer.
The buyers have to pay some amount of ether to buy a ticket and once the transaction is completed,they are given the ticket(s). Among all the buyers' addresses,one random address is generated with the help of keccak256 function and with the help of mod(%) operator. The total ether is then transacted to the winner,s address. The manager is the one who is able to generate the winner.
