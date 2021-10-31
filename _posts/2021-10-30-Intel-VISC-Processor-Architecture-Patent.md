---
layout: post
published: true
main: true
title: "Intel is still working on VISC architecture 5 years after acquisition of Soft machines"

description: "Not many of you remember, but in 2016 Intel quietly bought a small startup : Soft Machines . That startup was developing a new type of processor architecture called VISC. New patent are surfacing showing that Intel is still actively developing the concept.
"

picture: visc.jpg

label_default: "Intel" 
label_primary: "Patent"
label_info: "VISC"
---
<!-- Main Container -->
Not many of you remember, but in 2016 Intel quietly bought a small startup, "Soft Machines." That startup was developing a new type of processor architecture called VISC.

Quick recap on RISC vs CISC vs CRISC vs VISC:

For the most part, processor architectures are traditionally built around either CISC (complex) or RISC (reduced) instruction sets and execution models. At the same time, more modern designs (e.g., Intel Core) are increasingly a mix or so-called 'CRISC' design. The difference between CISC and RISC boils down to the fact that simpler designs can be more power-efficient. Still, complex designs can do more complicated things in fewer cycles. At the same time, CRISC essentially meets the two paradigms benefits, though not without inheriting some of the drawbacks. VISC, for lack of a better description, is a RISC design using a custom instruction set over a translation layer that allows a single thread of operations to be dispatched over multiple physical cores.

Now, why bring this up five years later? Many people would have assumed that the tech might have disappeared (me included) in the depth of Intel, never to be seen again.

Well, not so fast. It turns out that some of the fundamental principles implemented in the VISC architecture are still being worked on and patented by Intel. The following patent, filed in 2020, is an excellent example.

Patent: [Method and system for instruction block to execution unit grouping - Intel](https://www.freepatentsonline.com/20200341768.pdf)

Title : Instruction blocks, register templates, and inheritance vectors to simplify OoO mgmt job, also allowing recovery from miss-predictions and flushes very quickly


<!--End Main Container -->
