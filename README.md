# dweet.io + Node-RED

A simple example of [dweet.io.](http://dweet.io/) with Node-RED.

## Visit [dweet.io/play](https://dweet.io/play) and create "dweets"

<p align="center">
<img src="https://github.com/phyunsj/dweet.io-node-red/blob/master/dtweet.io.post.thing.png" width="600px"/>
</p>

<p align="center">
<img src="https://github.com/phyunsj/dweet.io-node-red/blob/master/dtweet.io.get.thing.png" width="600px"/>
</p>

## Assign URL in Node-RED function node

<p align="center">
<img src="https://github.com/phyunsj/dweet.io-node-red/blob/master/node-red-function-node-dweet-url.png" width="600px"/>
</p>

- `msg.url='https://dweet.io:443/dweet/for/thermostat';` from dweet.io/play
- `msg.url='https://dweet.io:443/get/latest/dweet/for/thermostat';` from dweet.io/play

## Related Posts

- [HAPI](https://github.com/jheising/HAPI) : The Humanized API
