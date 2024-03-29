This is the "Stratum2" (S2) Design Document, a system design building on the "Stratum V2 Protocol Specification"  
(+) Extension Components.  

It can translate "Stratum" plain unencrypted clear text json to S2 encrypted binary connection network.  

Also do own transaction selection, if configured as such, and go solo if needed or preferred.   

***    

![alt text](/assets/S2_Component_Cluster_transp_8.png "Components Identification")  

Component Clusters shown is reused fully in waterfall of incoming message / outgoing message flow.

To the degree that the S2Proxy itself is used for creating a S2Pool.

![alt text](/assets/S2_plus_accounting_transp_4.png "Proxy Accounting Pool")

Accounting added uses the raw traffic from Datastore that is filtered to records.  

> ***  

> Composition of the above standalone Components will be able result in below diagram example :    

> ***  

![alt text](/assets/S2_Proxy_proxy_coinbase_3.png "Proxy Proxy to Pool")  

> ***  

> Mining-Devices has a local S2Proxy that can connect to a remote S2Proxy before the aggregated hashrate collects in "S2Pool Accounting".  

> ***  

> S2Proxy Dashboard will be able see all shares submitted to common S2Pool.  

> ***  

> When S2Proxy meet Target Difficulty it will broadcast to Network via the connected Template Provider,  
also signal S2Pool that in turn reach all connected S2Proxy => Template Provider for broadcast.  

> ***  

> The S2Pool Component Cluster has a Coinbase Component that S2Proxy can use with it's connected Template Provider, to at anytime, be able go solo.  

> ***  

Components above will further need be deconstructed, to all have its own diagram and UML representation.   


Contact           :  
stratum2dd@protonmail.com

We are following the "Stratum V2 Protocol Specification" :  
https://github.com/stratum-mining/sv2-spec  
++ massage and addons.  

***  

![alt text](/assets/S2_Proxy_Multiplexer.png "S2Proxy Multiplexer")  
