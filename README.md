# IMT
This repo contains the project files for "IMT"
## What we know so far 
Mission: Develop a simple smartphone application
Extended Mission: Develop an appplication that reads/sniffs ACK packetes, pings, traceroutes.
All to aproximate a targets location/distance from user device.
### Objectives:
- [ ] Get base app upp and running
- [x] Setup git
- [ ] Upload prodject base files to truly initiate main repo
- [x] Decide on a base IDE (others could be used in personal prefrence)
- [ ] Go to Mars
- [ ] Start developing the application
- [ ] Decide on a layout and the elements that are needed
- [ ] Write a rapport
- [ ] Flowchart
- [x] Realize that this is in no particular order

### Decided
IDE: Android Studio
Language: Java
Android Version: 10

### Main Mission
Build an app that sniffs tcp packets from RCA-messages.
App extracts IPv4-adress (¿IPv6?) and uses it to perform one or serveral of;
Ping, Traceroute, Arp-Scan, Nma.
Figure out if the application can, with some accuracy show where the reciever is located.
Se if the node(cell tower) that the reciever is connected to can be deciphered in som way,
thus giving some information about the general area that the recievier is located.
With the collected information, can the app with some simple math give show a general area
where the reciever is located. Combine a plethora of software utilities to give away a somewhat
precise location.
