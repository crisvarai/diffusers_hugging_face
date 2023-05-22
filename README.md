# diffusers_hugging_face

Diffusers is the go-to library for state-of-the-art pretrained diffusion models for generating images, audio, and even 3D structures of molecules. 
---

## Usage

```python
from diffusers import DDPMPipeline
pipeline = DDPMPipeline.from_pretrained('crisrv/sd-class-butterflies-32px')
image = pipeline().images[0]
image
```
