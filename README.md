# Stable Diffusion XL 1.0 Experiments

![](example5.webp)

Jupyter Notebooks for experimenting with Stable Diffusion XL 1.0 and the [sdxl-wrong-lora](https://huggingface.co/minimaxir/sdxl-wrong-lora). All these notebooks have been confirmed to [barely](https://twitter.com/minimaxir/status/1691156740111568896) work in Colab on a T4 GPU.

These notebooks include:

- [SDXL 1.0 Image Generation](sdxl_image_generation.ipynb) ([Colab](https://colab.research.google.com/github/minimaxir/sdxl-experiments/blob/main/sdxl_image_generation.ipynb)): A notebook for general SDXL 1.0 image generation, including the refiner, compel syntax, and the `sdxl-wrong-lora` for improved image quality.
- [sdxl-wrong-lora Comparison](sdxl_wrong_comparison.ipynb) ([Colab](https://colab.research.google.com/github/minimaxir/sdxl-experiments/blob/main/sdxl_wrong_comparison.ipynb)): A notebook to generate images with and without the `sdxl-wrong-lora` for comparison.
- [Wrong Image Generator](wrong_image_generator.ipynb) ([Colab](https://colab.research.google.com/github/minimaxir/sdxl-experiments/blob/main/wrong_image_generator.ipynb)): A notebook to generate synthetic "negative" images for training the `sdxl-wrong-lora` Dreambooth LoRA.

## Maintainer/Creator

Max Woolf ([@minimaxir](https://minimaxir.com))

_Max's open-source projects are supported by his [Patreon](https://www.patreon.com/minimaxir) and [GitHub Sponsors](https://github.com/sponsors/minimaxir). If you found this project helpful, any monetary contributions to the Patreon are appreciated and will be put to good creative use._

## License

MIT
