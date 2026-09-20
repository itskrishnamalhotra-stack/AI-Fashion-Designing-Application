# AI Fashion Designing Application

A Colab-based generative-AI prototype for transforming fashion concepts with an image-inpainting workflow and an interactive web interface.

> Built in 2024 as an experimental applied-AI project.

## What it demonstrates

- Prompt-guided fashion image editing
- Mask-based inpainting and visual transformation
- A notebook-first workflow designed for Google Colab
- Integration of model inference with a browser-based interface

## Tech stack

Python · Jupyter · Google Colab · Diffusers · PyTorch · Image Inpainting

## Project structure

```text
fashion_designing.ipynb   # Complete Colab workflow
README.md                 # Project overview and results
```

## Running the project

1. Open `fashion_designing.ipynb` in Google Colab.
2. Select a GPU runtime.
3. Run the cells in order.
4. Upload an input image, create or select a mask, and enter the desired fashion prompt.

Model availability and dependency versions may have changed since the original build, so the notebook may require updated package versions or a newer compatible checkpoint.

## Results

| Input and editing workflow | Generated fashion concepts |
| --- | --- |
| ![Fashion workflow](https://github.com/user-attachments/assets/9eeb5829-6683-43e0-91c2-5b1065a54126) | ![Fashion result](https://github.com/user-attachments/assets/490daaa3-9e62-4536-b6ac-9a01e2b972e6) |
| ![Fashion example](https://github.com/user-attachments/assets/f37895f4-4565-4312-998a-e4b3aeeca648) | ![Fashion output](https://github.com/user-attachments/assets/960d1fa7-6008-4b13-9f91-1b9c9c42b992) |

<details>
<summary>Additional screenshot</summary>

![Additional project screenshot](https://github.com/user-attachments/assets/73704398-e7c7-4bf5-aaa6-3a01e2b972e6)

</details>

## Status

Portfolio prototype. The repository preserves the original notebook and visual results; it is not currently packaged as a production service.
