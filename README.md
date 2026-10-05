# lanlan-models

Model files the LanLan Android app downloads for its on-device voice.

This repository has **no license**; all rights reserved. The model files below are
third-party and remain under their own upstream terms, which require this notice.

## voice-v1: `qwen-talker-0.6b-customvoice-Q4_0m.gguf`
- **Model:** [Qwen3-TTS](https://github.com/QwenLM/Qwen3-TTS) 0.6B CustomVoice by the Qwen team (Alibaba Cloud), Apache License 2.0 (http://www.apache.org/licenses/LICENSE-2.0).
- **Source:** `qwen-talker-0.6b-customvoice-BF16.gguf` from [Serveurperso/Qwen3-TTS-GGUF](https://huggingface.co/Serveurperso/Qwen3-TTS-GGUF).
- **Modified:** re-quantized for phones. The transformer blocks and heads are Q4_0; the embeddings are Q6_K.
