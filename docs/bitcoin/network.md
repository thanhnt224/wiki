# Bitcoin Network The network of computers running the bitcoin program.

## What is the Bitcoin Network?

The Bitcoin Network is made up of everyone running the bitcoin software (better known as “bitcoin clients”).

![Bitcoin is a network people runnning the same computer program.](images/network/png/01-software_network.png)

Bitcoin is a network people runnning the same computer program.

## What does the network do?

People (well, bitcoin clients) on the network **talk to each other**.

![Very sociable.](images/network/png/02-software_network_talking.png)

Very sociable.

And by “talk to each other” I mean _pass on information_ about what’s going on in other parts of the network. This is done by sending each other _messages_.

For example, a message could be **information about a new _transaction_**.

![Sharing information about new transactions.](images/network/png/03-software_network_talking_transaction.png)

Sharing information about new transactions.

This sharing of information (e.g. transactions) is what allows the everyone on the network to keep up-to-date, which is pretty important if you want to run a digital currency on the Internet.

![Eventually everyone knows about the new transaction. Good network.](images/network/png/04-software_network_talking_transaction_consensus.png)

Eventually everyone knows about the new transaction. Good network.

The Bitcoin Network is described as a “[peer-to-peer](https://en.wikipedia.org/wiki/Peer-to-peer) network”, because:

1.  Everyone is connected to each other, so it’s a network.
2.  Everyone on the network is equal, so we are peers.

## Who makes up the network?

As mentioned, **anyone with an active Internet connection and running a bitcoin client**.

Seriously, _anyone can join the bitcoin network_. All you need is an internet connection and a [bitcoin client](https://bitcoin.org/en/download), which is a piece of software like any other.

And once you’re up and running you’ll be referred to as a node on the bitcoin network.

![Node - a slightly more concise way of saying an individual running a bitcoin client and relaying information around the network.](images/network/png/05-nodes_network.png)

Node - a slightly more concise way of saying “an individual running a bitcoin client and relaying information around the network”.

For more information on nodes, check out [nodes](nodes).

## How can I join the network?

That’s the spirit.

All you need to do is download (and run) a [bitcoin client](https://bitcoin.org/en/download).

When you run the client it will connect to other nodes and start downloading a full copy of the blockchain (the file that contains all the verified transactions). After that, your client will start receiving transactions from other nodes and relaying them around the network.

Congratulations, you are now a node on the bitcoin network.

You may need to [edit some settings in your router to allow other nodes to connect to you](https://bitcoin.org/en/full-node#gui-peer-info), but this is just a minor configuration. By downloading and running a bitcoin client you are 95% of the way to becoming an active node on the bitcoin network.

By [Greg Walker](/about), 27 February 2015