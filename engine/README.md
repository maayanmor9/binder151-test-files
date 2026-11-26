# Binder151 phone engine files

Recognition files the Binder151 apps download to scan cards on the phone itself. No code here.

Licences:
- `dino_int8.onnx` (card matcher): a fine-tune of DINOv3 ViT-S/16 by Meta Platforms, Inc., distributed under the
  DINOv3 License (`LICENSES/DINOv3-License.md`). **Built with DINOv3.**
- `finder.onnx`, `upright_head.*`, `number_reader.*`: from the CardCorpus Scanner, Copyright 2026 The CardCorpus Authors,
  Apache License 2.0 (`LICENSES/Apache-2.0.txt`, `LICENSES/CardCorpus-models-NOTICE.txt`).
- `cc_art.json`: card facts from CardCorpus's reference index, CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/),
  credit: CardCorpus.
- `ch_PP-OCR*.onnx`, `ocr_keys.txt`: PaddleOCR PP-OCRv4 models (via RapidOCR), Apache License 2.0.

Pokémon and Pokémon character names are trademarks of Nintendo, Creatures and GAME FREAK. Card pictures and text are
© The Pokémon Company, Nintendo, Creatures, GAME FREAK and, for older cards, Wizards of the Coast. Binder151 is not
produced, endorsed, sponsored or supported by, or affiliated with, any of them.
