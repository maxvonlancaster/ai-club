# Ідеї до семінару на тематику "Основи ШІ та його застосування в прикладних задачах"



## Теми занятть

**1. Вступ до ШІ та типи задач.**
- Класифікація, регресія. Генерація данних.
- Pipeline ШІ систем.
- Огляд ШІ додатків.

**2. NLP та векторизація.**
- токенізація.
- TF-IDF.
- векторизація, embeddings (Word2Vec, GloVe, OpenAi).

**3. Трансформери, attention.**
- self-attention. Інтуіція використання трансформерів.
- encoder/decoder. Позиційний encoding.

**4. Промпт інжиниринг.**
- few-shot / zero-shot, структурований промптинг.
- Tree of thoughts, experts.

**5. Open-source AI, автоматизовані рішення, HuggingFace.**
- closed-source vs open-source, API vs local, конфіденційність, затримка, вартість
- Llama, DeepSeek
- HuggingFace екосистема (transformers, datasets, tokenizers, diffusers, spaces), hub (model cards, datasets, inference API, downloading and loading models)
- Inference pipelines (pipeline("text-generation"), sentiment-analysis, image-to-text)
- Local AI (Ollama, llama.cpp, quantization (GGUF, GPTQ))
- AI automation (automated summarization, classification pipelines, AI assistants, document processing)
- *Практика*: запуск open-source LLM локально, створення AI chatbot, HuggingFace Spaces demo

**6. Евалюація LLM.**
- Галюцинації. Метрики.
- Типи оцінки: automatic, human, benchmark.
- Метрики: BLEU, ROUGE, BERTScore, perplexity

**7. Rag системи. Вступ.**
- Векторні DB, пошук по данних.
- Chunking (fixed, semantic, recursive)
- Retrieval methods (dense, sparse, hybrid)
- Просунуті методи (reranking, graph RAG, agentic RAG, multimodal RAG)
- Проблеми: context poisoning, retrieval failures, token limits
- *Практика*: PDF chatbot, local document assistant, semantic search engine

**8. Робота з данними.**
- Збір данних, візуалізація данних.
- Дата процессинг: імпутація, нормалізація, масштабування.
- Конструювання ознак. 
- Використання ШІ для імпутування данних.

**9. Машинне навчання, огляд.**
- Вступ в ML, лінійна/логістична регресії
- SVM, поліноміальне ML
- PCA, k-means
- Ансамблеві моделі: Random Forest, XGBoost

**10. Глибинне навчання.**
- Нейронні мережі, типи нейронних мереж.

**11. Gradio додатки.**
- Приклади конструювання та деплою ШІ додатків в Gradio.

**12. Streamlit додатки.**
- Приклади конструювання та деплою ШІ додатків в Streamlit.

**13. Файн-тюнинг моделей.**
- transfer learning, domain adaptation
- Типи: full fine-tuning, LoRA, QLoRA, adapters
- Instruction tuning: Alpaca format, conversational datasets
- Dataset preparation: cleaning, formatting, synthetic data generation
- Training pipelines: HuggingFace Trainer, PEFT, TRL
- Quantization: 4-bit / 8-bit, memory optimization
- reinforcement learning from human feedback, preference optimization
- Direct Preference Optimization
- Catastrophic forgetting, overfitting on instruction data
- Practical infrastructure (GPU VRAM, checkpointing, gradient accumulation)
- *Практика*: fine-tuning chatbot, domain-specific assistant, medical/legal tuning

**14. Мульти-агент системи.**
- архітектура агентів.
- tool use.

**15. MCP сервера.**
- Що таке MCP протокол.
- *Практика*: створення власного MCP server, AI assistant with tools, filesystem agent demo

**16. Diffusion та робота із зображеннями.**
- Stable Diffusion, теорія.
- Sam 2, yolo, робота із зображеннями. 

**17. Теорія ігор та змагальні ШІ рішення.**
- VAE, GAN

**18. Production ML, MLops**
- ML пайплайни, Azure, AWS.


## Що можуть робити студенти


- Власне datascience дослідження.
- RAG система. 
- Файн-тюнинг фронтир моделі.
- Файн-тюнинг опен-сорсної моделі.
- Побудова автономної мульти-агентної системи.
- MCP сервер.






## Загальні ідеї.

**1. Створення ai-застосунків**. 
- Rag
- Agents, multi-agent systems
- MCP сервери.
- Голосові ai системи.
- Локальні ші системи.

Результат навчання: задеплоєний додаток.

**2. Огляд алгоритмів машинного навчання та data science.**
- Алгоритми машинного навчання, як їх використовувати.

Результат навчання: проведене дослідження в сфері науки про дані, тези конференції

**3. Промпт інжиниринг.**
- Техніки промпт-інжинирингу.
- Типи ai додатків, як їх використовувати.

Результат навчання: реферат (?)