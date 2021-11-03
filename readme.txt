1）win32版本问题
第三方库均为64版本，请使用x64编译。
另外在Configuration Properties->Linker->Command Line->Additional Options, 把X86改为X64

2）debug版本中freeglutd.lib问题
Configuration Properties->C/C++->Preprocessor->Preprocessor Definitions, 添加NDEBUG，使用release库