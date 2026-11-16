# Lumen on-device models

Model files downloaded once by the Lumen photo app for offline search. Nothing is uploaded from phones.

- **SigLIP 2** (ViT-B/16, 224 px) by Google, Apache-2.0: https://huggingface.co/google/siglip2-base-patch16-224
  Converted to ExecuTorch 1.4.1: image tower int8 (XNNPACK), text tower int8 linears + 4-bit vocabulary.

Files are attached to the `models-v1` release.
