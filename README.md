# Before you start
This is intended to be a **demo** setup to run hardware accelerated content on Nvidia RTX GPU's. It is intended for Deep Neural Network, ML, and other GPGPU workflows.

# Requirements
These scripts must be run on Ubuntu 18.04 LTS using the Nvidia RTX 2080 Ti

# What is included?
Among the other packages these scripts will install
- nvidia drivers v418.56 https://www.nvidia.com/download/driverResults.aspx/145182/en-us
- docker https://www.docker.com/
- nvidia-docker https://github.com/NVIDIA/nvidia-docker
- nvidia-docker-compose https://github.com/eywalker/nvidia-docker-compose

# Installation
SSH into your Ubuntu 18.04 LTS (server) machine, once in just run the following
```bash
git clone git@gitlab.com:nrygpu/anomly-dnn-gpu-linux.git
cd anomly-dnn-gpu-linux
sudo su
source setup.sh
```
Keep in mind that:
- The installation will reboot the machine once done.

