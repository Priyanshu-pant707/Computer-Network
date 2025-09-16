# Switching in Computer Networks

- Switching in computer networks is the technique of forwarding data (packets/frames) from the source to the destination through intermediate devices (like switches, routers, or exchanges).

- It decides which path the data should take in a network to reach the correct device.

##  Types of Switching

- There are three main types of switching in computer networks:

1. ***Circuit Switching***

A `dedicated communication` path is established between sender and receiver for the entire duration of the session.

- Example: Traditional telephone networks.

✅ Advantages: Reliable, constant data rate, no interference.

❌ Disadvantages: Wastes bandwidth if the channel is idle.

---

2. ***Packet Switching***

- Data is broken into packets and each packet is routed independently across the network.

- Packets may take different paths and are reassembled at the destination.

- Example: The Internet (IP networks).

✅ Advantages: Efficient use of bandwidth, supports many users.

❌ Disadvantages: Packets may face delay, congestion, or arrive out of order.

---

3. ***Message Switching*** (older concept, less used now)

- Entire messages (not small packets) are transmitted from node to node.

- Each node stores the whole message, checks it, and forwards it ("store and forward").

✅ Advantages: No need for a dedicated path.

❌ Disadvantages: Very slow, requires large storage at intermediate nodes.

---

✅ In short:
Switching is how data moves from one device to another in a network, using circuit switching, packet switching, or message switching depending on the system.