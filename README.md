dockerimage-libmesos-ubuntu
===========================

The Updated Version of libmesos/ubuntu




# Starting point
935a545ea9dea6e867919addc6382ee7f3708f61cd220b95a6439a66734655ca   4 months ago        /bin/sh -c #(nop) CMD [true]                                                                                                                            0 B
250207c9e526c05d31cf9faef4c410a9d790f4b44ed5436c6d91ffe840e94131   4 months ago        rm -rf /tmp/mesos.egg /tmp/mesos.deb                                                                                                                    7 B
903e3cd770ee32fc1e0ba11afe77f054a68c719c700bae986acd9c87231be044   4 months ago        easy_install /tmp/mesos.egg                                                                                                                             123.1 MB
79b40cdae35f54a9ef79466e632feae050d3a466d55bb5124f9cf7e414c7fddb   4 months ago        /bin/sh -c #(nop) ADD tarsum+sha256:e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855 in /tmp/mesos.egg                                  32.6 MB
b42afbc950f384f17a2782f23691cbaca8686273b0055ed1be195b8072a9d73e   4 months ago        bash -c echo manual > /etc/init/mesos-slave.override                                                                                                    14 B
cfe3309edd027ae6057f3ae608f7c25587eaf540b49b94958752607e69a22b98   4 months ago        bash -c echo manual > /etc/init/mesos-master.override                                                                                                   14 B
30b4b13d968ddd5ff5d8a4a105bf0c83897cd383fad641ba84c40de574e21fbe   4 months ago        env DEBIAN_FRONTEND=noninteractive dpkg -i /tmp/mesos.deb                                                                                               179.7 MB
f4bbca627a233e1a7d4d297d143e171f0314dc6ae86bda2bf67085648a9bea57   4 months ago        /bin/sh -c #(nop) ADD tarsum+sha256:e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855 in /tmp/mesos.deb                                  47.45 MB
e0eab4a07d1a1fe74fa7430ffc4d22e8842668370f4926ac1dcd9b9ed0047828   4 months ago        env DEBIAN_FRONTEND=noninteractive apt-get install -y --fix-missing --force-yes default-jre-headless                                                    105.6 MB
b5630c427dcddfca7ee18b0cc06ea22c3cc9d30d528b0a58eab38c0e30310a69   4 months ago        env DEBIAN_FRONTEND=noninteractive apt-get install -y --fix-missing --force-yes python python-setuptools python-pip python-protobuf                     74.25 MB
403b18511742c53893efc0fda843f4ffec4179b8565494515230eef156021dbd   4 months ago        env DEBIAN_FRONTEND=noninteractive apt-get install -y --fix-missing --force-yes python2.7 libsasl2-2 libcurl3 curl wget unzip                           33.56 MB
cc97086edb0a7c9efece8f98a01be1931a9e1378099ccf8af6e7678f3592d2c0   5 months ago        env DEBIAN_FRONTEND=noninteractive apt-get update                                                                                                       33.69 MB
6933b675600133dd14ee148017a4048a084d14caabb94eaeccf49fc1c1796428   5 months ago        /bin/sh -c #(nop) MAINTAINER Mesosphere support@mesosphere.io                                                                                           0 B
24ba2ee5d982b0dd6bd9a1bd053c0c4da09e000207794816351a2539ce2ad9f2   7 months ago        /bin/sh -c #(nop) ADD saucy.tar.xz in /                                                                                                                 144.6 MB
cc7385a89304a3c7c789250e1f9e1f0848c42eddb29509b26e841a2b8977b8ea   7 months ago        /bin/sh -c #(nop) MAINTAINER Tianon Gravi <admwiggin@gmail.com> - mkimage-debootstrap.sh -i iproute,iputils-ping,ubuntu-minimal -t saucy.tar.xz saucy   0 B
511136ea3c5a64f264b78b5433614aec563103b4d4702f3ba7d4d2698e22c158   13 months ago                                                                                                                                                               0 B
