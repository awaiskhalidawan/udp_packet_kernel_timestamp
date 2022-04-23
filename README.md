# Timestamping received UDP packets in Kernel

This example shows how a received udp packet can be timestamped in the kernel. Timestamping the received udp packet helps to accurately find the parameters in different protocols such as TWAMP (Two way active measurement protocol).

To compile the code:
g++ main.cpp -o test

To test the code:
1. ./test -s (Start as a server to listen for packets.)
2. ./test -r (Start as a client to send the packets.)
