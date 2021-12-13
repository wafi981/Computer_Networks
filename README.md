# Computer_Networks
Programs for stimulating and implementing stop and wait protocol for noisy channel,  selective repeat sliding window protocol.


Stop-and-wait ARQ, also referred to as alternating bit protocol, is a method in telecommunications to send information between two connected devices. It ensures that information is not lost due to dropped packets and that packets are received in the correct order.
Simplex Stop – and – Wait protocol for noisy channel is data link layer protocol for data communications with error control and flow control mechanisms. It is popularly known as Stop – and –Wait Automatic Repeat Request (Stop – and –Wait ARQ) protocol. It adds error control facilities to Stop – and – Wait protocol.

This protocol takes into account the facts that the receiver has a finite processing speed and that frames may get corrupted while transmission. If data frames arrive at the receiver’s end at a rate which is greater than its rate of processing, frames can be dropped out. 



Why Selective Repeat Protocol?
The go-back-n protocol works well if errors are less, but if the line is poor it wastes a lot of bandwidth on retransmitted frames. An alternative strategy, the selective repeat protocol, is to allow the receiver to accept and buffer the frames following a damaged or lost one.
Selective Repeat attempts to retransmit only those packets that are actually lost (due to errors).
