# create-ros-noetic-no-gui-docker-using-docker-file
This docker file create a docker image with the base image ros:noetic-ros-base and installs linux and ros packages.

To automate your docker place your script path or commands in the ros_entrypoint.sh file.


### Command to run this Dockerfile and create a docker image
```sh
sudo docker build -t image_name:image_tag .
```

## License
**Free Software, Hell Yeah!**

## Authors
- [Rahul Gupta](https://github.com/rahulelex)