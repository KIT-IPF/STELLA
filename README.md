# STELLA - obSTaclE, occLusion and visibiLity constrAins benchmark dataset
[<img src="https://github.com/sqirrel3/STELLA/blob/main/imgs/window-trajectory.png" width="400"/>](window-trajectory.png)
[<img src="https://github.com/sqirrel3/STELLA/blob/main/imgs/vegetation-trajectory.png" width="400"/>](vegetation-trajectory.png)

We introduce a new benchmark dataset [STELLA](https://drive.google.com/drive/folders/1eYkUXY6tKA08b9FMoWVC-mj5Zl4VFN_t?usp=sharing) (obSTaclE, occLusion and visibiLity constrAins) for image-based 3D reconstruction. The dataset consists of real-world challenging scenarios concerning transparent and non-transparent obstacles. The object behind obstacles is 0.7m tall Buddha statue placed on a rectangular plate. Both scenarios are captured using high resolution digital camera. The images are captured in a circular trajectory and each scenario contains 125 images.

![Ground-Truth](https://github.com/sqirrel3/STELLA/blob/main/imgs/sil-mesh.gif)
[<img src="https://github.com/sqirrel3/STELLA/blob/main/imgs/sil-mesh.gif" width="400"/>]
The ground truth data in the form of a mesh with 0.1mm accuracy is obtained using Structured Light.

[Petrovska I.](https://isprs-archives.copernicus.org/articles/XLVIII-1-W3-2023/153/2023/)

### Citation

`@Article{isprs-archives-XLVIII-1-W3-2023-153-2023, title={Geometric accuracy analysis between neural radiance fields (NeRFs) and Terrestrial Laser Scanning (TLS)}, author={Petrovska, I. and J\"ager, M. and Haitz, D. and Jutzi, B.}, year={2023}, journal={The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences}, volume= {XLVIII-1/W3-2023}, pages={153--159} }`

```
@inproceedings{nerfstudio,
	title        = {Nerfstudio: A Modular Framework for Neural Radiance Field Development},
	author       = {
		Tancik, Matthew and Weber, Ethan and Ng, Evonne and Li, Ruilong and Yi, Brent
		and Kerr, Justin and Wang, Terrance and Kristoffersen, Alexander and Austin,
		Jake and Salahi, Kamyar and Ahuja, Abhik and McAllister, David and Kanazawa,
		Angjoo
	},
	year         = 2023,
	booktitle    = {ACM SIGGRAPH 2023 Conference Proceedings},
	series       = {SIGGRAPH '23}
}

```
