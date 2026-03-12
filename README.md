# Multimodal-Credibility-Analysis
Transformer-based multimodal credibility analysis for social media posts using RoBERTa and ViLT.

# 1. Overview

Social media platforms often contain misleading or false information. Detecting the credibility of posts requires analyzing both textual content and associated images.

This project proposes a multimodal deep learning framework that combines:
- Text features extracted using RoBERTa
- Image features captured using Vision-and-Language Transformer (ViLT)
- Fusion of multimodal features for credibility classification.

The model predicts whether a social media post is credible or non-credible.


# 2. Model Architecture

The proposed system consists of four main components:

1. Text Encoder  
   - RoBERTa transformer model is used to extract contextual embeddings from the textual content of posts.

2. Image Encoder  
   - ViLT (Vision-and-Language Transformer) processes the image associated with the post.

3. Multimodal Fusion  
   - Text and image embeddings are combined to create a unified feature representation.

4. Classification Layer
   
# 3. Requirements

Python 3.8+

Main libraries used:

- PyTorch
- Transformers
- NumPy
- Pandas
- OpenCV
- Scikit-learn
   - A fully connected layer predicts the credibility label.

