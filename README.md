# FireSpot-CNX
Forest Fire/ Smoke in Chiang Mai, Thailand

**Authors:** 

## About

D-Fire is an image dataset of fire and smoke occurrences designed for machine learning and object detection algorithms with more than 21,000 images.

<div align="center">
<table>
  <tr>
    <th>Number of images</th>
    <th>Number of bounding boxes</th>
  </tr>
 
  <tr><td>

  | Category | # Images |
  | ------------- | ------------- |
  | Only fire  | 1,164  |
  | Only smoke  | 5,867  |
  | Fire and smoke  | 4,658  |
  | None  | 9,838  |

  </td><td>

  | Class | # Bounding boxes |
  | ------------- | ------------- |
  | Fire  | 14,692 |
  | Smoke  | 11,865 |

  </td></tr> 
</table>
</div>

All images were annotated according to the YOLO format (normalized coordinates between 0 and 1). 
However, we provide the yolo2pixel function that converts coordinates in YOLO format to coordinates in pixels.

***

## Examples

<div align="center">

</div>

## Download

* [D-Fire dataset (Training, validation and test sets)](https://www.dropbox.com/scl/fo/jpheymj5odn3xkrkt29r2/h?rlkey=ely1wck6qoqok9x6nf9on568m&dl=0).

## Citation

Please cite the following paper if you use our image database:

