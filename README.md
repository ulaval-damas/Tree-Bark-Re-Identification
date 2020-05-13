# Tree-Bark-Re-Identification

## Article

If you use one or more of our datasets in your work, please cite the following article:</br>
https://arxiv.org/abs/1912.03221

## Bibtex entry
@INPROCEEDINGS{Robert2020BarkRe-Id, 
author={M. {Robert} and P. {Dallaire} and P. {Giguère}}, 
booktitle={2020 Conference on Computer and Robot Vision (CRV)}, 
title={Tree bark re-identification using a deep-learning feature descriptor}, 
year={2020}
}

## Datasets

Link for all of our datasets:</br>
https://drive.google.com/drive/folders/1nD2puK8r8FsLWAdnZEQMzurjr5uQHszG?usp=sharing
</br>
This link provides access to 7 zip files that compose our datasets. Among them, you will find our original Bark Id dataset, an already cropped version of this dataset and our Bark Aligned dataset, as shown below: </br>

Bark Id Dataset:</br>
These files contain the unprocessed images we collected. Each of these images contains Red Pine or Elm bark, surrounded by our wooden frame. Images are organized by folder, with each folder representing a distinct bark surface. Also, each folder is identified by the tree species (EL or RP), the number of the tree, and the number of the surface of this tree used to take pictures (ex.: EL-tree-5_frame-2).</br>

RP-Dbark.zip</br>
EL-Dbark.zip</br>


Negative Examples Dataset:</br>
Extra images of elm. Every image displays no wooden frame and is already cropped to remove the background.</br>

Dataset_TN.zip</br>


Bark Id Dataset Crop:</br>
Same as the Bark Id dataset, but all the images have already been crop, and all pixel other than bark has been removed.</br>

RP-CropDataset.zip</br>
EL-CropDataset.zip</br>


Bark Aligned:</br>
Images patches of 64x64 pixels. These patches are store as a numpy array with dimension (n, 12, 64, 64), where n is the number of keypoints found for a single bark surface. Each numpy file is identified with the same name as the folder in the Bark Id dataset to allow the correspondence between them. Thus, a file named EL-tree-5_frame-2 is the patches produced from the keypoints found in the images of the folder EL-tree-5_frame-2 of the Bark Id dataset.</br>

RP-PatchDataset.zip</br>
EL-PatchDataset.zip</br>

