FROM centos:centos5

RUN yum install -y make bzip2-devel bzip2-devel.i386 zlib-devel zlib-devel.i386 ncurses-devel ncurses-devel.i386 perl glibc-devel glibc-devel.i386 libX11-devel libX11-devel.i386 libXt-devel libXt-devel.i386 patch expat.i386 expat.x86_64

RUN yum install -y wget
RUN wget https://bitbucket.org/squeaky/centos-devtools/downloads/gcc-4.9.2-multilib-binutils-2.25-x86_64.tar.bz2 -O - | tar -C / -xj
RUN yum install -y setarch
