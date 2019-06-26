# 软件工程概述

## 软件

### 软件的定义

**软件 = 程序 + 数据 + 文档**

* **程序      按事先设计的功能和性能需求执行的指令序列 ,  是可执行部分**
* **数据      是程序能正常操纵信息的数据结构   , 是不可执行部分**
* **文档      与程序开发, 维护 和 使用有关的图文材料    , 是不可执行部分**

### **软件的特征**

* 软件是开发的 或者是工程化的, 并不是制造的.
* 软件的生成是简单的拷贝.
* 软件会多次修改.
* 软件开发环境对产品影响较大.
* 软件开发事假讷河工作量难以估计.
* 软件的开发进度几乎没有客观衡量标准.
* 软件测试非常困难.
* 软件不会磨损和老化.
* 软件维护易产生新的问题.

### 软件的双重作用

* **一方面是一种产品**
  * 提供计算能力
  * 产生, 管理, 获取, 修改, 显示或传输信息.
* **另一方面是开发其他软件产品的工具**
  * 支持或直接提供系统所需的功能
  * 控制其他程序 \( 如操作系统\)
  * 改善通信 \(如网络软件\)
  * 帮助开发其他软件 \(如软件开发工具\)
  * 其他功能....

### **软件的分类**

#### **按软件功能分类**

* **系统软件**
  * 操作系统
  * 数据库管理系统
  * 设备驱动程序
  * 通信处理程序  等.
* **支撑软件**
  * 文本编辑程序
  * 文本格式化程序
  * 磁盘或磁带间数据传输的程序
  * 程序库系统
  * 支持需求分析, 设计, 实现, 测试 和 支持管理 的软件.
* **应用软件**
  * 商业数据处理软件
  * 工商与科学计算机软件
  * 计算机辅助设计 / 制造 软件
  * 系统仿真软件
  * 智能产品嵌入软件
  * 医疗 , 制药 软件
  * 事务管理,  办公自动化软件.
  * 计算机辅助教学软件

#### **按服务对象分类**

* **项目软件**
  * 来自于具体范围内的客户集合  \(定制\)
* **产品软件**
  * 面对数量更为庞大的客户群体

### 软件的发展

![&#x53D1;&#x5C55;](.gitbook/assets/image%20%28152%29.png)

#### 软件规模越来越大

![](.gitbook/assets/image%20%28171%29.png)

![](.gitbook/assets/image%20%2877%29.png)

## 软件危机

**软件危机:  在计算机软件的开发和维护过程中所遇到的一系列严重问题.**

* **项目超出预算**
* **项目超过计划完成时间**
* **软件运行效率很低**
* **软件质量差**
* **软件通常不符合要求**
* **项目难以管理 并且代码难以维护**
* **软件不能及时交付**

### **软件成本日益增加**

![](.gitbook/assets/image%20%2862%29.png)

### **软件技术进步  &lt;  需求增长**

![](.gitbook/assets/image%20%28116%29.png)

### **产生软件危机的原因**

*  **客观  :  软件本身特点**
  * 逻辑部件
  * 规模庞大
* **主观  :  不正确的开发方法**    
  * 忽视需求分析
  * 错误认为 :  软件开发 = 程序编写
  * 轻视软件维护

### **消除软件危机的途径 : 软件工程**

![](.gitbook/assets/image%20%28124%29.png)

\*\*\*\*

## 软件工程的概念与发展

### 软件工程的定义

**IEEE 计算机协会将软件工程定义为 :  \(1\) 应用系统化的, 学科化的, 定量的方法, 来开发, 运行和维护软件, 即 ,将工程应用到软件.**

### **软件工程的目标**

**软件工程的目标欧式在给定的时间和预算内  按照用户的需求,开发  易修改,高效,可靠,可维护,适应力强, 可移动, 可重用的软件.**

### **软件工程三要素:  方法, 工具, 过程**

* **工具**
  * 它为软件工程的过程和方法提供自动化或半自动化工具支持. 集成的软件工程工具再加上人的因素构成了软件工程环境. \(如 VS, Xcode, QT ...\)
* **方法**
  * 软件工程方法是完成软件工程项目的技术手段. 它支持项目计划和评估, 系统和软件需求分析, 设计, 编程, 测试和维护.  软件工程方法依赖一组原则, 它贯穿软件工程的各个环节. 软件工程方法分两类:  结构化方法 和 面向对象方法.
* **过程**
  * 过程贯穿软件开发的各个环节, 在各环节之间建立里程碑.  **管理者**在软件工程过程中对软件开发的质量, 进度, 成本进行评估, 管理和控制;  **技术人员**采用相应的方法和工具生成软件工程产品 \(模型, 文档, 数据, 报告, 表格 等\).
* **质量焦点**

![&#x8F6F;&#x4EF6;&#x5DE5;&#x7A0B;&#x5C42;&#x6B21;&#x56FE;](.gitbook/assets/image%20%28146%29.png)

### 软件工程的发展已经历了四个重要阶段

**传统软件工程  ---&gt;  对象工程  ---&gt;  过程工程   ---&gt;  构建工程**

![&#x56DB;&#x4E2A;&#x9636;&#x6BB5;](.gitbook/assets/image%20%28154%29.png)

![](.gitbook/assets/image%20%2838%29.png)

### **软件工程的7个原则**

1. **使用阶段性生命周期计划的管理**
2. **进行连续的验证  \(测试工作今早开始\)**
3. **保证严格的产品控制**
4. **使用现代编程 工具 / 工程  实践**
5. **保持清晰地责任分配**
6. **用更好更少的人**
7. **保持过程改进**

\*\*\*\*

## 软件工程知识体系与职业道德

![&#x5341;&#x4E2A;&#x77E5;&#x8BC6;&#x57DF;, &#x5206;&#x4E3A;&#x4E24;&#x7C7B;&#x8FC7;&#x7A0B;\(&#x5F00;&#x53D1;&#x548C;&#x7EF4;&#x62A4;&#x8FC7;&#x7A0B;, &#x652F;&#x6301;&#x548C;&#x7EC4;&#x7EC7;&#x8FC7;&#x7A0B;\)](.gitbook/assets/image%20%28184%29.png)

### 软件工程知识体系各主体之间的关联

![&#x5173;&#x8054;](.gitbook/assets/image%20%2856%29.png)

### 软件工程是一门交叉学科

![](.gitbook/assets/image%20%28189%29.png)

### **软件工程与计算机科学的区别**

![](.gitbook/assets/image%20%28121%29.png)

![](.gitbook/assets/image%20%28123%29.png)

### **对软件工程的误解**

![&#x7BA1;&#x7406;&#x65B9;&#x7684;&#x8BEF;&#x89E3;](.gitbook/assets/image%20%2865%29.png)

![&#x5BA2;&#x6237;&#x65B9;&#x7684;&#x8BEF;&#x89E3;](.gitbook/assets/image%20%28109%29.png)

![&#x51C6;&#x5B88;&#x8F6F;&#x4EF6;&#x5DE5;&#x7A0B;&#x89C4;&#x8303;](.gitbook/assets/image%20%28130%29.png)

### **软件工程职业道德和责任规范**

![](.gitbook/assets/image%20%28195%29.png)

\*\*\*\*

\*\*\*\*

\*\*\*\*

\*\*\*\*

\*\*\*\*

\*\*\*\*

\*\*\*\*

\*\*\*\*

