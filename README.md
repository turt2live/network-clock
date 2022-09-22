# network-clock
A simple electron app to host a network-controlled countdown clock. Electron because it's easy, not because it's right.

Intended for usage as a presenter timer at a conference for cheap - works great on a Raspberry Pi.

## Install / usage

You will need Node 18 or higher to run this.

```bash
git clone https://github.com/turt2live/network-clock.git
cd network-clock
npm install
npm run start
```

Then access the clock over the network. Note that the connection is NOT secured, so anyone on the network can change the time.

## Usage with BitFocus Companion

Set up a generic HTTP connection for your host machine, then set up the following macros:

TBD
