# LLIDynErrInj
A repository containing dirty modification of LLVM interpreter for dynamic error injection
This modification is done by Naveed Ul Mustafa
==================================================
In this modification, LLVM interpreter is modified in a dirty quick way to achieve following target
1) ENabling error injection for insruction
2) Enable the selection of instructions based on opcode for error injection
3) Enable the selection of field within the selected instruction for error injection

All those lines which are not part of original code are augmented with a comment line like this
//addded by Naveed 
or
//modified by Naveed
so you can easily terack all modification by searching for Naveed.
 To use this modification, simply copy this whole folder/repository in llvm/lib/ExecutionEngine/Interpreter (overwrite already exsiting source files) and recompile llvm.

Important Note: These modifications are yet not completed, so code is not in best shape. In case of questions, you can reach me at naveed.mustafa@bilkent.edu.tr




