# Exploring Diffusion: From MNIST Generation to Robotic Control

This repository collects a sequence of diffusion-model experiments that start with image generation on MNIST and extend to policy learning and trajectory generation for robotics.

## Repository structure

- `ddpm/` - DDPM experiments on MNIST, including linear and cosine noise schedules, training curves, and sampling artifacts.
- `ddim/` - DDIM experiments and sampling comparisons built on the MNIST setup.
- `diffusion_policy/` - visuomotor policy learning experiments based on action diffusion.
- `diffuser/` - trajectory diffusion and planning experiments, plus a large library of robot model assets and demo media.
- `data/` folders - cached datasets, checkpoints, and generated outputs used by each experiment.

### Main notebooks

- `ddpm/ddpm_test.ipynb`
- `ddim/ddim_test.ipynb`
- `diffusion_policy/diffusion_policy.ipynb`
- `diffuser/diffuser.ipynb`

## Papers cited

1. Ho, J., Jain, A., & Abbeel, P. (2020). Denoising diffusion probabilistic models. Advances in Neural Information Processing Systems, 33, 6840–6851.
2. Song, J., Meng, C., & Ermon, S. (2020). Denoising diffusion implicit models. arXiv preprint arXiv:2010.02502.
3. Janner, M., Du, Y., Tenenbaum, J., & Levine, S. (2022). Planning with diffusion for flexible behavior synthesis. arXiv preprint arXiv:2205.09991.
4. Chi, C., Xu, Z., Feng, S., Cousineau, E., Du, Y., Burchfiel, B., Tedrake, R., & Song, S. (2025). Diffusion policy: Visuomotor policy learning via action diffusion. The International Journal of Robotics Research, 44(10–11), 1684–1704.
5. Perez, E., Strub, F., De Vries, H., Dumoulin, V., & Courville, A. (2018). FiLM: Visual reasoning with a general conditioning layer. In Proceedings of the AAAI Conference on Artificial Intelligence.
6. Dhariwal, P., & Nichol, A. (2021). Diffusion models beat GANs on image synthesis. Advances in Neural Information Processing Systems, 34, 8780–8794.

## Notes

- The MNIST experiments focus on diffusion schedules, denoising behavior, and sample quality.
- The robotics sections show how diffusion methods can be adapted for planning and policy learning.
- Check the notebooks for training details, visuals, and experiment-specific outputs.
