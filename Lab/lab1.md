# Lab1: Introduction to Sniper

Please review the following files and attempt to answer the subsequent questions:

1. **How many levels of cache were used?**

   - L1-I
   - L1-D
   - L2
   - L3

2. **What was the associativity of the L1 cache?**

   - L1-I: 4
   - L1-D: 8

3. **What replacement policy did each cache use?**

   - LRU (Least Recently Used)

4. **What is the dispatch width of the processor?**

   - 4

5. **How many cycles delay does a branch misprediction cause?**

   - 8

6. **How many branch instructions were executed?**

   - 112423 + 5384

7. **What is the miss rate of each of the caches?**

   - L1-I: 2.66%
   - L1-D: 1.86%
   - L2: 74.06%
   - L3: 91.81%


## Generate SIFT Trace with SPEC CPU2006 (TODO)

	export SPEC_DIR=$(CPU2006_HOME)
	git clone -b sift https://github.com/nus-comparch/Speckle.git
	cd Speckle
	export SPECKLE_ROOT=$(pwd) # read README