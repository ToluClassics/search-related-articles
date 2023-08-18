# Semantic Search & Retrieval Augmented Generation Research and Implementations 🧠🔍
This repository is dedicated to collecting blog posts and articles on the implementation of state-of-the-art techniques in semantic search, dense retrieval, and retrieval augmented generation (RAG). From theoretical exploration to hands-on performance in real-world scenarios, this repository serves as a central hub for researchers, practitioners, and enthusiasts in the field.

# Who is this Repository For? 🎓
Whether you are a seasoned researcher, a software engineer, a student stepping into the world of dense retrieval, or a business leader looking to understand the practical implications of these technologies, this repository provides valuable insights and resources tailored to your needs.

- [Scaling the Instagram Explore recommendations system](https://engineering.fb.com/2023/08/09/ml-applications/scaling-instagram-explore-recommendations-system/)<br>
  <b>Preview: Explore is one of the largest recommendation systems on Instagram. We leverage machine learning to make sure people are always seeing content that is the most interesting and relevant to them. Using more advanced machine learning models, like Two Towers neural networks, we’ve been able to make the Explore recommendation system even more scalable and flexible.</b>

- [Search: Query Matching via Lexical, Graph, and Embedding Methods](https://eugeneyan.com/writing/search-query-matching/#supervised-techniques-improves-modeling-of-our-desired-event)<br>
  <b>Preview: Search and recommendations have a lot in common. They help users learn about new products, and need to retrieve and rank millions of products in a very short time (<150ms). They’re trained on similar data, have content and behavioral-based approaches, and optimize for engagement (e.g., click-through rate) and revenue (e.g., conversion, gross merchandise value).</b>

- [Broad and Ambiguous Search Queries](https://dtunkelang.medium.com/broad-and-ambiguous-search-queries-1bbbe417dcc)<br>
  <b>Preview: A typical approach for processing search queries is to retrieve a set of matching documents and then rank them with a relevance scoring function. This simple approach generally works well for unambiguous, specific search queries.
But sometimes this approach breaks down. When a search query is broad (e.g., “shirts”), it isn’t clear how to decide which matching results are the most relevant ones.</b>

- [LambdaMART in Depth](https://softwaredoug.com/blog/2022/01/17/lambdamart-in-depth.html) by [Doug Turnbull](https://softwaredoug.com/) <br>
  <b>Preview:</b> LambdaMART is a classic. It’s the endlessly tinkerable classic car of ranking algorithms. If you can grok the algorithm, you can play with the model architecture, coming up with your own variations on this learning-to-rank staple....

- [How LambdaMART works - optimizing product ranking goals](https://softwaredoug.com/blog/2021/11/28/how-lammbamart-works.html) by [Doug Turnbull](https://softwaredoug.com/) <br>
  <b>Preview:</b> Learning to Rank optimizes search relevance using machine learning. If you bring to Learning to Rank training data – documents labeled as relevant/irrelevant for queries – you’ll get out a ranking function optimizing search closer to what users want....
  
- [Save space with byte-sized vectors](https://www.elastic.co/blog/save-space-with-byte-sized-vectors) <br>
  <b>Preview:</b> Elasticsearch is introducing a new type of vector in 8.6! This vector has 8-bit integer dimensions, where each dimension has a range of [-128, 127]. This is 4x smaller than the current vector with 32-bit float dimensions, which can result in substantial space savings...
  
- [5 Reasons why you should remove stop words (at indexing time)](https://opensourceconnections.com/blog/2023/01/30/5-reasons-why-you-should-remove-stop-words-at-indexing-time/) <br>
<b>Preview:</b> While storage feels almost infinite, and cheap, to boot, it does still cost money to store stopwords. Let’s consider a simple index. Each posting consumes 8 bytes for document ID, 4 bytes for position....

- [10 Reasons why you shouldn’t remove stop words](https://opensourceconnections.com/blog/2023/01/24/10-reasons-why-you-shouldnt-remove-stop-words/) <br>
  <b>Preview:</b> So there shouldn’t be any harm in removing them from the data we are indexing in search engines and from the queries that are sent to these to retrieve relevant results, right? ..
  
- [Serving Large Language Models to improve Search Relevance at leboncoin](https://medium.com/@_leboncoin/serving-large-language-models-to-improve-search-relevance-at-leboncoin-2a364e5b6f76)<br>
  <b>Preview:</b> In this post, we describe this first iteration towards an improved search relevance. By the end of the post you will know how we successfully deployed in production, facing highly restrictive conditions specific to the search engine industry, large neural networks to facilitate users’ contact and improve their search experience on leboncoin........

- [Improving Search Ranking with Few-Shot Prompting of LLMs](https://blog.vespa.ai/improving-text-ranking-with-few-shot-prompting/)<br>
  <b>Preview:</b> This blog post explores using large language models (LLMs) to generate labeled data for training ranking models. Distilling the knowledge and power of generative models with billions of parameters to ranking models with a few million parameters...
  
- [eBay’s Blazingly Fast Billion-Scale Vector Similarity Engine](https://tech.ebayinc.com/engineering/ebays-blazingly-fast-billion-scale-vector-similarity-engine/)<br>
  <b>Preview:</b> The Similarity Engine's use cases include item-to-item similarity for text and image modality and user-to-item personalized recommendations based on a user’s historical behavior data....

- [Ask like a human: Implementing semantic search on Stack Overflow](https://stackoverflow.blog/2023/07/31/ask-like-a-human-implementing-semantic-search-on-stack-overflow/)<br>
  <b>Preview</b>: Our hypothesis is that if our semantic search produces high-quality results, technologists looking for answers will use our search instead of a search engine or conversational AI. Our forthcoming semantic search functionality is the first step in a continuous experimental process that will involve a lot of data science, iteration, and most importantly: our users. We’re excited to embark upon this adventure together with our community and can’t wait for you to experience our new semantic search.

- [Retrieval Augmented Generation: Streamlining the creation of intelligent natural language processing models](https://ai.meta.com/blog/retrieval-augmented-generation-streamlining-the-creation-of-intelligent-natural-language-processing-models/)<br>
  <b>Preview</b>: RAG looks and acts like a standard seq2seq model, meaning it takes in one sequence and outputs a corresponding sequence. There is an intermediary step though, which differentiates and elevates RAG above the usual seq2seq methods. Rather than passing the input directly to the generator, RAG instead uses the input to retrieve a set of relevant documents, in our case from Wikipedia.

- [Should you use OpenAI's embeddings? Probably not, and here's why.](https://iamnotarobot.substack.com/p/should-you-use-openais-embeddings)<br>
  <b>Preview</b>: If you do go with OpenAI, one word of advice: make sure you don’t spend $50M embedding the whole internet, become successful and then depend on OpenAI’s API to run your search engine!

- [Llama from scratch](https://blog.briankitano.com/llama-from-scratch/?utm_source=pocket_saves)<br>
  <b>Preview</b>: I want to provide some tips from my experience implementing a paper. I'm going to cover implementing a dramatically scaled-down version of Llama for training TinyShakespeare. This post is heavily inspired by Karpathy's Makemore series, which I highly recommend.

- [The little search engine that couldn’t](https://www.theverge.com/23802382/search-engine-google-neeva-android?utm_source=pocket_saves)<br>
  <b>Preview</b>: A couple of ex-Googlers set out to create the search engine of the future. They built something faster, simpler, and ad-free. So how come you’ve never heard of Neeva?

- [Patterns for Building LLM-based Systems & Products](https://eugeneyan.com/writing/llm-patterns/?utm_source=pocket_saves)<br>
  <b>Preview</b>: This write-up is about practical patterns for integrating large language models (LLMs) into systems & products. We’ll build on academic research, industry resources, and practitioner know-how, and distill them into key ideas and practices.

- [The Secret Sauce behind 100K context window in LLMs: all tricks in one place](https://blog.gopenai.com/how-to-speed-up-llms-and-use-100k-context-window-all-tricks-in-one-place-ffd40577b4c)<br>
  <b>Preview:</b> tldr; techniques to speed up training and inference of LLMs to use large context window up to 100K input tokens during training and inference: ALiBi positional embedding, Sparse Attention, FlashAttention, Multi-Query attention, Conditional computation, and 80GB A100 GPUs.

- [Emerging Architectures for LLM Applications](https://a16z.com/2023/06/20/emerging-architectures-for-llm-applications/?utm_source=pocket_reader)<br>
  <b>Preview:</b> Large language models are a powerful new primitive for building software. But since they are so new—and behave so differently from normal computing resources—it’s not always obvious how to use them.

- [Data Agents](https://medium.com/llamaindex-blog/data-agents-eed797d7972f)<br>
  <b>Preview:</b> Today we’re incredibly excited to announce the launch of a big new capability within LlamaIndex: Data Agents..

- [Building Advanced Query Engine and Evaluation with LlamaIndex and W&B](https://wandb.ai/ayush-thakur/llama-index-report/reports/Building-Advanced-Query-Engine-and-Evaluation-with-LlamaIndex-and-W-B--Vmlldzo0OTIzMjMy)<br>
  <b>Preview:</b> If you are trying to leverage an LLM to build a powerful search engine, a chatbot or any other LLM-based system over your data, LlamaIndex should be one of the first options to explore. Why is that? Well, you can literally build a search engine on top of your own data in just a few lines of code. And even that's just scratching the surface here. 

- [Delving Deeper Into LlamaIndex: An Inside Look](https://betterprogramming.pub/getting-started-with-llamaindex-part-2-a66618df3cd)<br>
  <b>Preview:</b> In my previous piece about LlamaIndex, we walked through a simple use case of indexing a GitHub repository to be able to ask questions about it. I thought it would be interesting to delve deeper and try to understand what it does in a bit more detail.

- [LlamaIndex: the ultimate LLM framework for indexing and retrieval](https://towardsdatascience.com/llamaindex-the-ultimate-llm-framework-for-indexing-and-retrieval-fa588d8ca03e)<br>
  <b>Preview:</b> LlamaIndex, previously known as the GPT Index, is a remarkable data framework aimed at helping you build applications with LLMs by providing essential tools that facilitate data ingestion, structuring, retrieval, and integration with various application frameworks. 
