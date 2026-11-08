# Complete AI/ML Engineering Roadmap

This roadmap is ordered by dependency. Move forward when you can apply the current stage, not when you have consumed every available resource.

## 01 — Programming and engineering tools
**Learn:** Python fluency; C++ fundamentals; data structures in both languages; debugging; testing; Git/GitHub; Linux shell; files, processes, permissions, environment variables, package management.

**Build:** CLI data cleaner, reusable Python package, C++ algorithm collection, tested command-line application.

**Ready when:** you can write readable modular code, use a debugger, write tests, profile a basic program, and work comfortably from a terminal.

## 02 — Mathematics for machine learning
**Foundations:** algebra, functions, logarithms, trigonometry, vectors, summation notation.

**Linear algebra:** vectors, matrices, linear transformations, systems of equations, rank, basis, subspaces, orthogonality, projections, eigenvalues/eigenvectors, SVD, matrix calculus basics.

**Calculus:** limits, derivatives, chain rule, partial derivatives, gradients, Jacobians, Hessians, multivariable optimization, integrals.

**Probability and statistics:** random variables, common distributions, expectation, variance, covariance, conditional probability, Bayes' theorem, sampling, estimation, confidence intervals, hypothesis tests, likelihood, maximum likelihood.

**Optimization:** convexity, gradient descent, SGD, momentum, Adam, constraints, regularization, learning-rate schedules.

**Information theory:** entropy, cross-entropy, KL divergence, mutual information.

**Build:** NumPy implementations of linear regression, logistic regression, PCA, gradient descent, and a small autodiff engine.

**Ready when:** you can derive gradients for common models and explain what the equations mean geometrically and statistically.

## 03 — Computer science foundations
**Algorithms and data structures:** arrays, strings, linked lists, stacks, queues, hashing, trees, heaps, graphs, sorting, searching, recursion, greedy algorithms, dynamic programming, complexity analysis.

**Computer systems:** binary representation, memory hierarchy, CPU, caches, processes, threads, concurrency, virtual memory, filesystems, system calls.

**Operating systems:** scheduling, synchronization, deadlocks, memory management, storage, networking interfaces.

**Networking:** TCP/IP, DNS, HTTP, TLS, sockets, latency, throughput, load balancing.

**Databases:** relational modeling, SQL, indexes, transactions, query plans, isolation, NoSQL trade-offs.

**Build:** multithreaded data processor, SQL-backed API, simple key-value store or cache.

## 04 — Data science and data engineering
**Learn:** NumPy, Pandas, visualization, exploratory data analysis, missing data, outliers, leakage, data validation, feature engineering, SQL analytics, ETL/ELT, reproducible pipelines, dataset versioning.

**Build:** end-to-end dataset pipeline with validation, analysis notebook, and documented data dictionary.

**Ready when:** you can take raw data to a reproducible, leakage-aware training dataset.

## 05 — Classical machine learning
**Foundations:** supervised vs unsupervised learning, train/validation/test splits, cross-validation, bias-variance, overfitting, underfitting, regularization, feature scaling, metrics, calibration, class imbalance, leakage.

**Algorithms:** linear and logistic regression, k-nearest neighbors, naive Bayes, decision trees, random forests, gradient boosting, SVMs, clustering, PCA, anomaly detection.

**Model practice:** scikit-learn pipelines, hyperparameter search, error analysis, interpretability, experiment tracking.

**Build:** tabular prediction project with a baseline, strong validation, error analysis, and reproducible inference.

## 06 — Deep learning
**Learn:** perceptrons, MLPs, activations, losses, backpropagation, initialization, normalization, regularization, optimizers, learning-rate schedules, embeddings, batching, GPU training.

**Framework:** PyTorch tensors, autograd, nn.Module, Dataset/DataLoader, training loops, checkpoints, mixed precision, profiling, reproducibility.

**Architectures:** CNNs, RNNs, LSTMs/GRUs, attention, autoencoders, generative models, diffusion foundations.

**Build:** implement an MLP and backpropagation from scratch; train and compare a CNN; create a reproducible training pipeline.

## 07 — NLP, Transformers, and LLM engineering
**NLP foundations:** text preprocessing, tokenization, embeddings, language modeling, sequence tagging, evaluation.

**Transformers:** attention, positional representations, encoder/decoder blocks, residual connections, normalization, causal masking, tokenization, pretraining and fine-tuning.

**LLM engineering:** prompting, structured outputs, tool calling, fine-tuning, LoRA/QLoRA concepts, evaluation datasets, hallucination analysis, safety and latency/cost trade-offs.

**Retrieval systems:** chunking, embedding models, vector search, hybrid retrieval, reranking, retrieval evaluation, citations, access control.

**Agents:** tool interfaces, state, planning limits, retries, observability, human approval, failure handling.

**Build:** train a tiny language model, implement a small Transformer, build a measured RAG application, and evaluate an LLM workflow.

## 08 — AI systems and performance engineering
**Hardware:** CPU/GPU architecture, memory hierarchy, parallelism, bandwidth, FLOPs, occupancy, profiling.

**GPU programming:** CUDA execution model, kernels, memory transfers, shared memory, synchronization, reductions, tiling.

**Deep learning systems:** tensor layouts, computational graphs, operator fusion, mixed precision, quantization, memory optimization, distributed data/model/tensor parallelism.

**LLM inference:** prefill vs decode, KV cache, batching, continuous batching, speculative decoding, quantization, serving throughput and tail latency.

**Tools:** CUDA, Nsight, Triton, PyTorch Profiler, vLLM, SGLang.

**Build:** benchmark CPU vs GPU operations; write and profile a CUDA/Triton kernel; serve an open model and measure throughput, latency, and memory.

## 09 — Production engineering and MLOps
**Software engineering:** API design, clean architecture, typing, testing, logging, configuration, security, reliability.

**Backend:** HTTP, REST, FastAPI, authentication, async programming, queues, caching.

**Deployment:** Docker, CI/CD, cloud fundamentals, Kubernetes concepts, monitoring, secrets, model serving.

**MLOps:** experiment tracking, model registry, data/model versioning, feature and inference monitoring, drift, rollback, reproducibility.

**Build:** deploy a model-backed API with tests, containerization, CI, monitoring, and documented rollback.

## 10 — Research engineering
**Learn:** reading papers efficiently, identifying claims, reproducing baselines, ablation studies, controlled experiments, statistical reporting, compute budgeting, research ethics.

**Practice:** reproduce a published result, document deviations, compare against a baseline, and publish code plus a technical report.

**Ready when:** you can translate a paper into a reliable implementation and distinguish evidence from speculation.

## 11 — Specializations
Choose one primary specialization after the shared foundations:
- **LLM systems:** inference, serving, distributed training, evaluation.
- **Computer vision:** image models, detection, segmentation, vision Transformers.
- **Reinforcement learning:** MDPs, value methods, policy gradients, actor-critic.
- **Multimodal AI:** joint representations, vision-language models, audio/text systems.
- **Applied ML:** ranking, recommendation, forecasting, experimentation.
- **Research:** choose a narrow question and build depth through papers and replications.

Add Rust, advanced C++, CUDA, SQL, or TypeScript when a project requires them; do not learn languages without a concrete use case.

## 12 — Career preparation
**Engineering portfolio:** 3–4 substantial projects, clean repositories, tests, benchmarks, architecture diagrams, reproducible setup, clear READMEs.

**Interview preparation:** DSA, Python/C++, SQL, ML fundamentals, statistics, deep learning, ML system design, debugging, behavioral stories.

**Research readiness:** paper summaries, reproduction reports, open-source contributions, technical writing, clear explanation of limitations.

## Mastery ladder
1. **Apply:** use established libraries correctly and evaluate outputs.
2. **Engineer:** design, implement, test, deploy, monitor, and optimize complete systems.
3. **Research:** reproduce results, run controlled experiments, challenge assumptions, and contribute new ideas.

## Project milestones
See [the project ladder](projects/PROJECTS.md). Projects should grow in complexity alongside the curriculum.
