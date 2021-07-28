This is a demo tool that uses PhASAR as a library. The number of phasar libraries explicitly stated in CMakeLists.txt can be further reduced by stating the non-transitive dependencies of phasar libraries. This is pending work on the PhASAR side.

The demo tool has been adjusted to produce only the callgraph. Although it ends with a segmentation fault, the callgraph of the .ll file is written in a text file before the abrupt termination.

**Example**
myphasartool test1.ll

**Output**
Segmentation fault on console. Callgraph written in test1_callgraph.txt


**Installation**
mkdir build
cd build
cmake ..
sudo make install
