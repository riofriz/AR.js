# Steps
- thresholding is working in webassembly
- now lets make it fast
  - O(n) incremental blur In webassembly
  - Incremental blur: 3 stages. First, middle, end. Do slow loop for those. Only aim for O(n). 
- do a linear time with the incremental technique
  - do a pure average first
  - you know how to code it
  - later: do a gaussian approximentation - boxstackblur stuff which is the trick
- so you get a good idea of the speed
- so you get webassembly version from optimised c - this is the fastest it can be on the web at the moment
- good to bench webassembly
- test multiple browser - multiple resolutions
- see how hard it would be to incoporate it in threex-aruco.js
- source ~/webwork/emsdk/emsdk_env.sh