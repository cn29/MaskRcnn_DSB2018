# MaskRcnn_DSB2018
Version for Nvidia P100

## Install Nvidia Drivers
### Nvidia driver r390
```
sudo dpkg -i nvidia-diag-driver-local-repo-ubuntu1604-390.30_1.0-1_amd64.deb
sudo apt-get update
sudo apt-get install cuda-drivers 
reboot
```
### Cuda 9.1
  ```
  sudo dpkg -i cuda-repo-ubuntu1604-9-1-local_9.1.85-1_amd64.deb
  sudo apt-key add /var/cuda-repo-<version>/7fa2af80.pub
  sudo apt-get update
  sudo apt-get install cuda
  ```
### Cudnn 7005
```
sudo dpkg -i libcudnn7_7.0.3.11-1+cuda9.0_amd64.deb
sudo dpkg -i libcudnn7-dev_7.0.3.11-1+cuda9.0_amd64.deb
sudo dpkg -i libcudnn7-doc_7.0.3.11-1+cuda9.0_amd64.deb
```
