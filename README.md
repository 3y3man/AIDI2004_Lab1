# Project Report: Interactive NLP and Image Classification Application
## Overview
This project demonstrates the integration of HuggingFace Transformers and Gradio.io to create interactive applications for machine translation (English - Japanese) and image classification.
## Components
### Library Installation:
-	`gradio` for web app interfaces.
-	`accelerate` for enhanced computational performance. (used for the image classification operation)
### Translation:
-	Utilizes "Helsinki-NLP/opus-tatoeba-en-ja" and "Helsinki-NLP/opus-mt-ja-en" models for English-Japanese translations.
-	Features a Gradio web interface allowing users to translate text between English and Japanese.
### Image Classification:
-	Implements the "microsoft/resnet-50" model for classifying images.
-	Includes a Gradio interface where users upload images for classification, with results displayed in JSON format.
