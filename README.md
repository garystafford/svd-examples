# Stability AI Stable Video Diffusion XT 1.1 Examples

All videos I created here were with [Stability AI](https://stability.ai/stable-video)ʼs Stable Video Diffusion XT 1.1 Image-to-Video latent diffusion model (SVD XT 1.1), available on [Hugging Face](https://huggingface.co/stabilityai/stable-video-diffusion-img2vid-xt-1-1). Videos were created on Amazon Web Services (AWS) from single images using the SVD XT 1.1 model and [ComfyUI](https://github.com/comfyanonymous/ComfyUI) on a G4dn instance, powered by NVIDIA T4 GPUs. The videos were rendered as MP4 files with recommended 25 frames at an average of 9 fps and a resolution of 1,024 x 576 pixels. The videos were also rendered as [WebP](https://developers.google.com/speed/webp) format files (or in some cases, the MP4 files were then converted to WebP) for display in GitHub, shown below.

One of the best instructional videos I've seen on the subject of what is possible with SVD, is [ComfyUI: Stable Video Diffusion (Workflow Tutorial)](https://www.youtube.com/watch?v=m-ZoxcYNWFg&list=LL&index=7), by ControlAltAI, on YouTube.

## Gated Model and Output
Note that SVD XT 1.1 is a 'Gated model', but, according to the Stable Video Diffusion 1.1 License Agreement, _"Derivative Work(s)" means (a) any derivative work of the Software Products as recognized by U.S. copyright laws and (b) any modifications to a Model, and any other model created which is based on or derived from the Model or the Model’s output._ __For clarity, Derivative Works do not include the output of any Model.__ <<<

## ComfyUI Workflow
The [ComfyUI](workflows/svd_xt_workflow.json) workflow is included in this repository. It creates both an MP4 and a WebP video file. This [workflow](https://comfyanonymous.github.io/ComfyUI_examples/video/) is based on the workflow referenced in the comments for the YouTube video, [Image2Video. Stable Video Diffusion Tutorial.](https://youtu.be/HOVYu2UbgEE?si=N65J15eWrnRh2jPj), by [Sebastian Kamph](https://www.youtube.com/@sebastiankamph).

![ComfyUI Workflow](comfy_ui_workflow.png)

## Wide-format Videos

<table>
   <tr>
      <td><img src="videos/red_car.webp" alt="Red Sports Car" width="512"/>
      </br><a href="https://www.pexels.com/photo/red-alfa-romeo-c4-on-road-near-trees-210019">Source image</a></td>
      <td><img src="videos/motorcycle_handlebars.webp" alt="Motorcycle Handlebars" width="512"/>
      </br><a href="https://www.pexels.com/photo/person-riding-motorcycle-on-road-2519371/">Source image</a></td>
   </tr>
   <tr>
      <td><img src="videos/couple_on_beach.webp" alt="Couple on Beach" width="512"/>
      </br><a href="https://www.shutterstock.com/image-photo/happy-romantic-middle-aged-couple-enjoying-352166360">Source image</a></td>
      <td><img src="videos/blue_car.webp" alt="Blue Sports Car" width="512"/>
      </br><a href="https://pxhere.com/en/photo/1551833">Source image</a></td>
   </tr>
   <tr>
      <td><img src="videos/motorcycle_racer.webp" alt="Skier" width="512"/>
      </br><a href="https://www.pexels.com/photo/rider-s-riding-on-gray-and-black-sports-bike-163210/">Source image</a></td>
      <td><img src="videos/skier.webp" alt="Skier" width="512"/>
      </br><a href="https://www.pexels.com/photo/man-using-ski-3193846/">Source image</a></td>
   </tr>
</table>

## Tall-format Videos

<table>
   <tr>
      <td><img src="videos/turkish_coffee.webp" alt="Turkish Coffee" width="387"/>
      </br><a href="https://www.pexels.com/photo/a-shot-of-steaming-pot-with-a-and-glass-with-a-beverage-10351409/">Source image</a></td>
      <td><img src="videos/pouring_champagne.webp" alt="Pouring Champagne" width="387"/>
      </br><a href="https://www.pexels.com/photo/close-up-of-beer-glass-against-black-background-255483/">Source image</a></td>
   </tr>
   <tr>
      <td><img src="videos/candle_2.webp" alt="Burning Candle" width="387"/>
      </br><a href="https://www.pexels.com/photo/white-candle-278823/">Source image</a></td>
      <td><img src="videos/colored_smoke_2.webp" alt="Colored Smoke" width="387"/>
      </br><a href="https://www.pexels.com/photo/red-smoke-illustration-604671/">Source image</a></td>
   </tr>
   <tr>
      <td><img src="videos/neon_ramen_cat.webp" alt="Neon Ramen Car" width="387"/>
      </br><a href="https://www.pexels.com/photo/gato-otaku-19138491//">Source image</a></td>
   </tr>
</table>
</br>

---

_The contents of this repository represent my viewpoints and not of my past or current employers, including Amazon Web Services (AWS). All third-party libraries, modules, plugins, and SDKs are the property of their respective owners._
