**这是一个LC-3工具，是ICS课程的附加实验，实现了LC-3的汇编器与虚拟机，支持特权模式、内存映射IO、键盘中断**
\
使用方法：\
\
Assembler:将LC-3汇编代码每行作为一个std::string载入std::vector<std::string>后传入assemble方法，返回一个std::vector<std::string>，其中每个std::string为一行LC-3机器码
\
Simulator:将LC-3机器码每行作为一个std::string载入std::vector<std::string>后传入load方法将其加载进虚拟机内存，然后用run方法运行
