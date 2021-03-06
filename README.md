### Linux Tracing Workshops Materials

This repository contains examples and hands-on labs for various Linux tracing workshops, focusing on modern tracing tools.  To perform these labs, you will need a Linux box that meets several prerequisites. You can also use a VirtualBox appliance supplied by the instructor.

- - -

#### Prerequisites

1. Linux 4.6+ (the distribution doesn't matter; tested on Ubuntu and Fedora Core)
1. [perf](https://perf.wiki.kernel.org/index.php/Main_Page)
1. [perf-map-agent](https://github.com/jrudolph/perf-map-agent)
1. [FlameGraph](https://github.com/brendangregg/FlameGraph)
1. [bcc](https://github.com/iovisor/bcc/blob/master/INSTALL.md)
1. [OpenJDK](http://openjdk.java.net)
1. The **systemtap-sdt-dev** package on Ubuntu or the **systemtap-sdt-devel** package on Fedora/RHEL
1. [Node.js](https://github.com/nodejs/node/wiki/Installation) built from source with `configure --with-dtrace`
1. MySQL or [MariaDB](https://mariadb.org)
1. [MySQL Python Connector](https://dev.mysql.com/doc/connector-python/en/connector-python-installation.html)

- - -

#### Labs

1. [Probing Tracepoints with ftrace](ftrace.md)
1. [CPU Sampling with `perf` and Flame Graphs](perf.md)
1. [Using BPF Tools: Chasing a Memory Leak](bpf-memleak.md)
1. [Using BPF Tools: Database and Disk Stats and Stacks](bpf-io.md)
1. [Using BPF Tools: Node and JVM USDT Probes](bpf-usdt.md)
1. [Writing BPF Tools: Contention Stats and Stacks](bpf-contention.md)
1. [Writing BPF Tools: From BCC GitHub Issues](bpf-issues.md)

- - -

(C) Sasha Goldshtein, 2015-2016. All rights reserved.

