---
layout: post
published: true
main: true
title: "AMD's latest (patents) developments in CPU, GPU, package and more "
description: "AMD patent list that was published recently. Some Zen3 and CDNA foundation patents in the mix, packaging. AMD is also ramping up its Exascale Heterogenous Processor (EHP) IP."
picture: amdzen.gif

label_default: "Patent" 
label_primary: "AMD"
label_info: "Fresh"
---
<!-- Main Container -->

AMD patent list that was published recently. Some Zen3 and CDNA foundation patents in the mix. AMD is also ramping up its [Exascale Heterogenous Processor (EHP)](https://www.techpowerup.com/214868/amd-details-exascale-heterogenous-processor-ehp-for-supercomputers) IP.

* [Side information for video data transmission](https://www.freepatentsonline.com/20200314434.pdf) : Methods for performing efficient video compression for wireless VR stream communication

* [Integrated circuit package with integrated voltage regulator](https://www.freepatentsonline.com/20200312766.pdf) : Looks like next gen CPU/GPU need an integrated voltage regulator

* [Auto generation and tuning tool for convolution kernels](https://www.freepatentsonline.com/20200302285.pdf) : Methods for implementing an auto generation and tuning tool for convolution kernels, which is a basic CDNA foundation.

* [Processing unit with mixed precision operations](https://www.freepatentsonline.com/20200293286.pdf) : More CDNA goodies.

* [Using Multiple Memory Elements in an Input-Output Memory Management Unit for Performing Virtual Address to Physical Address Translations](https://www.freepatentsonline.com/20200301849.pdf) : This has some potential for speeding up access to Storage class memory device.
 
* [Dynamic Instances Semantics](https://www.freepatentsonline.com/20200301681.pdf)

* [Multi-RDL structure packages and methods of fabricating the same](https://www.freepatentsonline.com/20200294923.pdf) : next CPU battlefield is the packaging tech

* [Detecting voice regions in a non-stationary noisy environment](https://www.freepatentsonline.com/20200294534.pdf) : Foray into mobile phone tech, or simply wants to compete with NVDIA RTX voice?
 
* [Fan-Out packages with warpage resistance](https://www.freepatentsonline.com/20200294914.pdf) : packaging, packaging, packaging

* [Method and apparatus for peer-to-peer messaging in heterogeneous machine clusters](https://www.freepatentsonline.com/20200293387.pdf) : this one is interesting, looks like thread aware RDMA type semantics... foundation for EHP

* [Pipeline including separate hardware data paths for different instruction types](https://www.freepatentsonline.com/20200293329.pdf) : Say hello to one of the Zen 3 foundations...

* [Implementing a micro-operation cache with compaction](https://www.freepatentsonline.com/20200285466.pdf) : Say hello to one of the Zen 3 foundations...

* [Home agent based cache transfer acceleration scheme](https://www.freepatentsonline.com/20190188155.pdf) : Systems, apparatuses, and methods for implementing a speculative probe mechanism

* [Probe placement for laser probing system](https://www.freepatentsonline.com/20200284837.pdf) : A great improvement in defect identification

* [Activation Function Functional Block for Electronic Devices](Activation Function Functional Block for Electronic Devices)

* [Speculative instruction wakeup to tolerate draining delay of memory ordering violation check buffers](https://www.freepatentsonline.com/20200319889.pdf) : remember the ["zero-bubble"](https://www.freepatentsonline.com/20170068539.pdf) branch prediction, this is a continuation of the same idea. In case you didn’t know a bubble in the core pipeline is when it’s idle either due to a memory stall or incorrect branch prediction wherein the entire pipeline has to be flushed and loaded with a new set of instructions, wasting precious execution cycles.

* [Method enabling virtual pages to be allocated with noncontiguous backing physical subpages](https://www.freepatentsonline.com/20200320016.pdf) :  ho.... this one is interesting, virtual page backed by fragmented physical page. Not sure of the practical use case but this can lead to some interesting stuff in the virtualization domain.

* [Dynamic interrupt rate control in computing systems](https://www.freepatentsonline.com/20190163251.pdf)

* [Precise suspend and resume of workloads in a processing unit](https://www.freepatentsonline.com/20190163527.pdf) : A method for support suspend/resume operations for dependent workloads executing on different pipelines in GPUs

* [Stochastic rounding logic](https://www.freepatentsonline.com/10628124.pdf) : Techniques and circuits are provided for stochastic rounding. Highly recommended to read the article referred to in the patent.

* [Near-memory hardened compute blocks for configurable computing substrates](https://www.freepatentsonline.com/10579557.pdf) : EHP foundations ... keep a close eye on this one.

* [ In-memory interconnect protocol configuration registers](https://www.freepatentsonline.com/9767028.pdf) : More EHP foundation

* [Onboard monitoring of voltage levels and droop events](https://www.freepatentsonline.com/10627883.pdf)

* [Multi-plane Transmission](https://www.freepatentsonline.com/20200314436.pdf)

* [Generating vectorized control flow using reconverging control flow graphs](https://www.freepatentsonline.com/20200310766.pdf)

* [Source clock recovery in wireless video systems](https://www.freepatentsonline.com/20200314469.pdf) : wireless console video ? probably VR/AR tech.

* [Platform Agnostic Atomic Operations](https://www.freepatentsonline.com/20200310684.pdf) : Atomic operations for GPU or FPGA... RDMA semantics, I see what you are doing here AMD, more EHP foundation

* [Timer for use dual voltage supplies](https://www.freepatentsonline.com/20200312389.pdf)

* [Metal zero power ground stub route to reduce cell area and improve cell placement at the chip level](https://www.freepatentsonline.com/20190155979.pdf)

* [Save and restore scoreboard](https://www.freepatentsonline.com/10403351.pdf) : Read [Loh's paper](https://www.cs.utah.edu/wondp/wondp2013-paper2-final.pdf) for a more palatable version of this patent.

* [Deskewing method for a physical layer interface on a multi-chip module](https://www.freepatentsonline.com/20200344039.pdf) : packaging interconnect

* [Buffer management for plug-in architectures in computation graph structures](https://www.freepatentsonline.com/20200344378.pdf)

* [Data sparsity monitoring during neural network training](https://www.freepatentsonline.com/20200342327.pdf)

* [Symmetrical Balanced C-element](https://www.freepatentsonline.com/20200358447.pdf)

* [Memory management in graphics and compute application programming interfaces](https://www.freepatentsonline.com/20200357093.pdf) : continuation of U.S. patent application Ser. No. 15/477,795, filed Apr. 3, 2017

* [System and method for scheduling instructions in a multithread simd architecture with a fixed number of registers](https://www.freepatentsonline.com/20200278947.pdf) : RDNA3 ...

* [Region-based image compression and decompression](https://www.freepatentsonline.com/20200280721.pdf)

* [Virtual Reality Beamforming](https://www.freepatentsonline.com/20200280862.pdf) : Methods for implementing enhanced beamforming training procedures in VR wireless communication.

* [Wave creation control with dynamic resource allocation](https://www.freepatentsonline.com/20190129756.pdf) : A method to determine the resource allocations of waves based on the average resource allocation and dispatching the spawned waves on the GPU.

* [Swizzling In 3D Stacked Memory](https://www.freepatentsonline.com/20190129651.pdf) : EHP ...
 
* [Hybrid lower-level cache inclusion policy for cache hierarchy having at least three caching levels](https://www.freepatentsonline.com/20190121748.pdf)

* [Processor with accelerated lock instruction operation](https://www.freepatentsonline.com/20200272463.pdf) : Another Zen3 foundation...

* [Hybrid Matrix Multiplication Pipeline](https://www.freepatentsonline.com/20200272687.pdf) : More CDNA

* [Method and apparatus for generating artificial intelligence resistant verification images](https://www.freepatentsonline.com/20200272726.pdf) : Hardware captcha ...
 
* [Preemptive cache writeback with transaction support](https://www.freepatentsonline.com/20190095330.pdf)

* [Compressing tags in software and hardware semi-sorted caches](https://www.freepatentsonline.com/10749545.pdf) : A data storage system which performs partial compression and decompression of cached data.

* [Domain Identifier and Device Identifier Translation by an Input-Output Memory Management Unit](https://www.freepatentsonline.com/20200334058.pdf)

* [Nwell and Subtrate Taps In Memory Layout](https://www.freepatentsonline.com/20200335142.pdf)

* [Asynchronous Buffer with Pointer Offsets](https://www.freepatentsonline.com/20190179777.pdf)

* [Semiconductor chip with stacked conductor lines and air gaps](https://www.freepatentsonline.com/20200328155.pdf): Air gaps in interlevel dielectric layers between adjacent conductor lines to counteract the capacitance increase associated with reduced line spacing.

* [Capacitive structure for memory write assist ](https://www.freepatentsonline.com/20190180798.pdf)

* [Land Pad Design for High Speed Terminals](https://www.freepatentsonline.com/20190181087.pdf)

* [Standard cell and power grid architectures with EUV lithography](https://www.freepatentsonline.com/10796061.html)
<!--End Main Container -->
