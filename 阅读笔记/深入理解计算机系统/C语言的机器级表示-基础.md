# C语言的机器级表示-基础

## 因特尔处理器的发展历史

1. 主导了笔记本、台式、服务器市场
2. 先进设计，向后兼容直到8086处理器，随着时间的推移增加了很多新特性
3. 设计了复杂指令集，在不考虑功率的情况下，精简指令集的性能无法匹配

### x86的发展里程碑

8086

386

奔腾4E

Core 2

Core i7

> 新增功能
>
> 支持多媒体操作指令、启用更高效的条件操作指令、支持32到64位转换、多核心

### 后起之秀AMD



## C语言、汇编、机器语言之间的关系

### 指令集架构（[instruction set architecture](https://en.wikipedia.org/wiki/Instruction_set_architecture)）

> 一个给定的ISA可以用不同的微架构实现

包含如下：

The ISA includes the [instructions](https://en.wikipedia.org/wiki/Instruction_set_architecture#Instructions), [execution model](https://en.wikipedia.org/wiki/Execution_model), [processor registers](https://en.wikipedia.org/wiki/Processor_register), address and data formats among other things;

### 微架构

> 微架构就是ISA的实现，需要实现各组件之间的互联、相互操作

#### 指令流水线



#### 执行单元

- 算术逻辑单元ALU
- 浮点单元FLU
- load/store units
- branch prediction
- [SIMD](https://en.wikipedia.org/wiki/Single_instruction,_multiple_data)

### 微架构概念

#### 指令周期

#### 多周期微架构

#### 提高执行速度

#### 指令集选择

#### 指令流水线

#### CPU 缓存

#### 分支预测

#### 超标量

#### 分支预测

#### Register renaming

#### 多进程&多线程



