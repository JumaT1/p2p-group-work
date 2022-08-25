# group2-peer-to-peer
Peer to Peer network implementation

## How it works

### Step 1 First clone the project

```sh
git clone https://github.com/code-lords/group2-peer-to-peer.git
```
The go the project directory

```sh
cd group2-peer-to-peer
```
### Step 2 Running the project
To start a peer you run the following command
```sh
python peer.py  <peerName> <port>
```
This creates a peer and you can interact with it via the available commands
i.e 
- addfile to add a file
- getfile to get from the network
- search to search and see which peer has the file
- exit to exit the network