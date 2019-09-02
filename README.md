# Docker ESA Snap 7

![Docker Cloud Automated build](https://img.shields.io/docker/cloud/automated/mapic/esa-snap)

----------


# docker-esa-snap

ESA Sentinel and SMOS Toolboxes preinstalled container for Earth Observation processing and analysis.

http://step.esa.int/main/

ESA is developing free open source toolboxes for the scientific exploitation of Earth Observation missions under the the Scientific Exploitation of Operational Missions (SEOM) programme element. STEP is the ESA community platform for accessing the software and its documentation, communicating with the developers, dialoguing within the science community, promoting results and achievements as well as providing tutorials and material for training scientists using the Toolboxes.

Contains: SNAP, S1TBX, S2TBX, S3TBX, SMOS Box, PROBA-V Toolbox.

Get it from https://hub.docker.com/r/mrmoor/esa-snap/


Or get it via docker from the cmd:

    docker pull mrmoor/esa-snap
  
  
## Python integration

There is also a Docker-Container available with Python and SNAP integration with snappy based on this repo.
Have a look at https://github.com/schwankner/esa-snap-with-python
Or pull from docker:
    
    docker pull mrmoor/esa-snap-with-python