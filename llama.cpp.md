# Starting a server

- ``llama-server -hf ggml-org/gemma-4-E4B-it-GGUF --tools get_datetime --reasoning off``
- ``llama-server -hf ggml-org/gemma-4-E4B-it-GGUF --tools get_datetime --temp 0.4 --repeat-penalty 1.2``


list all models in cache: 
- -cl,   --cache-list                     show list of models in cache
- --temp, --temperature N                 temperature (default: 0.80)
- --repeat-penalty N                      penalize repeat sequence of tokens (default: 1.00, 1.0 = disabled)


