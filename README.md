##IS30320: Network Report (in Markdown format)

In this report I will explain all the network terms which are used as part of network analysis, and included in my own network graph. I will additionally describe the process on how I created the graph.

Several types of networks exist. A *full network* displays the entire map of connections in a network. A *partial network* displays a particular subgroup of connections. An *ego-centric network* displays the connections that revolve around a single person. A *topic-centric network* displays the connections that revolve around a single topic. 

*Nodes*, otherwise known as vertices, may represent various things in a network graph. They typically represent individuals, but can also represent larger groups such as organisations, institutions, etc.  They can also represent content, such as webpages or keyword tags. Additionally, they can represent physical or virtual locations or events. Nodes often relate strongly to the core building blocks of social media platforms. In my network graph, nodes are represented by circular points which show individuals.

*Edges*, otherwise known as links, represent the connection between two nodes. Edges can represent different types of relationships between nodes, such as friendship, proximity, collaborations, or any shared attributes between nodes. A connection exists whenever there is any form of relationship or connection between two nodes. Two types of edges exist, directed and undirected edges. Direct edges have a clear origin and destination. They show a one-sided relationship between nodes. They are represented on a graph by a line connecting the source node and recipient node, along with an arrow pointing towards the recipient node.  Indirect edges show a mutual relationship where there is no origin or destination. They are represented on a graph by a line connecting two nodes with no arrows. My network graph contains undirected edges between nodes which represents friendships.  

*Influence* in social networks is measured through the range of the network a person has, their ability to evoke engagement, and to drive measurable outcomes.

Two kinds of social capital can also be seen in social networks, *bonding* and *bridging capital*. *Bonding capital* is when people socialize with others who are similar to them in terms of demographics and/or interests. *Bridging* is when people socialize with others who aren’t similar to them in terms of demographics and/or interests. 

*Degree centrality* in a network is the count of a number of edges a node has to other nodes. If the network has direct edges, degrees are measured in terms of in-degrees and out-degrees. *In-degrees* are the number of incoming edges to a particular node. *Out-degrees* are the number of outgoing edges from a particular node. My graph doesn’t display in-degrees or out-degrees as it represents a network with indirect edges. 

*Betweenness centrality* in a network is a measurement of the distance between people or vertices in a network. The distance between two people who aren’t friends is measured by the smallest number of friend of a friend’s separating them. The shortest path separating people is known as a ‘geodesic distance’ (Hansen et al., 2011, pp.40). 

*Closeness centrality* in a network is a measurement of the average distance between a vertex and every other vertex in a network. A low closeness centrality means that a person is directly connected or very closely connected to others in a network. A high closeness centrality means that a person has many personal connections who which they must travel through to reach many other people in the network (Hansen et al., 2011, pp.41). 

*Eigenvector centrality* in a network allows for some connections to have more value than others. A person with few connections can have a high eigenvector centrality if the few connections they have very were well connected themselves (Hansen et al., 2011, pp. 41).

The network graph I created is a partial directed social network graph of a Facebook personal friend network. To create the graph, I logged into Facebook and searched for an application called Netvizz. Netvizz captures data of a personal network for visualisation. Once this data was downloaded from Netvizz, I opened it in software known as Gephi. Gephi is used to visualize social networks. I firstly ran the ‘forced atlas 2’ layout to visually separate groups. Then I ran the ‘modularity partition’ in order to identify and colorize social groups.  The degree range was also filtered to limit the amount of nodes shown in order to make the graph more visible. The end result is that my graph displays 3 different colored social groups with bonding connections, and also it displays the bridging connections that link all three groups together. I created the graph in consideration of Schneiderman's ‘Netvizz Nirvana' standard of graph clarity.

***

#####Bibliography:
Hansen, D. L., Shneiderman, B., & Smith, M. A. (2011). *Analyzing social media networks with NodeXL: Insights from a connected world*. Amsterdam: Elsevier, Morgan Kaufmann.
