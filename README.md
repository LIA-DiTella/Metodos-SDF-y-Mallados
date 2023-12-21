# Metodos-SDF-y-Mallados

| Método | Representación | Arquitectura | Input Generador  |
|--------|----------------|--------------|-------|
| StyleSDF \[[CVPR22](https://stylesdf.github.io/)] | NSDF  | MLP + GAN | Imagen 2D |
| Get3D \[[NeurIPS22](https://research.nvidia.com/labs/toronto-ai/GET3D/)] | Mesh | MLP + CNNs | Vectores Latentes |
| Next3D \[[CVPR23](https://mrtornado24.github.io/Next3D/)] | Tri-Plane | GAN | Imagen 2D |
| Mezghanni \[[CVPR21](https://openaccess.thecvf.com/content/CVPR2021/html/Mezghanni_Physically-Aware_Generative_Network_for_3D_Shape_Modeling_CVPR_2021_paper.html)] | ? | GAN | Vector Latente |
| MeshGPT \[[Link](https://nihalsid.github.io/mesh-gpt/)] | Mesh | Transformer | ? |
| One-2-3-45 \[[Link](https://one-2-3-45.github.io/)] | Mesh | Diffusion | Imagen 2D |
| Control3Diff \[[3DV24](https://jiataogu.me/control3diff/)] | Mesh | Diffusion | Imagen 2D |
| DreamCraft3D \[[Link](https://mrtornado24.github.io/DreamCraft3D/)] | Mesh | Diffusion | Prompt |
| MeshDiffusion \[[ICLR23](https://mrtornado24.github.io/DreamCraft3D/)] | Mesh | Diffusion | Prompt |
| SLIDE \[[CVPR23](https://slide-3d.github.io/)] | Mesh | Diffusion | ? |
| Magic3D \[[CVPR23](https://research.nvidia.com/labs/dir/magic3d/)] | Mesh | Diffusion | Prompt |
| Fantasia3D \[[ICCV23](https://fantasia3d.github.io/)] | DMTet | Diffusion | Prompt |
| LRM \[[ArXiv](https://yiconghong.me/LRM/)] | Tri-plane / NERF-rendered | Transformer E-D | Imagen 2D |
| DMV3D \[[ArXiv](https://justimyhxu.github.io/projects/dmv3d/)] | Tri-plane / NERF-rendered | Transformer/Diffusion | Varias samples de ruido 2D |
| Instant3D \[[ArXiv](https://jiahao.ai/instant3d/)] | Tri-plane / NERF-rendered | Diffusion | Prompt |
| ZeroNVS \[[ArXiv](https://kylesargent.github.io/zeronvs/)] | No entendi | Diffusion | Imagen 2D |
| HoloDiffusion \[[CVPR23](https://holodiffusion.github.io/)] | Features voxelizadas + MLP | Diffusion | No entendi - pareciera ser ruido voxelizado |
| HoloFusion \[[ICCV23](https://holodiffusion.github.io/holofusion/)] | Features voxelizadas| Diffusion | No entendi - pareciera ser ruido voxelizado |
| Text2Room \[[ICCV23](https://holodiffusion.github.io/holofusion/)] | Features voxelizadas| Diffusion | No entendi - pareciera ser ruido voxelizado |
| HyperDiffsuion \[[ICCV23](https://ziyaerkoc.com/hyperdiffusion/)] | MLP overfiteada | Diffusion | Ruido 1D |

