# [1] EXAONE 3.5 (Open LLMs for Real-world use cases)
This technical report introduces EXAONE 3.5,instruction-tuned LLMs (32B, 7.8B, and 2.4B), developed by LG AI Research. These models feature several standout capabilities: 1) exceptional instruction following capabilities in real-world scenarios, 2) outstanding long-context comprehension and 3) competitive results compared to state-of-the-art open models across nine general benchmarks. [Tweet] and [Paper]

# [2] Granite Guardian (Open Safeguard LLMs)
This paper introduces the Granite Guardian models, a suite of safeguard LLMs. Granite Guardian models are trained on a unique dataset combining human annotations from diverse sources and synthetic data.  These safeguard LLMs provide risk detection for prompts and responses, enabling safe and responsible use in combination with any large language model (LLM). [Tweet] and [Paper]

# [3] Asynchronous LLM Function Calling
This paper introduces AsyncLM, a system for asynchronous LLM function calling. LLMs use function calls to interface with external tools and data source. However, the current approach to LLM function calling is inherently synchronous, where each call blocks LLM inference, limiting LLM operation and concurrent function execution. AsyncLM improves LLM’s operational efficiency by enabling LLMs to generate and execute function calls concurrently. [Tweet] and [Paper]

# [4] Efficient Long-Context LLM Inference for Mid-Range GPUs
This paper introduces  SparseAccelerate for efficient long-context LLM inference in mid-range GPUs.  SparseAccelerate  is a dynamic sparse attention method that adapts its sparsity patterns based on input characteristics, effectively flattening the attention complexity curve. Results show that SparseAccelerate achieves up to a 1.04x reduction in Time-To-First-Token (TTFT) latency at 32K tokens, while also providing substantial memory savings. [Tweet] and [Paper]

If you find this newsletter informative, you can support me with a coffee.

# [5] LLM-based Evaluation Methods (Survey)
This paper provides a comprehensive survey on LLM-based evaluation methods from five key perspectives: Functionality, Methodology, Applications, Meta-evaluation, and Limitations. The paper also presents a detailed analysis of the limitations of LLM judges and discusses potential future directions. To summarize, the paper provides insights on the development and application of LLMs-as-judges in both research and practice. [Tweet] and [Paper](https://arxiv.org/abs/2412.04862)

# [6] Reranking with LLMs
This paper introduces PyTerrier-GenRank, the PyTerrier plugin for reranking with LLMs. This library facilitates seamless reranking experiments with LLMs, supporting popular ranking strategies like pointwise and listwise prompting. [Tweet] and [Paper]

# [7] Lightweight LLM Evaluation Toolbox 
This paper introduces OmniEvalKit, a lightweight toolbox to evaluate LLMs and their omni-extensions across multilingual, multidomain, and multimodal capabilities. OmniEvalKit supports over 100 LLMs and 50 evaluation datasets, covering comprehensive evaluations across thousands of model-dataset combinations. Importantly, OmniEvalKit provides a modular, lightweight, and automated evaluation system. [Tweet] and [Paper]

# [8] Code LLMs (Survey)
This paper provides a comprehensive survey of code LLMs, investigating how these models are utilized in coding tasks and examining their methodologies, architectures, and training processes. This survey offers insights into the current state and future directions of LLMs in coding tasks, including their applications and limitations. [Tweet] and [Paper]

# [9] LLM-based Text Embeddings (Survey)
This paper presents a survey on LLM-based text embeddings. This paper covers (1) LLM-augmented text embedding, enhancing traditional embedding methods with LLMs; (2) LLMs as text embedders, utilizing their innate capabilities for embedding generation; and (3) Text embedding understanding with LLMs, leveraging LLMs to analyze and interpret embeddings. [Tweet] and [Paper]

# [10] Phi-4 Technical Report
This paper introduces phi-4, a 14-billion parameter LLM developed with a training recipe that is centrally focused on data quality.  phi-4 strategically incorporates synthetic data throughout the training process. Despite minimal changes to the phi-3 architecture, phi-4 achieves strong performance relative to its size due to improved data, training curriculum, and innovations in the post-training scheme. [Tweet] and [Paper]
