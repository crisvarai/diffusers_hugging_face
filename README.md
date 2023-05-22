# diffusers_hugging_face

---
license: mit
tags:
- pytorch
- diffusers
- unconditional-image-generation
- diffusion-models-class
---

## Usage

```python
from diffusers import DDPMPipeline
pipeline = DDPMPipeline.from_pretrained('crisrv/sd-class-butterflies-32px')
image = pipeline().images[0]
image
```
