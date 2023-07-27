# FireSpot-CNX

**Authors:** 
Natthaphol P., Warit P., Kanokvate T., Jessada K.

## About

The <b>FireSpot</b> database is developed based on a collaboration between National Electronics and Computer Technology Center (NECTEC) and three local municipalities, including Pa Miang, Nong Yaeng, and Choeng Doi, in Chiang Mai, Thailand. In the current release, it consists of 4,000 images. Half of them contain smoke in the early burning stages, and another half do not. Smoke areas in those images are labeled with bounding boxes. The bounding box values are a quadruple $(x_c,y_c,w,h)$, where $(x_c,y_c)$ is the Cartesian coordinates of the point at the box center, $w$ is the box width, and $h$ is the box height. The bounding box values are normalized to the maximum of $1$, i.e., range from $0$ to $1$, of which the point at $(0,0)$ represents the top-left corner, and the point at $(1,1)$ represents the bottom-right corner of the image.

<div align="center">
<table>
  <tr>
    <th>Number of images</th>
    <th>Number of bounding boxes</th>
  </tr>
 
  <tr><td>

  | Category | # Images |
  | ------------- | ------------- |
  | Smoke  | 2,000 |
  | None  | 2,000  |

  </td><td>

  | Class | # Bounding boxes |
  | ------------- | ------------- |
  | Smoke  | 2,000 |

  </td></tr> 
</table>
</div>

Note: We provide the <i><b>yolo2pixel</b></i> function that converts coordinates in the YOLO format to coordinates in pixels.

***

## Examples

<table>
  <tr>
    <td align="center">
      <img alt="Smoke1 Image" src="https://drive.google.com/uc?id=17srKpo5JyoK309sY0jBpvRHX2LyvT0l2">
    </td>
    <td align="center">
      <img alt="Smoke2 Image" src="https://drive.google.com/uc?id=17qnoDD_ucQTkckG5e_PPDU4eMRU-Zpw6">
    </td>
  </tr>
  <tr>
    <td align="center">
      <img alt="Smoke3 Image" src="https://drive.google.com/uc?id=1G2Ah3sUe7Up2mQTFV-0h-ILwEg5aTLGm">
    </td>
    <td align="center">
      <img alt="Smoke1 Image" src="https://drive.google.com/uc?id=1sxJRXMPKrVWQIfv2KaDfr8p7aOIqErmG">
    </td>
  </tr>
  <tr>
    <td align="center">
      <img alt="Smoke1 Image" src="https://drive.google.com/uc?id=11X7Z3lxy-dNoaXsqL2GrO4Nu-iXplqpw">
    </td>
    <td align="center">
      <img alt="Additional Image" src="https://drive.google.com/uc?id=1SXAmyUeWpi0XB4dgMiqIVj44VjFlZkzg">
    </td>
  </tr>
</table>




## Download

* [FireSpot-CNX-r1 (Only images and labels)](https://www.dropbox.com/scl/fo/jpheymj5odn3xkrkt29r2/h?rlkey=ely1wck6qoqok9x6nf9on568m&dl=0).

## Citation

Please cite the following paper if you use our image database.

## Sponsor & Project members

![Organizations](https://drive.google.com/uc?id=1RFr4t7D0pVGwEVmGBtTSod5SG_fuegMU)
