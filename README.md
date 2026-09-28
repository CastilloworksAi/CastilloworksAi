# Hey, I'm Castillo

I build AI tools out of Texas, and almost all of it runs on my own machine. No cloud bills, no data leaving the house.

Most of what's here started as something I needed for my own work: image pipelines, LoRA training, voice cloning, a local chat app, and a pile of terminal tools I use every day.

## The rig

Everything in these repos is built and tested on this box:

| Part | What I run |
|---|---|
| CPU | AMD Ryzen 9 9900X (12 cores) |
| GPU | NVIDIA RTX 5080, 16 GB (Blackwell) |
| RAM | 96 GB DDR5-6000 (2x 48 GB) |
| Board | Gigabyte X870E AORUS ELITE WIFI7 |
| Storage | 2x 4 TB Kingston Fury Renegade NVMe (Gen4), 2 TB WD external |
| OS | Ubuntu 24.04 LTS, kernel 7.0 |
| Driver | NVIDIA 580.178 (CUDA 13.0) |
| PyTorch | 2.11 + cu128 |

Software on top: ComfyUI for images, Ollama for local LLMs, Claude Code for building.
Nothing AI starts at boot. I turn each service on when I need it.

## Tools

| Repo | What it does |
|---|---|
| [imagine](https://github.com/CastilloworksAi/imagine) | Type a prompt in the terminal, get a PNG. A small CLI for ComfyUI |
| [headshot](https://github.com/CastilloworksAi/headshot) | Selfie in, studio headshots out, on your own GPU |
| [clone](https://github.com/CastilloworksAi/clone) | Local voice cloning with Chatterbox. No per-character fees |
| [grab](https://github.com/CastilloworksAi/grab) | Download video or audio from the web with one word |
| [broll](https://github.com/CastilloworksAi/broll) | Terminal B-roll for screen recordings. Pure bash |
| [terminal-fun](https://github.com/CastilloworksAi/terminal-fun) | Random terminal animations for recording content |

## Image models and training

| Repo | What it does |
|---|---|
| [comfyui-workflows](https://github.com/CastilloworksAi/comfyui-workflows) | My ComfyUI workflows: Flux, SDXL, LoRA training, captioning |
| [z-image-turbo-comfy](https://github.com/CastilloworksAi/z-image-turbo-comfy) | One-command ComfyUI for Z-Image-Turbo on RTX 50-series cards |
| [lora-training-guide](https://github.com/CastilloworksAi/lora-training-guide) | Beginner guide, from raw images to a trained `.safetensors` |
| [lora-studio](https://github.com/CastilloworksAi/lora-studio) | Local web app for captioning datasets and exporting training jobs |
| [ai-workstation](https://github.com/CastilloworksAi/ai-workstation) | Setup scripts, backups, and model downloaders for this rig |

## Other stuff

| Repo | What it does |
|---|---|
| [block-buddies](https://castilloworks.ai/neuronest/play/) | Place-value number game for kids. Moved to castilloworks.ai, repo archived |
| [valet-trash-calculator](https://github.com/CastilloworksAi/valet-trash-calculator) | Profit calculator for a valet trash business |
| [killswitch](https://github.com/CastilloworksAi/killswitch) | Data wipe scripts for Linux, macOS, Windows, and ChromeOS. NUCLEAR tier is written and dry-runs by default; not yet run on live hardware |

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-121011?style=flat&logo=gnu-bash&logoColor=white)
![ComfyUI](https://img.shields.io/badge/ComfyUI-AI%20Pipelines-blueviolet?style=flat)
![Ollama](https://img.shields.io/badge/Ollama-Local%20LLMs-000000?style=flat)
![CUDA](https://img.shields.io/badge/CUDA-12.8-76B900?style=flat&logo=nvidia&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-24.04-E95420?style=flat&logo=ubuntu&logoColor=white)

---

*Based in Texas. More at [castilloworks.ai](https://castilloworks.ai).*
