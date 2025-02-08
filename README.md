# Handwriting to Markdown 
Small project to turn handwritten notes into Markdown format notes with LaTeX math notation.

Encodes handwritten images using a Visual Transformer into a latent vector, decodes using Latural Language decoder.

## Setup
Assuming target system has CUDA capable graphics card with CUDA toolkit, python3-pip, python3-venv, installed 

### Start venv, install requirements
```python3 -m venv .venv```
```source .venv/bin/activate```
```pip install -r requirements.txt```