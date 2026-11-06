# Chad Saglam

Data & ML Engineer in Zurich. I build data pipelines, then fine-tune and evaluate small models on top of them, and I report what doesn't work as well as what does.

10+ years in software engineering, 4+ in applied ML. MSc Computer Engineering, BSc Physics.

## Featured projects

| Project | What it is | Result |
|---|---|---|
| [evidence-rag](https://github.com/ChadSaglam/evidence-rag) | Evidence-first multilingual RAG (EN / DE / FR): BM25, dense and hybrid retrieval, reranking, NLI citation checks, 154 tests and CI | NLI verifier cuts false citation accepts from **56% to 6%**; best retrieval nDCG@10 **0.805** |
| [swiss-bookkeeping-ai](https://github.com/ChadSaglam/swiss-bookkeeping-ai) | LoRA fine-tune of Qwen2.5-0.5B for Swiss SME account suggestion, trained with MLX on Apple Silicon | 16.2% → **93.2%** accuracy on held-out vendors, **98.6%** top-3 · [live demo](https://huggingface.co/spaces/ChadSaglam/swiss-bookkeeping-demo) |
| [efficiency-lab](https://github.com/ChadSaglam/efficiency-lab) | Accuracy, latency and memory of fp16, 8-bit and 4-bit variants against a larger prompted model | Fine-tuned 0.5B beats prompted 1.5B by **54 points** at one third of the memory |
| [bookkeeping-mcp-agent](https://github.com/ChadSaglam/bookkeeping-mcp-agent) | MCP server that drafts bookings with an 8-bit model plus deterministic VAT and amount checks; never posts on its own | Stress-tested with **352** adversarial inputs, failure rates reported |
| [code-model-lab](https://github.com/ChadSaglam/code-model-lab) | GLM-style code model trained from random weights in PyTorch, then improved with reinforcement learning | **3 → 15 of 24** unseen tasks solved after RL; seed-to-seed noise measured |
| [swiss-law-rag](https://github.com/ChadSaglam/swiss-law-rag) | Multilingual RAG over Swiss federal law excerpts (DE / EN / FR) | **Hit@4 100%** on 40 hand-written questions |

Models, datasets and demos: [huggingface.co/ChadSaglam](https://huggingface.co/ChadSaglam)

## Stack

Python, PyTorch, MLX, Hugging Face, LoRA, scikit-learn, RAG, SQL, PostgreSQL, ETL/ELT, Docker, Git, CI

## Contact

[LinkedIn](https://www.linkedin.com/in/chadsaglam) · [chadev.ch](https://chadev.ch) · saglam.chad@chadev.ch
