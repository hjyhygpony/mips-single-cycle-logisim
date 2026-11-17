# MIPS Single-Cycle Processor in Logisim

使用 Logisim 实现单周期 MIPS 处理器，是计算机组成原理课内大作业的独立版本。

## 内容

- `mips-single-cycle.circ`：Logisim 处理器电路
- `IFU.asm` / `IFU.txt`：取指单元测试程序与指令数据
- `p1-test.asm` / `p1-test.txt`：MIPS 测试程序与机器码
- `question.txt`：实验要求摘要

## 电路结构

- 程序计数器 PC
- 指令存储器 IM
- 通用寄存器堆 GPR
- ALU
- 立即数扩展单元
- 数据存储器 DM
- 主控制器
- 指令字段拆分与写回控制

## 运行

1. 安装 Logisim Evolution 或其他兼容 Logisim 的版本。
2. 打开 `mips-single-cycle.circ`。
3. 加载程序数据并运行时钟。
4. 观察 PC、寄存器、ALU 和数据存储器变化。

## 说明

- `.circ` 文件已经过 XML 格式检查。
- 仓库不包含 Logisim 安装包、课程报告或其它课程的实验资料。
- 本项目只实现单周期处理器，多周期、中断和 FPGA 版本见 `mips-processor-course-design`。
