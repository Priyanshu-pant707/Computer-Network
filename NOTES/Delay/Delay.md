# Delay

- The delay of network specifies how long it takes a bit of data to travel across the network from one node to another.



### There are Four different types of Delay:

1. `Transmission Delay` : Time take to push the packet bit onto the communication link. It depends on length of packet and bandwidth of network.

```
Transmission Delay(T) = Length of packet(L)/Bandwidth(B)

example

L=1kb and  B=1kbps

so converting the data to bps;

L = 1 kb = 1024 bs
B = 1 kbps = 1000 bps


T=1024/1000=1.024

```


2. `Propagation Delay ` : Time for a bit reach its destination , Time taken by first bit to travel from source to destination.

```
Propagation delay (T)= Distance(D)/ Transmission speed(V)

default spee= 2.1 * 10**8 m/s


Example :

d= 2.1 km
v=2.1 * 10**8

T=2.1 * 10**3/2.1 * 10**8

answer is 10 to the power -5 millisecond.

```


3. `Queueing Delay`  : Time the packet spend in routing queueing . The queueing delay depends upon number of packet earlier in the queue.


4. `Processing Delay` : A packet consist of head and data field, the head consist address of source and destination . The time require to examine header is called processing delay.



## To Find the total delay we can use : 
```
totalDelay = TotalTransmissionDelay + TotalPropagationDelay +                TotalQueueingDelay + TotalProcessingDelay
```
