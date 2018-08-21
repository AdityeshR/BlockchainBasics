# Blockchain_Basics
Project is about learning the basics of Blockchain and its fundamentals such as mining, proof of work, connecting nodes, transaction etc.
Postman will help in accessing the Blockchain methods manually.<br />
	GET - http://127.0.0.1:5001/mine_block<br />
	GET - http://127.0.0.1:5001/get_chain<br />
	GET - http://127.0.0.1:5001/is_valid<br />
	POST - http://127.0.0.1:5001/connect_node<br />
		Body (Raw) - { "nodes": ["http://xx.xx.xx.xxx:5001",.... ] } //Replace the IP address of the node to be added in local network. Each node should run this this to keep the list of nodes updated.<br />
	POST - http://127.0.0.1:5001/add_transaction<br />
		Body (Raw) - { "sender":"","receiver":"","amount":10 } // Mention the Sender, Receiver and amount.This transaction will appear in Blockchain only if a new Block is mined. There is a fixed x'tion charge along with the x'tion.<br />

Note:Remember this is about basics of Blockchain.It is a working instance of a Blockchain in its preliminary form over a network.Consensus algorithm finds the longest chain in network and replaces it on the node. 
     Current stage does not have Smart Contract in place as well no validation of account.

//Download the exe and run on a Windows system.
