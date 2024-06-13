# Raft Consensus
> Based on https://raft.github.io/raft.pdf 

Raft implementation using python

## How to run

- Install requirements:
- `pip install -r requirements.txt`
- Run the server:
- `make server-local`
- Run other servers:
- `make server-to PORT={port} SERVER_PORT={host}`
- Run client:
- `make client-local SERVER_PORT={port}`
