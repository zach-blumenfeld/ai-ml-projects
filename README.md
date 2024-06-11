# Hi, I'm Zach 👋
I'm passionate about AI, machine learning, and data science. I thrive on learning and sharing new technologies and am always seeking innovative ways to make an impact with them.

Below are some of my recent technical project highlights. As background context, I'm a technical marketer for Neo4j (since Aug 2021), specializing in GenAI/RAG integration as well as graph data science and machine learning. As such, my technical projects are a mix of workflows geared towards GenAI/RAG app development (sample apps for Q&A, search, recommendations, etc.) and DS/ML (analytics, building models, etc.). I am very flexible about (and enjoy) working both ends of this spectrum!

## Technical Project Highlights

### GenAI & RAG Apps
- __Demo app for GraphRAG patterns ([code](https://github.com/neo4j-product-examples/graphrag-examples), [webinar recording](https://www.youtube.com/watch?v=OuyTENdRcNs)):__ This is a sample app and presentation I developed to explore various GraphRAG patterns and their benefits. The multi-page app demonstrates RAG for Q&A and email generation use cases. Most patterns involve a combination of embeddings, vector index, and graph operations. The app leverages OpenAI, Streamlit, Langchain, and Neo4j.

- __Short demo videos:__
  - [Build a dynamic search application with ai-agents and Neo4j](https://www.youtube.com/watch?v=wKJRvK6u5f8)
  - [Why Neo4j for RAG?](https://www.youtube.com/watch?v=7kbHw7dniUc)

- __Hands-on GenAI workshop ([notebook](https://github.com/neo4j-product-examples/genai-workshop/blob/main/genai-workshop.ipynb), [deck](https://github.com/neo4j-product-examples/genai-workshop/blob/main/workshop-slides.pdf)):__ This is a long-form (~2.5 hour) workshop I developed for Neo4j to run globally at in-person events with prospects and customers. It takes participants through a series of steps to understand how to perform graph-powered RAG using an email generation bot as an example. It leverages LangChain for creating retrievers and chains.


### Machine Learning & Data Science Workflows
- __Graph Data Science for fraud detection ([blog](https://neo4j.com/developer-blog/exploring-fraud-detection-neo4j-graph-data-science-summary/), [code](https://github.com/neo4j-product-examples/demo-fraud-detection-with-p2p)):__ This is an analytical/ML workflow I developed to demonstrate the benefits of graphs for entity resolution, risk scoring, and ML models in the context of fraud use cases. While it doesn't leverage embeddings, it is a multi-part series including in-depth blogs and coded examples that should give you a good idea of how I put together larger projects for technical audiences.

- __Graph Data Science for recommendation systems ([blog](https://towardsdatascience.com/exploring-practical-recommendation-engines-in-neo4j-ff09fe767782), [code](https://github.com/neo4j-product-examples/ds-recommendation-use-cases/tree/main/news-recommendation-mind/mind-large-collab-filtering)):__ This workflow explores how to use graphs, and specifically graph embeddings, to power and enhance recommendations. Graph embeddings encode graph structures, such as user preferences expressed in interconnected transactions, making them very interesting and applicable to recommendation use cases.

- __Graph machine learning overview [(blog)](https://towardsdatascience.com/graph-machine-learning-an-overview-c996e53fab90):__ This does not include any code, but can give you a good idea of how I communicate and explain complex ML topics in writing. The blog also touches on embedding, which is pretty core to graph ML.

- __Graph embeddings for improving model performance ([notebook](https://github.com/neo4j-product-examples/graph-machine-learning-examples/blob/main/inductive-node-classifiaction-ml-integration/example.ipynb)):__  This workflow demonstrates how to feed Neo4j graph embeddings into downstream classification models to improve accuracy.  I use PyTorch to construct MLP neural nets for the downstream models. I train the models on different graph and text embeddings, evaluate, and compare accuracy.

- __Graph Database sampling for training GNNs ([notebook](https://github.com/neo4j-product-examples/graph-machine-learning-examples/blob/main/gnns-with-neo4j/db-sampling-for-gnn-training/pyg-gnn.ipynb)):__ This notebook demonstrates how to sample large graphs to make computationally intensive Graph Neural Networks (GNNs) more efficient and feasible to train.  I use Neo4j's random walks with restarts (RWR) algorithm to export a sample graph then demonstrate training a convolutional graph neural network (CGN) using Pytorch Geometric (PyG). Taking representative samples of graphs is not trivial due to their arbitrary interconnected nature. It requires special algorithms, hence demonstrating Neo4j's RWR here.




### Other Examples
I own the [Neo4j Product Examples GitHub Org](https://github.com/neo4j-product-examples) which includes additional GenAI & DS/ML examples that may be of interest.