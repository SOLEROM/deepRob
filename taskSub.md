## planning

Embodied AI is the science and engineering of intelligent machines with a physical or virtual embodiment


operate in unstructured environments 
recognize objects, 
understand natural‑language instructions, 
and plan action

Vision models provide perception by mapping camera data into semantically rich features

LLMs interpret textual commands and perform high‑level reasoning

combine these models on edge devices to perform tasks they were never explicitly trained for.


vision‑language‑action (VLA) frameworks that unify perception and language understanding


quantization, model partitioning and efficient architectures


### models

* PaLM‑E, RT‑2 - considerable computational resources and are typically cloud-based.
* for edge  - Fast, Data-Efficient Vision-Language-Action Models for Robotic Manipulation
    * EdgeVLA -  (30–50 Hz) on low‑power devices (SigLIP and DINOv2 for vision and Qwen2‑0.5B for language)
    * TinyVLA -  outperforms OpenVLA in both speed and task success with only ~50 M parameters (FastViT / 128‑dim language encoder)
    * llama_ros  (Quantized LLaMA)





    VLA enables perception-to-action via language, often through end-to-end learning.

    ACT provides a structured, reusable way to define and execute actions, which can be useful when you want modularity or transferability across tasks.

In some research, both are combined:

    VLA helps ground language into actions.

    ACTs define the low-level skills the agent can execute.