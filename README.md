
# Hand-drawn Anime Style LoRA Expand

This project provides a LoRA model based on SDXL, designed to generate images in a specific hand-drawn anime and manga-inspired style.

![example.jpg](https://s2.loli.net/2025/02/14/Gc2Yevg37z5jPFm.jpg)

---

## Table of Contents

- [Overview](#overview)
- [Introduction](#introduction)
- [Features](#features)
- [Usage](#usage)
- [Project Structure](#project-structure)

---

## Overview

**Hand-drawn Anime Style LoRA Expand** is an SDXL-based LoRA project for generating images with a distinctive hand-drawn anime illustration style.

The project includes the trained LoRA model, training dataset, training script, and a Gradio-based Web UI for online image generation and style transfer.

---

## Introduction

This project fine-tunes **SDXL** using the **LoRA** technique, enabling the model to generate images with a customized hand-drawn manga and anime aesthetic.

In addition, the project integrates **LCM-LoRA** to accelerate inference, allowing high-quality image generation within approximately seven inference steps.

The project also supports **IP-Adapter**, which enables users to upload reference images and transfer them into the target hand-drawn anime style.

A **Gradio Web UI** is provided to make the model easy to use through an interactive web application.

---

## Features

- SDXL-based LoRA model for hand-drawn anime-style image generation
- Customized manga-inspired visual style
- LCM-LoRA support for fast image generation
- IP-Adapter support for image-guided style transfer
- Gradio-based Web UI for convenient online interaction
- Includes dataset and training script for LoRA fine-tuning

---

## Usage

Clone this repository:

```bash
git clone https://github.com/zyjOrz/Hand-drawn-Anime-Style-LoRA.git
cd Hand-drawn-Anime-Style-LoRA
````

---

## Project Structure

* `dataset`
  The dataset used for training the LoRA model.

* `train_text_to_image_lora_sdxl.py`
  The training script used to fine-tune the SDXL LoRA model.

* `gradio_ip.py`
  The backend script for the AI web application. It integrates IP-Adapter and LCM-LoRA for reference-image-based style transfer and accelerated inference.

---

## Demo

The following image shows the Gradio-based Web UI of the project:

![demo.png](https://s2.loli.net/2025/02/18/2lxh79jFtPSkDdN.png)

```

