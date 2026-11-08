# DSC 180A Methodology Assignment 4
## About Me
- Name: Shawn Cheng
- Email: shc068@ucsd.edu

## Section Info
- Section: Epistemic Engines: Turning Raw Data into Living Knowledge Bases for AI Agents (D28)
- Mentor: Ryan Lingo

## Questions
**1. What is the most interesting topic covered in your domain this quarter?**

The most interesting topic covered in my domain this quarter is retrieval augmented generation (RAG). I had been tasked with implementing a RAG system for our project, and before I didn't know how RAG worked. But now that I have built it end-to-end, it's a lot less intimidating than I though, and it was very interesting to see the math and how RAG actually works.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

A potential investigation I would like to pursue for my Quarter 2 Project is to see what can we can build off of RAG and existing graph database systems for our own knowledge graph system. The whole premise of our project is to see how knowledge graphs can benefit LLM inference and reasoning, so we want to construct the knowledge graph in the best way possible for the LLM to interact with it. I'd be interesting in exploring technologies like Microsoft's GraphRAG and Neo4j to see how existing graph databases work, and what lessons we can take in building our own knowledge graph system.

**3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**

A potential change I'd like to make to the approach taken in our current Quarter 1 Project is how we evaluate the LLM. Currently, we are evaluating a standard LLM with no external knowledge access whatsoever to when it can access a database with RAG, but I feel that an LLM with RAG will almost always significantly outperform the baseline LLM on knowledge-specific tasks. I'd like to compare the LLM with RAG to an LLM with a different way of accessing the same data, like maybe through a vector database or other NoSQL database.

**4. What other techniques would you be interested in using in your project?**

Other techniques that I would be interested in using in my project include experimenting with NoSQL databases, such as MongoDB or Redis. I would want to use these databases and compare them to RAG to see which knowledge retrieving approach would work better for LLMs. I would also be interesting in using standard graph databases and linking them up to an LLM, and compare how an LLM with a graph database compares to the same LLM but with a more complex graph database structure, such as a graph structure seen in Andrej Karpathy's LLM wiki.
