### SignalMaster
 Essentially a signal listener that will connect two people on a peer-to-peer connection. Will exist on a central server and exclusively make/remove P2P connections.

### WebRTC
 The environment that our chatrooms will exist in. The user will connect to this service, which will make a call to signalmaster, opening a connection to the central server, and then wait for anyone to try to connect to that. If that all goes well, a peer-to-peer connection will be established.
