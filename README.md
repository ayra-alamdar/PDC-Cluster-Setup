 Cluster using Docker
## Build Instruction

The images are prebuilt and hosted at Docker Hub, but in case you want to build them yourself:

```sh
$ git clone https://github.com/ayra-alamdar/PDC-Cluster-Setup.git ==> no need to do this every time

$ cd PDC-Cluster-Setup

$ cd cluster

$ ./cluster.sh up size=4
in this size is the number of slaves your want they can be 4 top till 100 :)

$ ./cluster.sh login

$ mpirun -n * ./*

here the first * is the numeber of device you want to run it on and the second * is the name of the exec file

$ exit --> to exit from the kernal level

```


