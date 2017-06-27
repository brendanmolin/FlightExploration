# Flight Exploration - 
Network Analysis Practice

Most network data are not as tidy as one finds in an igraph vignette. Networks in real life are wide, scattered, full of chance encounters, varying in strength and scope, and it can be extremely difficult to parse through the noise to identify the valueable relationships.

Take the well-known data on the co-occurence of characters within the novel Les Miserables.  This dataset has the luxury of the author, Victor Hugo, having parsed through millions of lives and trillions of connections between said lives involved in the French Revolution, picking 70 or so characters (fictional and quasi real) to represent this great conflict.  That is quite a lot of pre-processing!  Monsieur Hugo had the unique position of pre-determining the messages he wanted to convey and summoning a cast of characters to play out that role.  As data scientists, we have to work in reverse - we get ALL the characters, and then find the message.  This requires parsing through the noise to allow messages to come into focus.

This exploratory analysis is intended to practice cutting a large, tangled network to paint a broad picture of airline transit in the United States.  We'll break down the network into various communities based on the strength of connections between the nodes, then look more deeply into the connections within each community.  Finally, we'll look at some summary statistics of the communities themselves.  This should give us a general sense of the airline network in the United States. 

You may view my published summary here:
<http://rpubs.com/bmolin/USAFlightExploration>