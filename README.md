# Luca Brembilla

PhD researcher in Autonomous Driving.

[AIDA Group](https://aida.polimi.it) · [NiuLinx](https://www.niulinx.ai/) · Politecnico di Milano (DEIB)

I started working on autonomous-driving perception during my MSc. I was trying to make a
LiDAR detector run fast enough on an edge device, and ended up developing an adaptive crop
that removed half the points and doubled the frame rate. That work became my thesis and an
ICIAP 2025 paper.

After that, I joined AIDA's perception team. Most of my work sat between the model and the
vehicle: training 3D detectors, integrating them into ROS 2, and fixing the TensorRT and CUDA
pieces needed to run them in real time. A CUDA implementation of PointCloud2 unpacking, for
example, brought that step from 9 ms to 1.5 ms. Some of the perception software I wrote at
Politecnico di Milano was later transferred to NiuLinx.

Now I am doing a PhD with Matteo Corno and Giacomo Boracchi. I study self-supervised learning
for LiDAR and camera-LiDAR models. More specifically, I want to know what pre-training adds
to their representations, and how much of it is still useful after fine-tuning. Outside that
work, I am building [DriveRT](https://lucabrembilla.dev/projects/drivert), an open-source
compiler and runtime for sparse 3D detectors.

[Website](https://lucabrembilla.dev) ·
[CV](https://lucabrembilla.dev/docs/Brembilla_Luca_resume.pdf) ·
[LinkedIn](https://www.linkedin.com/in/lucabrembilla/) ·
[Email](mailto:luca.brembilla@polimi.it)
