# AI Workflows

The following are my notes on AI image generation.  This is focused on [ComfyUI](https://github.com/comfyanonymous/ComfyUI) as the workflow processor.  This is a documentation to try and demystify and simplify some of the generation.  Right now this is focused on SD based models, but maybe expanded to Flux, WAN, etc in the future as time and understanding permits.

These examples are not perfect or ground breaking prompts. They are designed to show how things can operate, how to have some level control, and how to tackle prompt adherence issues. 

An attempt will be made to give basic description of what each node does, any Custom Nodes used, and the example outputs will include the embeded workflows so you can jumpstart in testing.

Lastly, I will try to be platform agnostic as possible. However, I run on a Mac and therefore FP8 and FP4 workflows are closed to me at this point.  So don't expect anything discussion of that nature.  For workflows that use FP8 I will switch over to FP16 GGUF versions.  This may not be optimal for other platforms, and if at some point I decide on buying NVIDIA based hardware I will update the workflows with what feels to be optimial for them.

## SD Workflow Discussions

* [Basic Workflow](SD-Workflows-Basic.md)
* [ControlNet Workflow](SD-Workflows-ControlNet.md)
* Lora Workflow
* IP Adaptor Plus Workflow

