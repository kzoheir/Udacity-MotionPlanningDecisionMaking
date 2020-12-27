
Itried to build on Workspace and on my machine it's not working:Workspace:fatal error: uWS/uWS.h: No such file or directory #include <uWS/uWS.h>

**Details:**

Workspace:

/home/workspace/nd013-c5-planning-starter/project/starter_files/main.cpp:46:10: fatal error: uWS/uWS.h: No such file or directory

#include <uWS/uWS.h>

PC:

make[2]: *** No rule to make target '/usr/src/gtest/libgtest.a', needed by 'spiral_planner'. Stop.

make[1]: *** [CMakeFiles/Makefile2:76: CMakeFiles/spiral_planner.dir/all] Error 2

make: *** [Makefile:84: all] Error 2

Then: I copied

[ 9%] Linking CXX executable spiral_planner

/usr/bin/ld: cannot find -llapack

collect2: error: ld returned 1 exit status

make[2]: *** [CMakeFiles/spiral_planner.dir/build.make:232: spiral_planner] Error 1

make[1]: *** [CMakeFiles/Makefile2:76: CMakeFiles/spiral_planner.dir/all] Error 2

make: *** [Makefile:84: all] Error 2

Note: In the github I removed the:

eigen-3.3.7
libcarla-install
rpclib

