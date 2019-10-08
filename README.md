Project Message router
If one node wants to compete with another node, then avalanche routing is not an efficient approach.
Especially if the network is extensive - this leads to a large number of useless data transfer operations.

An alternative is a way to send messages from node to node until it reaches its destination!

The function is looking for a way to reach a specific host. But instead of returning the entire route,
she returns only the next step. The next socket itself, using its current information on the network, will decide
where to send the message further.
