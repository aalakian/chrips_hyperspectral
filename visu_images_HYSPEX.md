[Back to main page](index.md)

## Sensor : HYSPEX

<p align="center">
<img src="Complements/Legende_classif_ligne_v2.png" width="500" />
</p>

**Regularization** 

After CHRIPS processing, some pixels may be unclassified. A regularization process is then applied to try to classify them. A spatial constraint is applied: an unclassified pixel can be classified in a given class C if at least one pixel of its neighborhood, defined as a 5x5 square centered on P, belongs to the class C. Two types of regularization are proposed. 

 - **Safe regularization**: use of CHRIPS parameters with slightly modified thresholds for all classes 

 - **Raw regularization**:  use of CHRIPS parameters with slightly modified thresholds for classes with specific absorptions and spectral angle similarity (2 degrees) for other classes 

**France, Mauzac  -  size: 564 x 554**

<img src="Images/HYSPEX/Mauzac/HYSPEX_Mauzac_00_IMAGE.png" width="270" /> | <img src="Images/HYSPEX/Mauzac/HYSPEX_Mauzac_02_SAFE_REGUL.png" width="270" /> | <img src="Images/HYSPEX/Mauzac/HYSPEX_Mauzac_03_RAW_REGUL.png" width="270" />
:-: | :-: | :-:
&nbsp;&nbsp;Hyperspectral image: &nbsp;&nbsp;&nbsp; color composite | Classification map with safe regularization | Classification map with raw regularization

**France, Fauga  -  size: 1027 x 950**

<img src="Images/HYSPEX/Fauga08_NORD/HYSPEX_Fauga08_NORD_00_IMAGE.png" width="270" /> | <img src="Images/HYSPEX/Fauga08_NORD/HYSPEX_Fauga08_NORD_02_SAFE_REGUL.png" width="270" /> | <img src="Images/HYSPEX/Fauga08_NORD/HYSPEX_Fauga08_NORD_03_RAW_REGUL.png" width="270" />
:-: | :-: | :-:
&nbsp;&nbsp;Hyperspectral image: &nbsp;&nbsp;&nbsp; color composite | Classification map with safe regularization | Classification map with raw regularization

**France, Fauga - town  -  size: 241 x 303**

<img src="Images/HYSPEX/Fauga_town_XC/HYSPEX_Fauga_Town_Denoised_00_IMAGE.png" width="270" /> | <img src="Images/HYSPEX/Fauga_town_XC/HYSPEX_Fauga_Town_Denoised_02_SAFE_REGUL.png" width="270" /> | <img src="Images/HYSPEX/Fauga_town_XC/HYSPEX_Fauga_Town_Denoised_03_RAW_REGUL.png" width="270" />
:-: | :-: | :-:
&nbsp;&nbsp;Hyperspectral image: &nbsp;&nbsp;&nbsp; color composite | Classification map with safe regularization | Classification map with raw regularization

**France, Fauga - Fermat  -  size: 261 x 231**

<img src="Images/HYSPEX/Fermat/HYSPEX_Fermat_00_IMAGE.png" width="270" /> | <img src="Images/HYSPEX/Fermat/HYSPEX_Fermat_02_SAFE_REGUL.png" width="270" /> | <img src="Images/HYSPEX/Fermat/HYSPEX_Fermat_03_RAW_REGUL.png" width="270" />
:-: | :-: | :-:
&nbsp;&nbsp;Hyperspectral image: &nbsp;&nbsp;&nbsp; color composite | Classification map with safe regularization | Classification map with raw regularization

[AISAFENIX images](visu_images_AISAFENIX.md)

[HYMAP images](visu_images_HYMAP.md)

[AVIRIS-NG images](visu_images_AVIRIS-NG.md)

[AVIRIS-NG FULL images](visu_images_BIG-IMAGE.md)

[PRISMA images](visu_images_PRISMA.md)

[Back to main page](index.md)


