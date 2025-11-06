# The Rules of Programming - How to Write Better Code
### This was compiled using Clang++/LLVM as follows:

clang version 19.1.3 (https://github.com/llvm/llvm-project.git)
Target: x86_64-unknown-linux-gnu
Thread model: posix
InstalledDir: /home/kei/local/llvm19-assert/bin
Build config: +assertions

rule1.cpp -----------------------------------------------------------

Diff
```
diff --git a/rule1.cpp b/rule1.cpp
index 784d306..b9f12b7 100644
--- a/rule1.cpp
+++ b/rule1.cpp
@@ -1,4 +1,4 @@
-
+#include <cstdlib>
 #include <vector>
 #include <unordered_map>
 #include <assert.h>
```

Build
```
clang++ main.cpp tests.cpp rule1.cpp -o rule1
```

rule2.cpp:-----------------------------------------------------------

Diff
```
diff --git a/rule2.cpp b/rule2.cpp
index 5695489..ccdbb86 100644
--- a/rule2.cpp
+++ b/rule2.cpp
@@ -1,4 +1,4 @@
-
+#include <climits>
 #include <vector>
 #include <algorithm>
 #include <assert.h>
```

Build
```
clang++ main.cpp tests.cpp rule2.cpp -o rule2
```
