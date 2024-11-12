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
  | Smoke  | 2,817 |
  | None  | 1,179  |

  </td><td>

  | Class | # Bounding boxes |
  | ------------- | ------------- |
  | Smoke  | 2,817 |

  </td></tr> 
</table>
</div>

Note: We provide the <i><b>yolo2pixel</b></i> function that converts coordinates in the YOLO format to coordinates in pixels.

***

## Examples

<table>
  <tr>
    <td align="center">
      <img alt="Image 1" src="https://drive.google.com/uc?id=17srKpo5JyoK309sY0jBpvRHX2LyvT0l2" width="400" height="300">
    </td>
    <td align="center">
      <img alt="Image 2" src="https://drive.google.com/uc?id=17qnoDD_ucQTkckG5e_PPDU4eMRU-Zpw6" width="400" height="300">
    </td>
  </tr>
  <tr>
    <td align="center">
      <img alt="Image 3" src="https://drive.google.com/uc?id=17a4Bs3XyltTpIbNJW_bJGLG5uK9f-9GK" width="400" height="300">
    </td>
    <td align="center">
      <img alt="Image 4" src="https://drive.google.com/uc?id=17yixYzhhBtcHg8GnxhKJ7TLSuZFTK5A-" width="400" height="300">
    </td>
  </tr>
  <tr>
    <td align="center">
      <img alt="Image 5" src="https://drive.google.com/uc?id=17ahTS0WI2aRvmEvusUI2aJNCXVKHAeUV" width="400" height="300">
    </td>
    <td align="center">
      <img alt="Image 6" src="https://drive.google.com/uc?id=187wybd8fpRNizTidhMnT24o_FpnTIxnO" width="400" height="300">
    </td>
  </tr>
</table>




## Download

* [FireSpot-CNX-r1 (Images and labels)](https://www.dropbox.com/scl/fo/jpheymj5odn3xkrkt29r2/h?rlkey=ely1wck6qoqok9x6nf9on568m&dl=0).

## Citation

Please cite the following paper if you use our image database:

Pornpholkullapat, N., Phankrawee, W., Boondet, P., Thein, T.L.L., Siharath, P., Cruz, J.D., Marata, K.T., Tungpimolrut, K. and Karnjana, J., 2023, November. FireSpot: A Database for Smoke Detection in Early-stage Wildfires. In 2023 18th International Joint Symposium on Artificial Intelligence and Natural Language Processing (iSAI-NLP) (pp. 1-6). IEEE.

doi: https://doi.org/10.1109/iSAI-NLP60301.2023.10354807

## Sponsor & Project members

![Organizations](https://drive.google.com/uc?id=1RFr4t7D0pVGwEVmGBtTSod5SG_fuegMU)
