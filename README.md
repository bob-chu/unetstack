User-Space TCP/IP Stack Based on NetBSD

This project is inspired by the following projects:

FreeBSD based userspace tcp stack: F-Stack (https://github.com/F-Stack/f-stack)
FreeBSD based userspace tcp stack: Libuinet (https://github.com/pkelsey/libuinet)
4.4BSD based userspace tcp stack: User-land TCP/IP stack from 4.4BSD-Lite2 (https://github.com/chenshuo/4.4BSD-Lite2)
How to Build:

1. Clone the repository:
    git clone git@github.com:bob-chu/unetstack.git
2. Navigate to the project directory:
   cd unetbsd
3. Clone the NetBSD sources:
  git clone https://github.com/NetBSD/src.git

4.Build the project:
  make clean; make
