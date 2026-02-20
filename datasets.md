# Dataset for Monolithic Firmware
An index of datasets for monolithic firmware security research, covering images, labels, vulnerability annotations, and reproducible environments.
- Firmware images: public releases, OTA packages, system images
- Vulnerability annotations: CVE mappings, pre/post patch samples
- Runtime environments: emulation setups and scripts

## Dataset
* https://github.com/ucsb-seclab/heapster-dataset-metadata: a collection of metadata regarding the firmware images in dataset (i.e., loading configurations and many different additional information like blob entry-point, base-address, recognized functions, etc...). If you need more, or support on how to use those, don't hesitate to ping me.
* https://github.com/ucsb-seclab/monolithic-firmware-collection: a big collection of monolithic firmware images consolidated using previous research. You can find the exact list of tested blobs [here](https://github.com/ucsb-seclab/heapster/blob/master/heapster-env/fw-dataset/wild/fw-tested.txt).
* https://docs.google.com/spreadsheets/d/1e6GkfeSvBavg4e9e-mgUuTfPj4It9WYItkNG7xG1G2g/edit?usp=sharing: comprehensive metadata regarding firmware clusterization and stats of the tool.
* https://github.com/mindThomas/JetsonCar: This is the monolithic repository for the Jetson RC car project including embedded firmware, ROS nodes, libraries, MATLAB scripts, startup scripts etc. This repository collates the work from multiple repositories related to the JetsonCar project to simplify version control. 
