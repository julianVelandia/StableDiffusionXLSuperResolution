# StableDiffusionXLSuperResolution

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/julianVelandia/StableDiffusionXLSuperResolution/blob/master/StableDiffusionAutoDownloader.ipynb)


This project generates ultra-realistic images using *Stable Diffusion XL* and enhances them with super-resolution through *Real-ESRGAN*.

## Usage
A preconfigured Colab notebook is provided, requiring GPU access. Simply load it, run the cells, and generate images from textual descriptions.

![image](https://github.com/user-attachments/assets/a5587db2-53ae-4100-96be-b21c538bb292)

- "A vibrant carnival at night, with colorful lights illuminating Ferris wheels, carousels, and food stalls, children laughing, and a fireworks display lighting up the starry sky, ultra-realistic."

![super_resolved_image_1_A_vibrant_carnival_at_night__w_1426 (1)](https://github.com/user-attachments/assets/56747153-6cdd-4155-8072-580b5be8d0b7)

- "An alien jungle filled with luminescent plants and strange creatures, with a glowing waterfall cascading into a turquoise pool, surreal and otherworldly."

![super_resolved_image_2_An_alien_jungle_filled_with_to_4146 (1)](https://github.com/user-attachments/assets/c2da4fd0-f5fd-4eb8-ac4b-33989a1fb8a9)

## Running Without Super-Resolution

<img src="https://github.com/user-attachments/assets/db25381f-7542-4013-9c3c-d0e1671a744a" alt="Image without super-resolution" width="600"/>

<img src="https://github.com/user-attachments/assets/58701c21-2d11-4a47-9b40-06366322a055" alt="Image with super-resolution"/>



```python
generate_and_save_image(
    pipeline, 
    prompt=prompt, 
    super_resolution=False, 
    width=1024, 
    height=576
)
```
