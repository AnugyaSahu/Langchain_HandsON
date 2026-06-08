#### Langchain_HandsON
Theory + Practical , A to Z

#### Langchain 

Framework to build LLm-powered applications by chianing together components

1. Core Modules 

A. LLMs and Chat Models
B. Prompt Templates
C. Chains - Sequence of functions
D. Agents - ReAct Framework, autonomous
E. Tools - Database, Websearch

2. Data Connection Modules

A. Document loaders - PDFs, URLs, Notion
B. Text Splitters - Chunk Documents into manageable parts for indexing and retrieval 
C. Embeddings - Vector representations
D. Vector Stores - FAISS, PINECONE, CHROMA
E. Retrievers - fetch relevant docs from a vector store based on a query

3. Memory 

A. BufferMemory - stores all history
B. SummaryMemory
C. ConversationBufferMemory

4. Integrations 

A. Clouds
B. LLMs
C. Databases - Postgres, MongoDB, MySQL
D. VectorStores
E. Notebooks - Jupyter, Streamlit, LangServe

5. LangServe and LangSmith

A. LangServe - Deploys Langchain apps as a REST API (Fast API based)
B. LangSmith - Observability and debugging platform for Langchain apps - Metrics, token usage, traces, evaluation

6. Evaluation & Debugging

A. Tools to test and evaluate LLM Pipelines

LCEL - Expression language for clean, declarative pipeline building 