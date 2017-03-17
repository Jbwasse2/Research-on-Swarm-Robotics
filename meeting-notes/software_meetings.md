2017/03/17
==========

Updates:
-   part printed! Does it work??
    -   almost! Hole for post is too small. After drilling, we need a 14/64ths
        drill bit to make it work.
-   EngrIT recommends we register devices with IllinoisNet_Guest
    -   I doubt this will work but we can try, just need to get MAC addresses
-   Electromagnet stuff?
-   Haskell graphs - action items
    -   Generate graphs (all connected, none connected, various labelling options)
    -   Match subgraph (efficiency?)

What I will work on over break:
-   connecting ESP8266s
-   Maude implementation of graph rewriting

Next hardware meeting:
-   electromagnets
-   iterating on attachment design

Next software meeting:
-   report progress on generating graphs in Haskell

2017/03/08
==========

Li and Justin presented consensus. I am uploading their slides with these notes.

Some interesting questions that came up (just my opinions, other people can add
 more questions to this) - AN
 
-   The algorithm presented by Li today was just one of many different consensus
    protocols. Sometimes you want to agree on a shared state, not just a value,
    leading to protocols like blockchain. What exactly should our agents come to
    consensus on? Each pair of connected agents comes to consensus on their
    shared neighbors?
-   What kind of filters or minimal recognizers can we use to recognize binary
    and ternary rules?
-   Do we need to worry about the fact that ROS is asynchronous (an expected
    message may never come?)

2017/03/01
==========

Decided to hold hardware meetings 11am on Mondays. In the lab.

Software is staying 2pm on Wed, in 4124.

Everyone is on the self-assembly github now.

Went through "basic-haskell" assignment, getting familiar with recursion, list
operations, data types. Next week, Li and Justin will present on consensus
algorithms, the types of modelling choices made in consensus algorithms, and
what is relevant for our project.
