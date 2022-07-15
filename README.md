# Distributed-Hash-table-project
# Chord (Node.js and gRPC)
This project is an implementation of a p2p distributed hash table using the Chord algorithm by Ion Stoica, Robert Morris, David Karger, Kaashoek, and Hari Balakrishnan. It uses Node.js to implement the nodes, and gRPC as the method of inter-node communiation.

# The client script:

runs a crawler that walks the Chord successor chain to build an in-memory representaiton of the state of the overlay network serves a simple web UI that visualizes the overlay network In the future, the project will implement a "Stack Exchange Computer Science User Service" on top of this DHT, complete with a simple web app to demonstrate transparency and real-work use of a DHT. It will also enhance the admin pain to add controls to dynamically add and remove nodes from the Chord.
