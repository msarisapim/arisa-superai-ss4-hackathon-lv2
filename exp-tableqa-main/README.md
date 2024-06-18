
### Natural Language Table QA by EXP Season 4
This project uses OpenThaiGPT-13B as a base model, we fine-tuned it with [gretel dataset](https://huggingface.co/datasets/gretelai/synthetic_text_to_sql)

The pipeleine is as follows: 

User Query -> Similar Question retriever -> Prompt -> LLM -> Execute SQL on DB -> return query result
