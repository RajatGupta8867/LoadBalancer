# LoadBalancer
LoadBalancer is the primary load balancing configuration object that specifies the virtual IP address on which client traffic is received, as well as other details such as the load balancing method to be use, protocol, etc.

The Round Robin is an algorithm that distributes the load equally among the servers in the server pool, doing a simple rotation. Just performing a check if it is alive before forwarding the request to a certain server.

This method is commonly used when requests need to be split among several servers with similar capabilities in terms of processing and resources.
