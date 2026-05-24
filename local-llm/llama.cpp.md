# llama.cpp

## llama-server common params

- -cl,   --cache-list
- --tools get_datetime
- -rea,  --reasoning [on|off|auto]
- --temp, --temperature N 

To disable thinking / reasoning, use ``--chat-template-kwargs '{"enable_thinking":false}'``

## Working models

### [unsloth/gemma-4-E4B-it-GGUF:Q8_K_XL](https://huggingface.co/unsloth/gemma-4-E4B-it-GGUF)

``llama-server -hf unsloth/gemma-4-E4B-it-GGUF:Q8_K_XL --temp 1.0 --top-p 0.95 --top-k 64``

### [unsloth/Qwen3.5-9B-GGUF:Q6_K_XL](https://huggingface.co/unsloth/Qwen3.5-9B-GGUF)

Recommended for coding: 

``llama-server -hf unsloth/Qwen3.5-9B-GGUF:Q6_K_XL --temp 0.6 --top-p 0.95 --top-k 20 --repeat-penalty 1.0 --chat-template-kwargs '{"enable_thinking":true}' --min-p 0.00 --presence-penalty 0.00`` 

[Recommended settings](https://unsloth.ai/docs/models/qwen3.5)

## Models too big

Not enough memory

- [unsloth/Qwen3.6-27B-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-GGUF)
- [unsloth/Qwen3.6-35B-A3B-GGUF:UD-Q4_K_M](https://huggingface.co/unsloth/Qwen3.6-35B-A3B-GGUF)
