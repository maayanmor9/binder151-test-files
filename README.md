# Binderlog test files

Downloads for the Binderlog test app (the code is private). The app fetches these itself.

- `Binderlog-Test.apk` - the Android test app
- recognition files (`model_fp32.onnx`, `index.*`, `meta.json`, `numbers.json`, `checks.json`, `cards.json`)

`model_fp32.onnx` is the image encoder of Google's SigLIP 2 (ViT-B-32-SigLIP2-256), licensed under the
Apache License 2.0 (https://www.apache.org/licenses/LICENSE-2.0), exported to ONNX with 8-bit weights.
Card names and pictures belong to their owners (The Pokémon Company / Nintendo / Creatures / GAME FREAK).
