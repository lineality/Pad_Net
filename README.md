# Pad_Net
## One Time Pad Based Network Protocol For Sirius Security

## Outline:

This will be more memory-use, or memory storage, intensive.

The goal is for every 'user' profile to have a separate (account of) one-time pads.

AAA batteries

A. You cannot simply 'gain access'
B. You cannot 'decrypt' traffic

A Padnet would be a kind a white-list network in the sense that devices on the network are not automatically 'open' to anything on 'the internet.'

adding a layer to the standard, time tested, TCPIP protocol

1. (optional?) network traffic must have a network pad
2. the recipient must have a peer-pad



#### block of chunk of packet size has various issues:
- efficiency (larger chunk is less efficient)
- security of 'meta-data' (smaller chunk is less opaque)


Possibly a way to audit network traffic by 'user.'

Maybe a 'layer' in the router on top of TCPIP?

iot?

resource thin pad net?


Pure vs. Practical
In the pure version of padnet, each device has a pre-exchanged set of one time pads. 
But in a more pragmatic version, there may be some (though less secure way) of having synchronized key generation between devices on the network. 
