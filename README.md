<<<<<<< HEAD
=======
# Super Resolution Model
This project implements a CNN based image super-resolution model, designed to work with RGB images.

## 📐SRCNN Model Architecture
- Input: RGB low-resolution image  
- Layers:
  - Conv2D (64 filters, 3×3) + ReLU
  - Repeated Conv2D blocks with ReLU (configurable depth)
  - Final Conv2D (3 filters, 3×3)
  - Skip connection: input added back to output (residual learning)

## Dependencies
```bash
pip install tensorflow numpy opencv-python
```

## Reference
- **SRCNN** — Dong et al. (2014): [Paper](https://arxiv.org/abs/1501.00092)

## Why This Model May Not Be Enough

This model is a good starting point, but it still has some limitations:

- It has only a few layers, so it can’t learn very complex image details.
- It depends on bicubic upscaled images instead of learning how to upscale itself.
- It doesn’t use modern features like attention or advanced loss functions.
- The results may still look a bit blurry or soft, especially for real-world images.

### Why Make a Better Model?

Newer models like EDSR or ESRGAN:
- Learn to upscale more accurately
- Create sharper and more realistic images
- Use deeper layers and better training techniques

> This model is great for learning and small projects, but for best results, a more advanced model is recommended.

>>>>>>> 637831838be52ee10b1949b2e9ba2c0d5b57256c
