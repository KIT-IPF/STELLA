# STELLA - obSTaclE, occLusion and visibiLity constrAints dataset
[<img src="https://github.com/sqirrel3/STELLA/blob/main/imgs/no-obstacle-trajectory.png" width="260"/>](no-obstacle-trajectory.png)
[<img src="https://github.com/sqirrel3/STELLA/blob/main/imgs/window-trajectory.png" width="260"/>](window-trajectory.png)
[<img src="https://github.com/sqirrel3/STELLA/blob/main/imgs/vegetation-trajectory.png" width="260"/>](vegetation-trajectory.png)
[<img src="https://github.com/sqirrel3/STELLA/blob/main/imgs/noflash-trajectory.png" width="260"/>](noflash-trajectory.png)
[<img src="https://github.com/sqirrel3/STELLA/blob/main/imgs/flash-trajectory.png" width="260"/>](flash-trajectory.png)


We introduce a new dataset [STELLA](https://drive.google.com/file/d/1W6-KVcHWlxLwdm6A1X3fVWYbFryTZV2c/view?usp=drive_link) (obSTaclE, occLusion and visibiLity constrAints) for image-based 3D reconstruction. The dataset consists of real-world challenging scenarios concerning transparent (glass), non-transparent (vegetation) and semi-transparent (rain) occlusions captured uder diffuse and direct lighting. For comparability we also include a scenario without visibility obstructions (*Original*). Moreover, The object behind obstacles is 0.7m tall Buddha statue placed on a rectangular plate. The images are captured using high resolution digital camera in a circular trajectory and each scenario contains 125 images. Excluding certain image parts and investigating how different occlusion level affect the geometric reconstruction, we consider binary masks with different occlusion coverage. The ground truth mesh with 0.1mm accuracy is obtained using Structured Light.

<p align="center">
 <img src="https://github.com/sqirrel3/STELLA/blob/main/imgs/ground-truth-mesh.gif" width="250"/>
</p>

### Papers

> [**Vision through obstacles - 3D geometric reconstruction and evaluation of Neural Radiance Fields (NeRFs)**](https://www.mdpi.com/2072-4292/16/7/1188) <br />
> **Ivana Petrovska and Boris Jutzi**

> [**Seeing beyond vegetation: A comparative occlusion analysis between Multi-View Stereo, Neural Radiance Fields and Gaussian Splatting for 3D reconstruction**](https://doi.org/10.1016/j.ophoto.2025.100089) <br />
> **Ivana Petrovska and Boris Jutzi**

> [**Impact of Rain on 3D Reconstruction with Multi-View Stereo, Neural Radiance Fields and Gaussian Splatting**](https://doi.org/10.5194/isprs-annals-X-4-W6-2025-169-2025) <br />
> **Ivana Petrovska and Boris Jutzi**

> [**Novel View Synthesis Under Rainy Conditions with Neural Radiance Fields and Gaussian Splatting**](https://doi.org/10.5194/isprs-annals-XI-1-2026-17-2026) <br />
> **Ivana Petrovska and Boris Jutzi**

> [**SGS: Shadow-aware Gaussian Splatting**](https://doi.org/10.1016/j.ophoto.2026.100151) <br />
> **Ivana Petrovska, Daniel Rebain, Lukas Winiwarter and Boris Jutzi**

### Citation and License
```
@article{petrovska2024vision,
  title={Vision through Obstacles—3D Geometric Reconstruction and Evaluation of Neural Radiance Fields (NeRFs)},
  author={Petrovska, Ivana and Jutzi, Boris},
  journal={Remote Sensing},
  volume={16},
  number={7},
  pages={1188},
  year={2024},
  publisher={MDPI}
}
```

```
@article{petrovska2025seeing,
  title={Seeing beyond vegetation: A comparative occlusion analysis between Multi-View Stereo, Neural Radiance Fields and Gaussian Splatting for 3D reconstruction},
  author={Petrovska, Ivana and Jutzi, Boris},
  journal={ISPRS Open Journal of Photogrammetry and Remote Sensing},
  pages={100089},
  year={2025},
  publisher={Elsevier}
}
```

```
@article{petrovska2025impact,
  title={Impact of Rain on 3D Reconstruction with Multi-View Stereo, Neural Radiance Fields and Gaussian Splatting},
  author={Petrovska, Ivana and Jutzi, Boris},
  journal={ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences},
  volume={10},
  pages={169--176},
  year={2025},
  publisher={Copernicus GmbH}
}
```

```
@article{petrovska2026novel,
  title={Novel View Synthesis Under Rainy Conditions with Neural Radiance Fields and Gaussian Splatting},
  author={Petrovska, Ivana and Jutzi, Boris},
  journal={ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences},
  volume={11},
  pages={17--24},
  year={2026},
  publisher={Copernicus Publications G{\"o}ttingen, Germany}
}
```

```
@article{petrovska2026sgs,
  title={SGS: Shadow-Aware Gaussian Splatting},
  author={Petrovska, Ivana and Rebain, Daniel and Winiwarter, Lukas and Jutzi, Boris},
  journal={ISPRS Open Journal of Photogrammetry and Remote Sensing},
  pages={100151},
  year={2026},
  publisher={Elsevier}
}
```

The provided data is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).
