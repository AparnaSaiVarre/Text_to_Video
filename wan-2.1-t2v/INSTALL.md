# INSTALL.md

# Installation Instructions for WAN 2.1 T2V Setup

This guide explains how to set up **WAN 2.1 T2V** with ComfyUI and Diffusion-Pipe for local usage.

## 1. WAN 2.1 T2V Models

Download the pretrained WAN 2.1 T2V models from Hugging Face:  

- **WAN 2.1 T2V 1.3B**: [https://huggingface.co/Wan-AI/Wan2.1-T2V-1.3B/tree/main](https://huggingface.co/Wan-AI/Wan2.1-T2V-1.3B/tree/main)  
- **ComfyUI Repackaged WAN 2.1**: [https://huggingface.co/Comfy-Org/Wan_2.1_ComfyUI_repackaged](https://huggingface.co/Comfy-Org/Wan_2.1_ComfyUI_repackaged)

> Download the model files (e.g., `.safetensors`) and place them in your ComfyUI `models` folder.

---

## 2. ComfyUI Installation

ComfyUI is the GUI for running T2V models:  

- Repository: [https://github.com/comfyanonymous/ComfyUI](https://github.com/comfyanonymous/ComfyUI)  

**Steps:**

```bash
git clone https://github.com/comfyanonymous/ComfyUI
cd ComfyUI
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
pip install -r requirements.txt



