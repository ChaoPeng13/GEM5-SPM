GEM5-SPM
========

Now I am trying to add an SPM module to GEM5

In my opinion, this job can be implemented by two apporaches.

(1) See scratchpad memory as an extension of main memory. The only difference from main memory is its low latency. We can access SPM by load/store instruction.
(2) Implemnet an SPM module based on cache module. This way needs the support of the DMA instructions.

