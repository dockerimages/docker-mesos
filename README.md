dockerimage-libmesos-ubuntu
===========================

The Updated Version of libmesos/ubuntu

You can Simply Build and run that Container it 100% Works




# Starting point
      /bin/sh -c #(nop) CMD [true]                                                                                                                      

    rm -rf /tmp/mesos.egg /tmp/mesos.deb                                                                                                                    
    easy_install /tmp/mesos.egg                                                                                                                             
/bin/sh -c #(nop) ADD tarsum+sha256:e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855 in /tmp/mesos.egg  bash -c echo manual > /etc/init/mesos-slave.override      
bash -c echo manual > /etc/init/mesos-master.override                                                                    env DEBIAN_FRONTEND=noninteractive dpkg -i /tmp/mesos.deb                                                                /bin/sh -c #(nop) ADD tarsum+sha256:e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855 in /tmp/mesos.deb   
env DEBIAN_FRONTEND=noninteractive apt-get install -y --fix-missing --force-yes default-jre-headless                     
env DEBIAN_FRONTEND=noninteractive apt-get install -y --fix-missing --force-yes python python-setuptools python-pip python-protobuf 
   env DEBIAN_FRONTEND=noninteractive apt-get install -y --fix-missing --force-yes python2.7 libsasl2-2 libcurl3 curl wget unzip                          
env DEBIAN_FRONTEND=noninteractive apt-get update                                                                        
   /bin/sh -c #(nop) MAINTAINER Mesosphere support@mesosphere.io                                                              /bin/sh -c #(nop) ADD saucy.tar.xz in /                                                                             
        /bin/sh -c #(nop) MAINTAINER Tianon Gravi <admwiggin@gmail.com> - mkimage-debootstrap.sh -i iproute,iputils-ping,ubuntu-minimal -t saucy.tar.xz saucy   0 B
511136ea3c5a64f264b78b5433614aec563103b4d4702f3ba7d4d2698e22c158   13 months ago                                        
