## classification of hyperspectral reflectance images : CHRIPS (2020) --> EN CONSTRUCTION !!!!

A classification method of hyperspectral reflectance images named CHRIPS (Classification of Hyperspectral Reflectance Images with Physical and Statistical criteria) is presented. This method aims at classifying each pixel from a given set of thirteen classes: unidentified dark surface, water, plastic matter, carbonate, clay, vegetation (dark green, dense green, sparse green, stressed), house roof / tile, asphalt, vehicle / paint / metal surface and non-carbonated gravel. Each class is
characterized by physical criteria (detection of specific absorptions or shape features) or statistical criteria (use of dedicated spectral indices) over spectral reflectance. CHRIPS input is a hyperspectral reflectance image covering the spectral range \[400-2500nm\]. The presented method has four advantages, namely: i) is robust in transfer, class identification is based on criteria that are not very sensitive to sensor type; ii) does not require training, criteria are pre-defined; iii) includes a reject class, this class reduces misclassifications; iv) high precision and recall, F1 score is generally above 0.9 in our test. As the number of classes is limited, CHRIPS could be used in combination with other classification algorithms able to process the reject class in order to decrease the number of unclassified pixels.

Alakian, A.; Achard, V. Classification of Hyperspectral Reflectance Images With Physical and Statistical Criteria. Remote Sens. 2020, 12, 2335. https://doi.org/10.3390/rs12142335

<p align="center">
  <img src="Complements/Graphical_Abstract_CHRIPS.png" width="700" />
</p>





# Classification results with standard thresholds (no tuning of parameters)

<p align="center">  
  <img src="Complements/Legende_classif_ligne_v2.png" width="500" />
</p>




**Hyspex_Fauga08_NORD (1027 x 950)**
<img src="Images_COULEUR/Hyspex_Fauga08_NORD_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/Hyspex_Fauga08_NORD_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/Hyspex_Fauga08_NORD_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**Hyspex_Mauzac (564 x 554)**
<img src="Images_COULEUR/Hyspex_Mauzac_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/Hyspex_Mauzac_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/Hyspex_Mauzac_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**Hyspex_Fauga_town_denoised (241 x 303)**
<img src="Images_COULEUR/Hyspex_Fauga_town_denoised_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/Hyspex_Fauga_town_denoised_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/Hyspex_Fauga_town_denoised_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**Hyspex_Fermat (261 x 231)**
<img src="Images_COULEUR/Hyspex_Fermat_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/Hyspex_Fermat_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/Hyspex_Fermat_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**HyMap_Garons (527 x 998)**
<img src="Images_COULEUR/HyMap_Garons_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/HyMap_Garons_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/HyMap_Garons_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map


**AVIRIS_NG_Allemagne2_img1 (640 x 952)**
<img src="Images_COULEUR/AVIRIS_NG_Allemagne2_img1_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Allemagne2_img1_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Allemagne2_img1_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Allemagne2_img2 (635 x 953)**
<img src="Images_COULEUR/AVIRIS_NG_Allemagne2_img2_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Allemagne2_img2_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Allemagne2_img2_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Allemagne2_img3 (633 x 931)**
<img src="Images_COULEUR/AVIRIS_NG_Allemagne2_img3_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Allemagne2_img3_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Allemagne2_img3_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Allemagne2_img4 (637 x 941)**
<img src="Images_COULEUR/AVIRIS_NG_Allemagne2_img4_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Allemagne2_img4_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Allemagne2_img4_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Allemagne2_img5 (636 x 951)**
<img src="Images_COULEUR/AVIRIS_NG_Allemagne2_img5_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Allemagne2_img5_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Allemagne2_img5_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Allemagne_img1 (599 x 952)**
<img src="Images_COULEUR/AVIRIS_NG_Allemagne_img1_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Allemagne_img1_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Allemagne_img1_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Allemagne_img2 (601 x 764)**
<img src="Images_COULEUR/AVIRIS_NG_Allemagne_img2_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Allemagne_img2_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Allemagne_img2_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Allemagne_img3 (607 x 948)**
<img src="Images_COULEUR/AVIRIS_NG_Allemagne_img3_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Allemagne_img3_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Allemagne_img3_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Allemagne_img4 (612 x 940)**
<img src="Images_COULEUR/AVIRIS_NG_Allemagne_img4_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Allemagne_img4_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Allemagne_img4_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Allemagne_img5 (594 x 962)**
<img src="Images_COULEUR/AVIRIS_NG_Allemagne_img5_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Allemagne_img5_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Allemagne_img5_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Allemagne_img6 (614 x 890)**
<img src="Images_COULEUR/AVIRIS_NG_Allemagne_img6_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Allemagne_img6_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Allemagne_img6_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_France_img1 (575 x 899)**
<img src="Images_COULEUR/AVIRIS_NG_France_img1_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_France_img1_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_France_img1_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_France_img2 (613 x 932)**
<img src="Images_COULEUR/AVIRIS_NG_France_img2_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_France_img2_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_France_img2_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_France_img3 (598 x 914)**
<img src="Images_COULEUR/AVIRIS_NG_France_img3_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_France_img3_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_France_img3_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_France_img4 (599 x 927)**
<img src="Images_COULEUR/AVIRIS_NG_France_img4_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_France_img4_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_France_img4_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Suisse_Basel_img1 (623 x 910)**
<img src="Images_COULEUR/AVIRIS_NG_Suisse_Basel_img1_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Suisse_Basel_img1_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Suisse_Basel_img1_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Suisse_Basel_img2 (615 x 757)**
<img src="Images_COULEUR/AVIRIS_NG_Suisse_Basel_img2_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Suisse_Basel_img2_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Suisse_Basel_img2_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Italie_img1 (605 x 847)**
<img src="Images_COULEUR/AVIRIS_NG_Italie_img1_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Italie_img1_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Italie_img1_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Italie_img2 (597 x 856)**
<img src="Images_COULEUR/AVIRIS_NG_Italie_img2_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Italie_img2_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Italie_img2_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Italie_img3 (600 x 926)**
<img src="Images_COULEUR/AVIRIS_NG_Italie_img3_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Italie_img3_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Italie_img3_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map


**AVIRIS_NG_Houston_img1 (590 x 957)**
<img src="Images_COULEUR/AVIRIS_NG_Houston_img1_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Houston_img1_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Houston_img1_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Houston_img2 (596 x 938)**
<img src="Images_COULEUR/AVIRIS_NG_Houston_img2_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Houston_img2_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Houston_img2_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Houston_img3 (601 x 949)**
<img src="Images_COULEUR/AVIRIS_NG_Houston_img3_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Houston_img3_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Houston_img3_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map


**AVIRIS_NG_Oklahoma_img1 (591 x 933)**
<img src="Images_COULEUR/AVIRIS_NG_Oklahoma_img1_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Oklahoma_img1_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Oklahoma_img1_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Oklahoma_img2 (596 x 993)**
<img src="Images_COULEUR/AVIRIS_NG_Oklahoma_img2_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Oklahoma_img2_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Oklahoma_img2_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map




**AVIRIS_NG_Alaska_img1 (609 x 962)**
<img src="Images_COULEUR/AVIRIS_NG_Alaska_img1_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Alaska_img1_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Alaska_img1_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Alaska_img2 (584 x 953)**
<img src="Images_COULEUR/AVIRIS_NG_Alaska_img2_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Alaska_img2_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Alaska_img2_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Alaska_img3 (631 x 957)**
<img src="Images_COULEUR/AVIRIS_NG_Alaska_img3_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Alaska_img3_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Alaska_img3_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Alaska_img4 (638 x 957)**
<img src="Images_COULEUR/AVIRIS_NG_Alaska_img4_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Alaska_img4_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Alaska_img4_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Alaska_img5 (627 x 935)**
<img src="Images_COULEUR/AVIRIS_NG_Alaska_img5_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Alaska_img5_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Alaska_img5_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Inde_Bengaluru_img1 (588 x 929)**
<img src="Images_COULEUR/AVIRIS_NG_Inde_Bengaluru_img1_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Inde_Bengaluru_img1_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Inde_Bengaluru_img1_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Inde_Bengaluru_img2 (595 x 937)**
<img src="Images_COULEUR/AVIRIS_NG_Inde_Bengaluru_img2_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Inde_Bengaluru_img2_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Inde_Bengaluru_img2_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Inde_Bengaluru_img3 (568 x 952)**
<img src="Images_COULEUR/AVIRIS_NG_Inde_Bengaluru_img3_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Inde_Bengaluru_img3_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Inde_Bengaluru_img3_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Inde_Bengaluru_img4 (597 x 936)**
<img src="Images_COULEUR/AVIRIS_NG_Inde_Bengaluru_img4_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Inde_Bengaluru_img4_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Inde_Bengaluru_img4_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Inde_img1 (594 x 849)**
<img src="Images_COULEUR/AVIRIS_NG_Inde_img1_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Inde_img1_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Inde_img1_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Inde_img2 (589 x 822)**
<img src="Images_COULEUR/AVIRIS_NG_Inde_img2_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Inde_img2_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Inde_img2_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Inde_img3 (608 x 861)**
<img src="Images_COULEUR/AVIRIS_NG_Inde_img3_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Inde_img3_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Inde_img3_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**AVIRIS_NG_Inde_img4 (635 x 843)**
<img src="Images_COULEUR/AVIRIS_NG_Inde_img4_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/AVIRIS_NG_Inde_img4_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/AVIRIS_NG_Inde_img4_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map



**PRISMA_CEA_Cuprite (1000 x 1000)**
<img src="Images_COULEUR/PRISMA_CEA_Cuprite_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/PRISMA_CEA_Cuprite_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/PRISMA_CEA_Cuprite_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**PRISMA_CEA_Fos_sur_Mer (1000 x 1000)**
<img src="Images_COULEUR/PRISMA_CEA_Fos_sur_Mer_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/PRISMA_CEA_Fos_sur_Mer_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/PRISMA_CEA_Fos_sur_Mer_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**PRISMA_image10_Marseille (1000 x 1000)**
<img src="Images_COULEUR/PRISMA_image10_Marseille_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/PRISMA_image10_Marseille_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/PRISMA_image10_Marseille_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**PRISMA_image11_Australie (1000 x 1000)**
<img src="Images_COULEUR/PRISMA_image11_Australie_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/PRISMA_image11_Australie_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/PRISMA_image11_Australie_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**PRISMA_image12_Bali (1000 x 1000)**
<img src="Images_COULEUR/PRISMA_image12_Bali_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/PRISMA_image12_Bali_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/PRISMA_image12_Bali_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**PRISMA_image1 (1000 x 1000)**
<img src="Images_COULEUR/PRISMA_image1_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/PRISMA_image1_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/PRISMA_image1_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**PRISMA_image2 (1000 x 1000)**
<img src="Images_COULEUR/PRISMA_image2_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/PRISMA_image2_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/PRISMA_image2_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**PRISMA_image3 (1000 x 1000)**
<img src="Images_COULEUR/PRISMA_image3_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/PRISMA_image3_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/PRISMA_image3_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**PRISMA_image4 (1000 x 1000)**
<img src="Images_COULEUR/PRISMA_image4_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/PRISMA_image4_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/PRISMA_image4_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**PRISMA_image5_New_York (1000 x 1000)**
<img src="Images_COULEUR/PRISMA_image5_New_York_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/PRISMA_image5_New_York_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/PRISMA_image5_New_York_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**PRISMA_image6_Hawai (1000 x 1000)**
<img src="Images_COULEUR/PRISMA_image6_Hawai_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/PRISMA_image6_Hawai_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/PRISMA_image6_Hawai_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**PRISMA_image7_Toulouse (1000 x 1000)**
<img src="Images_COULEUR/PRISMA_image7_Toulouse_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/PRISMA_image7_Toulouse_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/PRISMA_image7_Toulouse_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**PRISMA_image8_San_Francisco (1000 x 1000)**
<img src="Images_COULEUR/PRISMA_image8_San_Francisco_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/PRISMA_image8_San_Francisco_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/PRISMA_image8_San_Francisco_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map

**PRISMA_image9_Madrid (1000 x 1000)**
<img src="Images_COULEUR/PRISMA_image9_Madrid_00_IMAGE.jpg" width="250" /> | <img src="Images_CLASSIF/PRISMA_image9_Madrid_01_CLASSIF.png" width="250" /> | <img src="Images_REGUL/PRISMA_image9_Madrid_02_REGUL.png" width="250" />
:-: | :-: | :-:
Color image | CHRIPS classification map | Regularized classification map



 

