# 3d-reconstruction

# Run app locally
- Install [MATLAB](https://la.mathworks.com/downloads/)
- Install MATLAB's add-ons: Communications Toolbox, Parallel Computing Toolbox, Image Processing Toolbox
- Install [CVX] (https://la.mathworks.com/downloads/)http://cvxr.com/cvx/download/) library for MATLAB
- Install Python's dependencies
```
python -m pip install --user numpy scipy matplotlib ipython jupyter pandas sympy nose
pip install torch===1.5.0 torchvision===0.6.0 -f https://download.pytorch.org/whl/torch_stable.html
pip install h5py
pip install -U scikit-learn
```
- Follow the instructions in the `get_started.m` file
- Source: [**paper**](https://arxiv.org/abs/1711.10669.pdf):
```
@article{pontes2017image2mesh,
  title={Image2Mesh: A Learning Framework for Single Image 3D Reconstruction},
  author={Jhony K. Pontes and Chen Kong and Sridha Sridharan and Simon Lucey and Anders Eriksson and Clinton Fookes},
  journal={arXiv:1711.10669},
  year={2017}
}
```
