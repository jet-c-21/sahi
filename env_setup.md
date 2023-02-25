```shell
conda create --name=sahi python=3.6.9 -y
```
```shell
conda env remove --name sahi -y
```

# Jupyter
```shell
python -m ipykernel install --user --name sahi --display-name "sahi"
```
```shell
jupyter kernelspec uninstall sahi -y
```

# install packages
```shell
pip install sahi
```
```shell
conda install pytorch=1.13.1 torchvision=0.14.1 pytorch-cuda=11.7 -c pytorch -c nvidia -y
```
```shell
pip install transformers -i https://pypi.python.org/simple
```
```shell
pip install yolov5
```
```shell
pip install -U openmim
```
```shell
mim install mmcv-full==1.7.0
```
```shell
conda install -n base -c conda-forge jupyterlab_widgets
conda install -n sahi -c conda-forge ipywidgets
```