# Image AI Workflows

The following are my notes on AI image generation.  This is focused on [ComfyUI](https://github.com/comfyanonymous/ComfyUI) as the workflow processor.  This is a documentation to try and demystify and simplify some of the generation.  Right now this is focused on SDXL based models, but maybe expanded to Flux, WAN, QWEN, etc in the future as time and understanding permits.

These examples are not perfect or ground breaking. They are designed to show how things can operate, how to have some level of control, and how to tackle prompt adherence issues. 

An attempt will be made to give basic description of what each node does, checkpoint/model links, any Custom Nodes used, and the example outputs will include the embeded workflows so you can jumpstart in testing.

Lastly, I will try to be platform agnostic as possible. However, I run on a Mac and therefore FP8 and FP4 workflows are closed to me at this point.  So don't expect anything discussion of that nature.  For workflows that use FP8 I will switch over to FP16 GGUF versions.  This may not be optimal for other platforms, and if at some point I decide on buying NVIDIA based hardware I will update the workflows with what feels to be optimial for them.

## SDXL Workflow Discussions

* [Basic Workflow](SDXL/SD-Workflows-Basic.md)
* [ControlNet Workflow](SDXL/SD-Workflows-ControlNet.md)
* Lora Workflow
* IP Adaptor Plus Workflow
* Hand Fixing Workflow
* Face Detailer Workflow
* Upscaling Workflow
* Batch Generation Workflow
* Multi-Lora Scheduling Workflow
* Multi-Character Scheduling Workflow
* Multi-Generation Layering Workflow

## Qwen Image/Edit Workflow Discussions
* [Basic Workflow](Qwen/Qwen-Workflows-Basic.md)
* [Edit Workflow](Qwen/Qwen-Edit-Workflows-Basic.md)

## Hunyuan3D Workflow Discussions

* Basic Workflow

## Flux Kontext Workflow Discussions

* Basic Workflow (Discussion)
* Text Replacement Workflow
* Syle Transfer Workflow
* Clothing Transfer Workflow
* Pose Trasnfer Workflow

## Custom Node for Third Party Tools Workflow Discussions

* ComfyUI-Blender (Blender to ComfyUI) Workflow
* Discomfort (Commandline tool) Workflow
