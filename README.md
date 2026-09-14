# Luca Brembilla

PhD researcher at Politecnico di Milano, working on perception and machine learning systems for autonomous driving.

## Current work

My work sits between **3D perception, representation learning, and efficient model deployment**. I am particularly interested in understanding what perception models learn, and in making modern architectures run efficiently on real hardware.

Current work includes:

* self-supervised representation learning for LiDAR and 3D perception;
* sparse and transformer-based perception models;
* model compilation and inference optimization with CUDA and TensorRT;
* deployment of autonomous-driving perception systems on embedded and automotive hardware.

## Selected work

**[What Does the Future Buy?](https://lucabrembilla.dev/projects/what-does-the-future-buy)**

An investigation of future-prediction objectives for LiDAR self-supervised learning. The study separates the effects of latent projection and future supervision, and analyzes what information becomes linearly accessible in the learned representation.

**[DriveRT](https://lucabrembilla.dev/projects/drivert)**

A compiler and runtime for autonomous-driving models, with a focus on sparse 3D networks and end-to-end GPU execution. It compiles preprocessing, sparse backbones, dense heads, and postprocessing into a unified runtime, with graph-level optimizations that exploit model semantics rather than only individual kernels.

**[Adaptive Point Cloud Cropping](https://lucabrembilla.dev/projects/thesis)**

A temporal point-cloud reduction method for efficient 3D object detection on embedded hardware, developed during my MSc thesis and evaluated on an NVIDIA Jetson AGX Orin.

## Previous work

Before starting my PhD, I worked as a Research Engineer in the
[AIDA Group](https://aida.polimi.it) at Politecnico di Milano on LiDAR and
camera perception, CUDA and TensorRT optimization, ROS 2 integration, and
deployment on autonomous vehicles. Some of the perception software I developed
there was later transferred to [NiuLinx](https://www.niulinx.ai/).

More details and publications are available at
[lucabrembilla.dev](https://lucabrembilla.dev).
