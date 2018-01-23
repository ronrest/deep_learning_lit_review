


| Name | n_classes| n_train (valid) | n_test | Accesible |
| --- | ---     | ---             | ---    | --- |
|[Pascal VOC][pascal_voc]	|     |      |     | yes |
|[ImageNet][imagenet]	    | 200 | 450k (?)| ?  | r_acc |
|[COCO][coco]	            | 80  | 120k (?)| ?  | yes |
|[Oxford-IIIT Pet][oxpet]	| 37  | 7K (?)  | ? | ? |
|[KITTI Vision][kitti]	    | 3   | 7K (?)  | ? | yes |

**KEYS**

- `r_acc`: dataset is restricted to only people with an email address of a recognized academic institution.


## References
- Pascal VOC
    - M. Everingham, L. Van Gool, C. K. Williams, J. Winn, and A. Zisserman. The pascal visual object classes (voc) challenge. International journal of computer vision, 88(2):303–338, 2010

- COCO
    - T.-Y. Lin, M. Maire, S. Belongie, J. Hays, P. Perona, D. Ramanan, P. Doll ́ ar, and C. L. Zitnick. Microsoft coco: Common objects in context. In European Conference on Computer Vision, pages 740–755. Springer, 2014.

[coco]: http://cocodataset.org/
[imagenet]: http://www.image-net.org/
[kitti]: http://www.cvlibs.net/datasets/kitti/eval_3dobject.php
[oxpet]: http://www.robots.ox.ac.uk/~vgg/data/pets/
[pascal_voc]: http://host.robots.ox.ac.uk/pascal/VOC/
