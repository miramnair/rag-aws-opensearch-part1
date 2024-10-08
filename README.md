**Please note that this is a two-part series, and this is Part 1 of the implementation.**

Deploy an enterprise grade Q&A, Serverless RAG application using Amazon Bedrock agents, Amazon Bedrock KnowledgeBase and OpenSearch Serverless and Amazon Titan Text Embeddings V1. Knowledge Bases for Amazon Bedrock is a fully managed capability that helps you implement the entire RAG workflow from ingestion to retrieval and prompt augmentation without having to build custom integrations to data sources and manage data flows.

Details : https://medium.com/@miramnair/develop-and-deploy-a-serverless-rag-solution-with-amazon-bedrock-agents-knowledge-base-and-ef8a1818bc1e


<img width="1260" alt="image" src="https://github.com/user-attachments/assets/80e1888d-6d70-4f92-8968-3943135e437e">




What will we achieve in Part 1?

We successfully created an Amazon OpenSearch Serverless collection and a vector index within that collection. Additionally, we uploaded a sample JSON file into our S3 bucket. Currently, these components exist as separate entities. In Part 2, we will create a Bedrock agent and a knowledge base and integrate them with OpenSearch Serverless.

Link to Part 2 : https://github.com/miramnair/rag-aws-opensearch-part2
