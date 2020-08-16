## Graph Learning 

GL or GRL (Graph Representation Learning) as it is more popularly known is a broad area with a lot of algorithms throught which we can learn basically anything from graph data.

It includes classical algorithms like PageRank and Cliques to extract information from graphs, or more recently, machine learning based methods.

This doc has ML based methods primarily for now, will add others later.

Prereqs: 
- ML basics (look at the respective topic.md file in Slack-Stock-DAG)
- DL (more than basics would be required usually)
- PyTorch (there's disadvantages with Tensorflow here)
- Graphs (the math and implementations)
- Databases on a case-to-case basis

Currently the best structured course on GRL is [CS224W](http://web.stanford.edu/class/cs224w/), and while it's pretty good, most of the learning is throught talks, blogs, papers and code. It's easy to find the important ones through a google search, so I'm focusing only on the topics.

- Look at [this paper](https://arxiv.org/abs/2005.03675#:~:text=Graph%20representation%20learning%20methods%20have,unsupervised%20representations%20of%20relational%20structure) for an overview of all GRL methods.

- Node2Vec is a classic algorithms that has been used in a number of places. It uses Random Walks to beautifully encode graphs into fixed-nodes.

- GNNs or GCNs (Graph Convolutional Networks) are a CNN-like architecture that works when the computational graph isn't fixed-sized and when we have graph like data instead of tensors.

- The most important libraries in Graph Learning are [Deep Graph Library](dgl.ai) and [PyTorch Geometric](https://github.com/rusty1s/pytorch_geometric) and they are very much in active developments right now.

- [Video lectures from CS224W](http://snap.stanford.edu/class/cs224w-videos-2019/) are a very good place for all theoretical understanding. After that all recent architectures are available on the PyTorch Geometric Docs.

- Read up papers, blogs, talks in conferences and code in these libraries!
