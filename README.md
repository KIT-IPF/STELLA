# STELLA - obSTaclE, occLusion and visibiLity constrAins benchmark dataset
[<img src="https://github.com/sqirrel3/STELLA/blob/main/imgs/window-trajectory.png" width="410"/>](window-trajectory.png)
[<img src="https://github.com/sqirrel3/STELLA/blob/main/imgs/vegetation-trajectory.png" width="410"/>](vegetation-trajectory.png)

We introduce a new benchmark dataset [STELLA](https://drive.google.com/drive/folders/1eYkUXY6tKA08b9FMoWVC-mj5Zl4VFN_t?usp=sharing) (obSTaclE, occLusion and visibiLity constrAins) for image-based 3D reconstruction. The dataset consists of real-world challenging scenarios concerning transparent and non-transparent obstacles. The object behind obstacles is 0.7m tall Buddha statue placed on a rectangular plate. Both scenarios are captured using high resolution digital camera. The images are captured in a circular trajectory and each scenario contains 125 images. The ground truth data in the form of a mesh with 0.1mm accuracy is obtained using Structured Light.

<p align="center">
 <img src="https://github.com/sqirrel3/STELLA/blob/main/imgs/ground-truth-mesh.gif" width="330"/>
</p>

> [**Vision through obstacles - 3D geometric reconstruction and evaluation of Neural Radiance Fields (NeRFs)**](https://isprs-archives.copernicus.org/articles/XLVIII-1-W3-2023/153/2023/) <br />
> **Ivana Petrovska and Boris Jutzi**

### Citation and License
```
@inproceedings{nerfstudio,
	title        = {Vision through obstacles - 3D geometric reconstruction and evaluation of Neural Radiance Fields (NeRFs)},
	author       = {Ivana Petrovska and Boris Jutzi},
	year         = 2023,
	booktitle    = {ACM SIGGRAPH 2023 Conference Proceedings},
	series       = {SIGGRAPH '23}
}

```

The provided data is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).
