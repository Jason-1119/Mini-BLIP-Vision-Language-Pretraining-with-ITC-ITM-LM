# Mini-BLIP-Vision-Language-Pretraining-with-ITC-ITM-LM

Mini-BLIP: A Lightweight Vision-Language Model

A simplified implementation of a BLIP-style vision-language model trained on Flickr30k, combining:

Image Captioning (LM)
Image-Text Contrastive Learning (ITC)
Image-Text Matching (ITM)

This project aims to reproduce core ideas behind modern multimodal models such as BLIP and CLIP in a compact and educational setting.

🚀 Features
✅ Vision encoder: ViT-based image representation
✅ Text decoder: Transformer-based language model
✅ Multi-task training:
Language Modeling (LM)
Image-Text Contrastive (ITC)
Image-Text Matching (ITM)
✅ Joint embedding space for image-text alignment
✅ Caption generation (greedy / beam search)
✅ Evaluation metrics:
BLEU-1 ~ BLEU-4
ITC Recall@1
ITM Accuracy
