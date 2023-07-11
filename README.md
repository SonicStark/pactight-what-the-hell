# Developer friendly PACTight

This repository contains a developer friendly version of source code for the USENIX Security'22 paper:

*"Tightly Seal Your Sensitive Pointers with PACTight
Mohannad Ismail, Andrew Quach, Christopher Jelesnianski, Yeongjin Jang, Changwoo Min
In Proceedings of the 31st USENIX Security Symposium (USENIX Security 2022)*

Only modified stuffs are preserved in this repository, so that developers can quickly inspect its implementation.

 * `diff-output.txt` - Output of diff (already re-organized) against PACTight/llvm-project and Apple's LLVM (swift-5.3.1-RELEASE).
 * `llvm-project` - All stuffs that PACTight modified (the deleted is excluded).
 * `CMakeLists.txt` - CMake file for building PACTight (keep as-is).
 * `example` - Example code (keep as-is).
