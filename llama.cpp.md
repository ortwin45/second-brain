# Starting a server

- ``llama-server -hf ggml-org/gemma-4-E4B-it-GGUF --tools get_datetime --reasoning off``
- ``llama-server -hf Qwen3.6-27B-Q5_K_M-mtp.gguf --spec-type mtp --spec-draft-n-max 3 -np 1 -c 74000 --temp 0.7 --top-k 20 -ngl 99``
- ``llama-server -hf Qwen3.6-27B-Q5_K_M-mtp.gguf --temperature 0.6 --top-p 0.95 --top-k 20 --min-p 0.0``

# Syntax

list all models in cache: 
- -cl,   --cache-list                     show list of models in cache
- --temp, --temperature N                 temperature (default: 0.80)
- --repeat-penalty N                      penalize repeat sequence of tokens (default: 1.00, 1.0 = disabled)

# Models

[unsloth/Qwen3.6-27B-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-GGUF)

temperature=0.6, top_p=0.95, top_k=20, min_p=0.0, presence_penalty=0.0, repetition_penalty=1.0

Not enough memory


[unsloth/Qwen3.6-35B-A3B-GGUF:UD-Q4_K_M](https://huggingface.co/unsloth/Qwen3.6-35B-A3B-GGUF)

Not enough memory


[unsloth/Qwen3.5-9B-GGUF](https://huggingface.co/unsloth/Qwen3.5-9B-GGUF)

Thinking mode for precise coding tasks (e.g., WebDev):
temperature=0.6, top_p=0.95, top_k=20, min_p=0.0, presence_penalty=0.0, repetition_penalty=1.0