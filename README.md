# STELLA - obSTaclE, occLusion and visibiLity constrAints dataset
[<img src="https://github.com/sqirrel3/STELLA/blob/main/imgs/no-obstacle-trajectory.png" width="260"/>](no-obstacle-trajectory.png)
[<img src="https://github.com/sqirrel3/STELLA/blob/main/imgs/window-trajectory.png" width="260"/>](window-trajectory.png)
[<img src="https://github.com/sqirrel3/STELLA/blob/main/imgs/vegetation-trajectory.png" width="260"/>](vegetation-trajectory.png)

We introduce a new dataset [STELLA](https://drive.google.com/file/d/1cxkB6OB_vUkszVOANeU8848njFiuxY2W/view?usp=drive_link) (obSTaclE, occLusion and visibiLity constrAints) for image-based 3D reconstruction. The dataset consists of real-world challenging scenarios concerning transparent (*Window*) and non-transparent (*Vegetation*) obstacles. For comparability and assessing the impact of occlusions to the pose estimation we also include a scenario without visibility obstructions (*Original*). The object behind obstacles is 0.7m tall Buddha statue placed on a rectangular plate. All scenarios are captured using high resolution digital camera in a circular trajectory and each scenario contains 125 images. The ground truth data in the form of a mesh with 0.1mm accuracy is obtained using Structured Light.

<p align="center">
 <img src="https://github.com/sqirrel3/STELLA/blob/main/imgs/ground-truth-mesh.gif" width="250"/>
</p>

> [**Vision through obstacles - 3D geometric reconstruction and evaluation of Neural Radiance Fields (NeRFs)**](https://www.mdpi.com/2072-4292/16/7/1188) <br />
> **Ivana Petrovska and Boris Jutzi**

### Citation and License
```
@Article{rs16071188,
AUTHOR = {Petrovska, Ivana and Jutzi, Boris},
TITLE = {Vision through Obstacles—3D Geometric Reconstruction and Evaluation of Neural Radiance Fields (NeRFs)},
JOURNAL = {Remote Sensing},
VOLUME = {16},
YEAR = {2024},
NUMBER = {7},
ARTICLE-NUMBER = {1188},
ISSN = {2072-4292}
}

```

The provided data is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).
