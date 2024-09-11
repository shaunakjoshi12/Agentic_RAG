# Agentic_RAG
This is a Q and A system which answers general questions asked by a user. The system is developed using a multi-step agent which uses Thought-> Action -> Observation sequence iteratively. The biggest challenge in any RAG system is the answer relevance of the query and the answer generated, given that everything is perfect say the chunking algorithm, the embedding model, the vector store however the query is in an interrogative language and the content is in affirmative language.

This is exactly where the need of an agent comes in which can transform the query to affirmative form from interrogative one. Here multi-step agent has been chosen as it is a sort of error correcting agent which employs a chain of thought reasoning.

The agent is ReAct and here are several LLMs which were tried for the agent.
1) Meta-Llama-3-8B-Instruct
2) CohereForAI/c4ai-command-r-plus
3) HuggingFaceH4/zephyr-7b-beta

