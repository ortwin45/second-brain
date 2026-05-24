# llama.cpp

## Starting a server

- ``llama-server -hf ggml-org/gemma-4-E4B-it-GGUF --tools get_datetime --reasoning off``
- ``llama-server -hf Qwen3.6-27B-Q5_K_M-mtp.gguf --spec-type mtp --spec-draft-n-max 3 -np 1 -c 74000 --temp 0.7 --top-k 20 -ngl 99``
- ``llama-server -hf Qwen3.6-27B-Q5_K_M-mtp.gguf --temperature 0.6 --top-p 0.95 --top-k 20 --min-p 0.0``

## llama-server common params

- -cl,   --cache-list                     show list of models in cache
- --tools get_datetime						


## Working models

### [unsloth/gemma-4-E4B-it-GGUF:Q8_K_XL](https://huggingface.co/unsloth/gemma-4-E4B-it-GGUF)

### [unsloth/Qwen3.5-9B-GGUF:Q6_K_XL](https://huggingface.co/unsloth/Qwen3.5-9B-GGUF)

## Models too big

Not enough memory

- [unsloth/Qwen3.6-27B-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-GGUF)
- [unsloth/Qwen3.6-35B-A3B-GGUF:UD-Q4_K_M](https://huggingface.co/unsloth/Qwen3.6-35B-A3B-GGUF)
