# 🎨🧠 Stable Diffusion Generator

A multimodal generative AI application that transforms text prompts into **high-quality images** 🖼️ and **audio** 🔊 using **Stable Diffusion** models from 🤗 Hugging Face. Built with `diffusers`, `torch`, and `Gradio`, this project enables interactive and accessible content generation.

---

## 🚀 Features

- 🔁 **Text-to-Image Generation** with `StableDiffusionXLPipeline`
- 🔊 **Text-to-Audio Generation** using `StableAudioPipeline`
- ⚡ GPU-accelerated with PyTorch + CUDA
- 🌐 Gradio-based web UI for seamless user interaction
- 🎯 Example prompts for testing both audio and visual outputs

---

## 👨‍💻 Responsibilities

As part of this project, I was responsible for:

- Integrating Hugging Face models for both text-to-image and text-to-audio tasks
- Implementing two interactive Gradio interfaces
- Optimizing the inference pipelines for GPU performance
- Structuring notebooks for clarity and experimentation
- Designing example use cases and prompts
- Writing clean, reproducible code for public sharing

---

## 📈 Outcomes

- ✅ Successfully generated high-quality audio and image outputs using text prompts
- 🧪 Created a functional prototype for multimodal generation
- 🖼️ Designed an intuitive UI for testing and demonstrating results
- 🧰 Packaged project into a reusable and extensible notebook-based toolkit

---

## 📚 Learning Insights

- Gained hands-on experience with Hugging Face `diffusers` and model pipelines
- Explored different schedulers like `EulerDiscreteScheduler` to optimize outputs
- Learned efficient audio generation using `StableAudioPipeline` and `soundfile`
- Developed UI deployment experience through `gradio`
- Understood how prompts influence outputs in both visual and audio domains

---

## 🧠 Summary Comparison

| Feature                  | Text-to-Image                            | Text-to-Audio                            |
|--------------------------|------------------------------------------|------------------------------------------|
| 🤖 Model                 | `StableDiffusionXLPipeline`              | `StableAudioPipeline`                    |
| 🧩 Model Source          | `stabilityai/stable-diffusion-xl-base`   | `stabilityai/stable-audio-open-1.0`      |
| 🎯 Input                 | Prompt text                              | Prompt + negative prompt + duration      |
| 📤 Output                | Image (`.png`, PIL)                      | Audio (`.wav`, NumPy array)              |
| 💻 Interface             | Gradio UI                                | Gradio UI                                |
| 🚀 Runtime               | CUDA-accelerated via PyTorch             | CUDA-accelerated via PyTorch             |

---

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/stable-diffusion-generator.git
cd stable-diffusion-generator
```


## 🔐 Hugging Face Authentication

To use pre-trained models from Hugging Face:
1. [Create an account](https://huggingface.co/join) if you don't have one.
2. Run the following inside the notebook or terminal:
```python
from huggingface_hub import notebook_login
notebook_login()
```

---

## 🧪 Example Prompts

**Text-to-Image:**
> "A director filming a dramatic scene in the middle of a monsoon."

**Text-to-Audio:**
> "A baby crying loudly with heavy background noise."

---

## 🌐 Launch Gradio Interface

To run the web UI:
- For **image generation**, launch from `Stable Diffusion(Text-Image).ipynb`
- For **audio generation**, launch from `Stable Diffusion (Text-Audio).ipynb`

---


## 🙏 Thank You

Thank you for checking out **Stable Diffusion Generator**!  
Your interest in creative AI applications is what drives open innovation. Feel free to ⭐ star the repo, contribute, or share your outputs!

---
