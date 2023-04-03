# MTRN2P
My Traceroute optimized for SIP Simulation.
Sintax example:   
mtr --udp -s 1500 -o "SDRL    NBAW    JMXI" 8.8.8.8 -P 5060 -bz

NET2PHONE TRACE ROUTE                                                                    Current time: 2023-04-03T16:48:55-0300 GMT
               Simulating a UDP PCM audio channel with 1500 bit payload, from: IDTBR82 (172.22.166.236), to: 8.8.8.8.

                                                                      PACKETS                   LATENCY                   JITTER
    HOST TRACKING                                              Snt Drop   Rcv Loss%      Last  Best   Avg  Wrst     Jttr Javg Jmax Jint
 1. AS???    IDTBR82.mshome.net (172.22.160.1)                 107    1   106  0.9%       0.5   0.2   0.7   7.5      0.1  0.4  7.2  5.6
 2. AS???    10.14.6.2 (10.14.6.2)                             107    1   106  0.9%       1.9   1.6   5.3  41.0      1.4  6.1 38.3 63.9
 3. (waiting for reply)

