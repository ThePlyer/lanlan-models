# lanlan-models

Model files the LanLan Android app downloads for its on-device voice.

## voice-v1: `qwen-talker-0.6b-customvoice-Q4_0m.gguf`
- **Model:** [Qwen3-TTS](https://github.com/QwenLM/Qwen3-TTS) 0.6B CustomVoice, © Alibaba Cloud / Qwen team, **Apache License 2.0**.
- **Source:** `qwen-talker-0.6b-customvoice-BF16.gguf` from [Serveurperso/Qwen3-TTS-GGUF](https://huggingface.co/Serveurperso/Qwen3-TTS-GGUF).
- **Changes:** re-quantized for phones with `qwen3_tts_quantize ... q4_0m`. The transformer blocks and heads are Q4_0 (Arm KleidiAI kernels, Adreno OpenCL). The embeddings are Q6_K. No other modification.
- **License:** Apache-2.0, see http://www.apache.org/licenses/LICENSE-2.0
