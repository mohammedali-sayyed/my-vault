
## [[Core Python]]

### Fundamentals

- [ ] **1. Syntax, variables & data types**
  - **Cover:** Syntax basics, variables, int/float/str/bool/None, dynamic typing, arithmetic/comparison/logical operators
  - Difficulty: Beginner | Estimated time: 2 hour(s) | Priority: High | Dates: 2026-10-21 00:00:00 to 2026-10-22 00:00:00
  - **Practice:** Write short scripts demonstrating each core data type and operator
- [ ] **2. Type casting & conversion**
  - **Cover:** Implicit vs explicit casting, int()/float()/str()/bool()/list() conversions, common casting pitfalls
  - Difficulty: Beginner | Estimated time: 1 hour(s) | Priority: High | Dates: 2026-10-21 00:00:00 to 2026-10-22 00:00:00
  - **Practice:** Build a small unit-converter script using explicit type casting

### Control Flow & Functions

- [ ] **3. Conditionals, loops & functions**
  - **Cover:** if/elif/else, for/while, break/continue/pass, def, default/*args/**kwargs, lambda, scope (LEGB rule)
  - Difficulty: Beginner | Estimated time: 2 hour(s) | Priority: High | Dates: 2026-10-21 00:00:00 to 2026-10-22 00:00:00
  - **Practice:** Write a CLI calculator using functions, loops and conditionals

### Data Structures

- [ ] **4. List, tuple, dict, set**
  - **Cover:** Indexing & slicing, mutability, list/dict/set comprehensions, common built-in methods
  - Difficulty: Beginner | Estimated time: 2 hour(s) | Priority: High | Dates: 2026-10-21 00:00:00 to 2026-10-22 00:00:00
  - **Practice:** Solve 10 short exercises manipulating each core data structure

### File Handling

- [ ] **5. Reading & writing files**
  - **Cover:** open() modes (r/w/a/rb), with statement, reading/writing text, CSV and JSON files
  - Difficulty: Beginner | Estimated time: 2 hour(s) | Priority: High | Dates: 2026-10-21 00:00:00 to 2026-10-22 00:00:00
  - **Practice:** Write a script that reads a CSV file, transforms rows, and writes JSON output

### Exception Handling

- [ ] **6. try/except & custom exceptions**
  - **Cover:** try/except/else/finally, catching specific exceptions, raising errors, custom exception classes, basic logging
  - Difficulty: Beginner | Estimated time: 2 hour(s) | Priority: High | Dates: 2026-10-21 00:00:00 to 2026-10-22 00:00:00
  - **Practice:** Add robust error handling and logging to the file-processing script above

### Serialization

- [ ] **7. Pickling & serialization**
  - **Cover:** json module (dumps/loads/dump/load), pickle module (dump/load), pickle security caveats, JSON vs pickle trade-offs
  - Difficulty: Intermediate | Estimated time: 2 hour(s) | Priority: High | Dates: 2026-10-21 00:00:00 to 2026-10-22 00:00:00
  - **Practice:** Serialize a custom Python object with both pickle and JSON and compare the results

## Development

### Advanced Python

- [ ] **8. GIL & memory model**
  - **Cover:** How the GIL works, reference counting, garbage collection
  - Difficulty: Advanced | Estimated time: 3 hour(s) | Priority: High | Dates: 2026-10-21 00:00:00 to 2026-10-22 00:00:00
  - **Practice:** Read CPython docs; run gc module experiments
- [ ] **9. Classes, inheritance, MRO**
  - **Cover:** Multiple inheritance, super(), MRO, mixins
  - Difficulty: Intermediate | Estimated time: 3 hour(s) | Priority: High | Dates: 2026-10-21 00:00:00 to 2026-10-22 00:00:00
  - **Practice:** Build a mixin-based plugin system
- [ ] **10. Dunder / magic methods**
  - **Cover:** __init__, __repr__, __eq__, __hash__, __enter__/__exit__, __call__
  - Difficulty: Intermediate | Estimated time: 2 hour(s) | Priority: High | Dates: 2026-10-21 00:00:00 to 2026-10-22 00:00:00
  - **Practice:** Implement a custom vector class with operator overloading
- [ ] **11. Decorators**
  - **Cover:** Function/class decorators, functools.wraps, parametrized decorators
  - Difficulty: Advanced | Estimated time: 3 hour(s) | Priority: High | Dates: 2026-10-21 00:00:00 to 2026-10-22 00:00:00
  - **Practice:** Build a retry & timing decorator
- [ ] **12. Generators & iterators**
  - **Cover:** yield, yield from, generator expressions, custom iterators
  - Difficulty: Advanced | Estimated time: 3 hour(s) | Priority: High | Dates: 2026-10-21 00:00:00 to 2026-10-22 00:00:00
  - **Practice:** Build a lazy data-pipeline generator
- [ ] **13. Context managers**
  - **Cover:** with statement, contextlib, nested contexts
  - Difficulty: Intermediate | Estimated time: 2 hour(s) | Priority: Medium | Dates: 2026-10-21 00:00:00 to 2026-10-22 00:00:00
  - **Practice:** Write a DB-connection context manager
- [ ] **14. Type hints & error handling**
  - **Cover:** typing module, Generics, Protocol, mypy, custom exceptions, logging
  - Difficulty: Advanced | Estimated time: 3 hour(s) | Priority: High | Dates: 2026-10-21 00:00:00 to 2026-10-22 00:00:00
  - **Practice:** Add full type coverage + structured logging to a module
- [ ] **15. Packaging & testing**
  - **Cover:** venv/poetry, pyproject.toml, pytest, fixtures, mocking, linting
  - Difficulty: Advanced | Estimated time: 3 hour(s) | Priority: High | Dates: 2026-10-21 00:00:00 to 2026-10-22 00:00:00
  - **Practice:** Set up a poetry project with a pytest suite (>80% coverage)

### SQL

- [ ] **16. DDL/DML/DQL + joins**
  - **Cover:** CREATE/ALTER, INSERT/UPDATE/DELETE, INNER/LEFT/RIGHT/FULL/SELF joins
  - Difficulty: Intermediate | Estimated time: 4 hour(s) | Priority: High
  - **Practice:** Design a normalized schema + write 10 multi-table join queries
- [ ] **17. Subqueries, CTEs & window functions**
  - **Cover:** Correlated subqueries, WITH/recursive CTEs, ROW_NUMBER, RANK, LAG/LEAD
  - Difficulty: Advanced | Estimated time: 4 hour(s) | Priority: High
  - **Practice:** Compute running totals & rankings per group
- [ ] **18. Normalization & indexing**
  - **Cover:** 1NF-3NF, B-tree/composite indexes, when NOT to index
  - Difficulty: Advanced | Estimated time: 3 hour(s) | Priority: High
  - **Practice:** Analyze query plans before/after indexing
- [ ] **19. Transactions & optimization**
  - **Cover:** ACID, isolation levels, locking, EXPLAIN/EXPLAIN ANALYZE, N+1 avoidance
  - Difficulty: Advanced | Estimated time: 3 hour(s) | Priority: High
  - **Practice:** Optimize 3 slow queries using EXPLAIN
- [ ] **20. SQL with Python & security**
  - **Cover:** SQLAlchemy/psycopg2, parameterized queries, connection pooling, SQL injection
  - Difficulty: Intermediate | Estimated time: 3 hour(s) | Priority: High | Dates: 2026-10-27 00:00:00
  - **Practice:** Build a small CRUD app using SQLAlchemy ORM

### NoSQL Databases

- [ ] **21. NoSQL vs SQL & data models**
  - **Cover:** CAP theorem, BASE vs ACID, key-value/document/column/graph models
  - Difficulty: Intermediate | Estimated time: 2 hour(s) | Priority: High | Dates: 2026-10-27 00:00:00 to 2026-10-28 00:00:00
  - **Practice:** Map 4 use-cases to 4 different NoSQL models
- [ ] **22. MongoDB**
  - **Cover:** Collections, BSON, CRUD, aggregation pipeline, indexing
  - Difficulty: Intermediate | Estimated time: 3 hour(s) | Priority: High | Dates: 2026-10-27 00:00:00 to 2026-10-28 00:00:00
  - **Practice:** Build CRUD + an aggregation pipeline with pymongo
- [ ] **23. Redis**
  - **Cover:** Strings/hashes/lists/sets, TTL, caching, rate limiting, pub/sub
  - Difficulty: Intermediate | Estimated time: 2 hour(s) | Priority: High | Dates: 2026-10-27 00:00:00 to 2026-10-28 00:00:00
  - **Practice:** Build a caching layer + rate limiter with Redis
- [ ] **24. Graph & column stores (overview)**
  - **Cover:** Neo4j/Cypher basics, wide-column (Cassandra) concepts
  - Difficulty: Advanced | Estimated time: 2 hour(s) | Priority: Medium | Dates: 2026-10-27 00:00:00 to 2026-10-28 00:00:00
  - **Practice:** Write basic Cypher queries for a small graph dataset

### HTTP & CRUD Fundamentals

- [ ] **25. HTTP protocol & methods**
  - **Cover:** Request/response cycle, GET/POST/PUT/PATCH/DELETE, idempotency
  - Difficulty: Beginner | Estimated time: 2 hour(s) | Priority: High
  - **Practice:** Map each CRUD op to the correct HTTP method
- [ ] **26. Status codes & headers**
  - **Cover:** 1xx-5xx codes, Content-Type, Authorization, caching headers
  - Difficulty: Beginner | Estimated time: 2 hour(s) | Priority: High
  - **Practice:** Build a status-code cheat sheet from real API testing
- [ ] **27. REST design & CRUD mapping**
  - **Cover:** Resources, statelessness, pagination, filtering, versioning
  - Difficulty: Intermediate | Estimated time: 2 hour(s) | Priority: High
  - **Practice:** Design a full CRUD API spec for a resource

### FastAPI

- [ ] **28. Setup, routing & Pydantic**
  - **Cover:** Routers, path/query params, BaseModel, validators, response_model
  - Difficulty: Intermediate | Estimated time: 4 hour(s) | Priority: High | Dates: 2026-10-29 00:00:00 to 2026-11-03 00:00:00
  - **Practice:** Scaffold a project with routers + validated schemas
- [ ] **29. Dependency injection & async**
  - **Cover:** Depends(), DB session injection, async def routes, background tasks
  - Difficulty: Advanced | Estimated time: 4 hour(s) | Priority: High | Dates: 2026-10-29 00:00:00 to 2026-11-03 00:00:00
  - **Practice:** Build async CRUD endpoints with injected DB sessions
- [ ] **30. Auth, testing & docs**
  - **Cover:** OAuth2PasswordBearer, JWT auth, TestClient/pytest, OpenAPI docs
  - Difficulty: Advanced | Estimated time: 4 hour(s) | Priority: High | Dates: 2026-10-29 00:00:00 to 2026-11-03 00:00:00
  - **Practice:** Secure endpoints with JWT + write integration tests

### Flask

- [ ] **31. Setup, routing & ORM**
  - **Cover:** App factory, blueprints, Flask-SQLAlchemy, migrations
  - Difficulty: Beginner | Estimated time: 3 hour(s) | Priority: High | Dates: 2026-10-29 00:00:00 to 2026-11-03 00:00:00
  - **Practice:** Structure an app with blueprints + models + migrations
- [ ] **32. REST APIs & auth**
  - **Cover:** Flask-RESTful/Smorest, Flask-Login/JWT-Extended, error handlers
  - Difficulty: Intermediate | Estimated time: 3 hour(s) | Priority: High | Dates: 2026-10-29 00:00:00 to 2026-11-03 00:00:00
  - **Practice:** Build a CRUD REST API with login-protected routes
- [ ] **33. Testing & deployment**
  - **Cover:** pytest test client, Gunicorn/WSGI, Docker
  - Difficulty: Intermediate | Estimated time: 2 hour(s) | Priority: Medium | Dates: 2026-10-29 00:00:00 to 2026-11-03 00:00:00
  - **Practice:** Write route tests + containerize with Gunicorn

### Multiprocessing & Multithreading

- [ ] **34. GIL, threading & synchronization**
  - **Cover:** Thread/Lock/Event, race conditions, deadlocks, thread safety
  - Difficulty: Advanced | Estimated time: 3 hour(s) | Priority: High | Dates: 2026-11-03 00:00:00
  - **Practice:** Reproduce and fix a race condition; build a thread-safe queue
- [ ] **35. Multiprocessing & IPC**
  - **Cover:** Process, Pool, Queue, Pipe, shared memory
  - Difficulty: Advanced | Estimated time: 3 hour(s) | Priority: High | Dates: 2026-11-03 00:00:00
  - **Practice:** Parallelize a CPU-bound task with Pool.map
- [ ] **36. asyncio & concurrent.futures**
  - **Cover:** Event loop, async/await, tasks/gather, ThreadPoolExecutor/ProcessPoolExecutor
  - Difficulty: Advanced | Estimated time: 3 hour(s) | Priority: High | Dates: 2026-11-03 00:00:00
  - **Practice:** Build an async web scraper with asyncio + aiohttp

### MCP (Model Context Protocol)

- [ ] **37. MCP concepts & primitives**
  - **Cover:** Client-server architecture, Tools, Resources, Prompts
  - Difficulty: Intermediate | Estimated time: 2 hour(s) | Priority: High | Dates: 2026-11-04 00:00:00 to 2026-11-06 00:00:00
  - **Practice:** Read the MCP spec and summarize key concepts
- [ ] **38. Building an MCP server**
  - **Cover:** Server setup (Python SDK), defining tools, resources, prompt templates
  - Difficulty: Advanced | Estimated time: 4 hour(s) | Priority: High | Dates: 2026-11-04 00:00:00 to 2026-11-06 00:00:00
  - **Practice:** Build an MCP server exposing 2-3 custom tools + a resource
- [ ] **39. Clients & agent integration**
  - **Cover:** Connecting a client/agent, transports (stdio/SSE/HTTP), auth basics
  - Difficulty: Advanced | Estimated time: 3 hour(s) | Priority: High | Dates: 2026-11-04 00:00:00 to 2026-11-06 00:00:00
  - **Practice:** Connect a custom client/agent to your MCP server

## Data Science

### Statistics

- [ ] **40. Descriptive statistics & EDA**
  - **Cover:** Mean/median/mode, variance, std dev, skewness; histograms, box plots
  - Difficulty: Beginner | Estimated time: 3 hour(s) | Priority: High | Dates: 2026-11-09 00:00:00 to 2026-11-10 00:00:00
  - **Practice:** Build an EDA notebook for a real dataset
- [ ] **41. Probability & distributions**
  - **Cover:** Conditional probability, Bayes' theorem, normal/binomial/Poisson dists
  - Difficulty: Intermediate | Estimated time: 4 hour(s) | Priority: High | Dates: 2026-11-09 00:00:00 to 2026-11-10 00:00:00
  - **Practice:** Fit distributions to sample data with scipy.stats
- [ ] **42. Sampling & hypothesis testing**
  - **Cover:** CLT, standard error, t-test, chi-square, ANOVA, p-values, CIs
  - Difficulty: Advanced | Estimated time: 4 hour(s) | Priority: High | Dates: 2026-11-09 00:00:00 to 2026-11-10 00:00:00
  - **Practice:** Run an A/B test analysis on sample data
- [ ] **43. Correlation & regression**
  - **Cover:** Pearson/Spearman correlation, linear/logistic regression, regularization
  - Difficulty: Advanced | Estimated time: 4 hour(s) | Priority: High | Dates: 2026-11-09 00:00:00 to 2026-11-10 00:00:00
  - **Practice:** Build and interpret a regression model from scratch
- [ ] **44. Model evaluation & applied stats**
  - **Cover:** R²/RMSE/precision/recall/F1/ROC-AUC, time series basics, A/B design
  - Difficulty: Advanced | Estimated time: 3 hour(s) | Priority: High | Dates: 2026-11-09 00:00:00 to 2026-11-10 00:00:00
  - **Practice:** Evaluate a classifier and justify the right metric

### Python Data Science Libraries

- [ ] **45. NumPy fundamentals**
  - **Cover:** ndarray, vectorized operations, broadcasting, indexing/slicing, reshaping, aggregations
  - Difficulty: Intermediate | Estimated time: 3 hour(s) | Priority: High | Dates: 2026-11-11 00:00:00
  - **Practice:** Perform vectorized computations and reshape sample datasets with NumPy
- [ ] **46. Pandas fundamentals**
  - **Cover:** Series/DataFrame basics, loc/iloc indexing, filtering, missing-data (NaN) handling, dtypes
  - Difficulty: Intermediate | Estimated time: 3 hour(s) | Priority: High | Dates: 2026-11-11 00:00:00
  - **Practice:** Clean a messy dataset: handle missing values, filter rows, and fix dtypes
- [ ] **47. Pandas for analysis**
  - **Cover:** groupby/aggregation, merge/join/concat, pivot tables, apply/vectorized ops, time series basics
  - Difficulty: Advanced | Estimated time: 3 hour(s) | Priority: High | Dates: 2026-11-11 00:00:00
  - **Practice:** Build a groupby + merge analysis pipeline on a real dataset

### AI & ML Foundations

- [ ] **48. ML lifecycle & supervised learning**
  - **Cover:** Problem framing, regression/classification, decision trees, ensembles
  - Difficulty: Advanced | Estimated time: 4 hour(s) | Priority: High | Dates: 2026-11-12 00:00:00 to 2026-11-17 00:00:00
  - **Practice:** Train and tune a classifier with scikit-learn
- [ ] **49. Unsupervised learning & feature eng.**
  - **Cover:** Clustering (k-means/DBSCAN), PCA/t-SNE, encoding, scaling, imbalance handling
  - Difficulty: Advanced | Estimated time: 4 hour(s) | Priority: High | Dates: 2026-11-12 00:00:00 to 2026-11-17 00:00:00
  - **Practice:** Cluster a dataset, visualize with PCA, build a feature pipeline
- [ ] **50. Model tuning & evaluation**
  - **Cover:** Cross-validation, grid/random search, overfitting, bias-variance
  - Difficulty: Advanced | Estimated time: 3 hour(s) | Priority: High | Dates: 2026-11-12 00:00:00 to 2026-11-17 00:00:00
  - **Practice:** Tune hyperparameters with cross-validation
- [ ] **51. Deep learning & NLP basics**
  - **Cover:** Neural nets, backprop, CNN/RNN overview, tokenization, embeddings, TF-IDF
  - Difficulty: Advanced | Estimated time: 4 hour(s) | Priority: Medium | Dates: 2026-11-12 00:00:00 to 2026-11-17 00:00:00
  - **Practice:** Build a small NN and a TF-IDF text classifier
- [ ] **52. Transformers, LLMs & prompting**
  - **Cover:** Attention mechanism, pretraining vs fine-tuning, prompt engineering, sampling parameters (temperature, top-p, top-k)
  - Difficulty: Advanced | Estimated time: 4 hour(s) | Priority: High | Dates: 2026-11-12 00:00:00 to 2026-11-17 00:00:00
  - **Practice:** Design prompts for 5 task types at different temperatures; diagram transformer architecture
- [ ] **53. LLM APIs & agents**
  - **Cover:** Anthropic/OpenAI APIs, tool/function calling, streaming, agent loops, controlling temperature/max_tokens for deterministic vs creative output
  - Difficulty: Intermediate | Estimated time: 4 hour(s) | Priority: High | Dates: 2026-11-12 00:00:00 to 2026-11-17 00:00:00
  - **Practice:** Build a tool-calling agent using an LLM API and compare outputs at different temperature settings

### RAG & Vector Databases (overview)

- [ ] **54. Embeddings, vector search & RAG pipeline**
  - **Cover:** Embeddings & similarity search, vector DB indexing options (FAISS/Chroma/pgvector), RAG architecture (retrieve→generate), chunking, GraphRAG overview
  - Difficulty: Advanced | Estimated time: 4 hour(s) | Priority: High | Dates: 2026-11-12 00:00:00 to 2026-11-17 00:00:00
  - **Practice:** Build a minimal RAG demo: embed documents, store in a vector DB, retrieve and generate an answer
