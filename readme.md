# Mr. Arp
## Observe Amazon Dash using ARP packets

Runs on Linux and OS X only because of Node-PCAP's requirements. Node-PCAP allows us to watch ARP (Address Resolution Protocol) packets on the local network, so we can see the Dash request an IP when it is pressed. By recording the MAC addresses of Dash buttons on a private network, we can watch specifically for their requests and tie them to different outputs.

Mr. Arp is a JavaScript implementation of [Ted Benson's baby data hack](https://medium.com/@edwardbenson/how-i-hacked-amazon-s-5-wifi-button-to-track-baby-data-794214b0bdd8).

### Build instructions
`npm install`
`node app.js`

