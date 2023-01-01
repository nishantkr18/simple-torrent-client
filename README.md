## Simple torrent client

A jupyter notebook explaining the basic steps required to make a torrent client application.

What the [notebook](simple_torrent_client.ipynb) does till now:

1. Reads info from a torrent file.
2. Connects to http trackers to fetch peers.
3. Connects to a peer and sends initial handshake message.


## Extras:

BitTorrent uses a "distributed sloppy hash table" (DHT) for storing peer contact information for "trackerless" torrents.

How does DHT handle churn? 
DHT explaination: https://www.bittorrent.org/beps/bep_0005.html

