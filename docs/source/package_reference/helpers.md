<!--⚠️ Note that this file is in Markdown but contain specific syntax for our doc-builder (similar to MDX) that may not be
rendered properly in your Markdown viewer.
-->

# Helper methods

A collection of helper functions for PEFT.

## Checking if a model is a PEFT model

[[autodoc]] helpers.check_if_peft_model
    - all

## Temporarily Rescaling Adapter Scale in LoraLayer Modules

[[autodoc]] helpers.rescale_adapter_scale
    - all

## Context manager to disable input dtype casting in the `forward` method of LoRA layers

[[autodoc]] helpers.disable_input_dtype_casting
    - all
