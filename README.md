# Reimplementation of Occupancy Networks:
Occupancy Networks: Learning 3D Reconstruction in Function Space.
Mescheder, Lars and Oechsle, Michael and Niemeyer, Michael and Nowozin, Sebastian and Geiger, Andreas.
Proceedings IEEE Conf. on Computer Vision and Pattern Recognition (CVPR).2019
https://github.com/autonomousvision/occupancy_networks


Repo Authors: Andrea Malleo, Reggie Gomez

[Project Paper](/report/report.pdf)
# Results

## Single Image Mesh Reconstruction of Benches
<p float="left">
<img src="/report/benchImages/pervertexbench.gif" width="350" height="350"/> 
<img src="/report/benchImages/wirebench.gif" width="350" height="350"/>
</p>

## Point Completion of Cell Phone
<p float="left">
<img src="/report/phoneImages/phone_pervertex.gif" width="350" height="350"/>
<img src="/report/phoneImages/phone_wireframe.gif" width="350" height="350"/>
</p>


## Interpolation in Latent Variable Space of Couches
<p float="left">
<img src="/report/latentInterpGifs/latentInterp_front_threshold3.gif" width="350" height="350"/> 
<img src="/report/latentInterpGifs/latentInterp_side_threshold3.gif" width="350" height="350"/>
</p>

## Dataset
We use renderings and voxelizations from [Choy2016](http://3d-r2n2.stanford.edu/).

```bash
bash scripts/download_choy.sh 
```
