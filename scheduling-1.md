
# 2023年春夏季开源操作系统训练营：第一阶段

- [新闻与纪要](./news.md)
- [常见问题解答](./QA.md)
- [Learning Resource](./relatedinfo.md) (训练营学习资源)
- Online Ranking （训练营在线排行榜）
  - [第一阶段排行：Rust Lang](https://learningos.github.io/classroom-grading/)

欢迎在校学生/工程师在2023年春夏季参加清华大学、CSDN、毛豆教育等共同举办的**2023年春夏季开源操作系统训练营**活动（2022.04.01～2023.08.01），本次活动分为两个阶段：

- 第一阶段：（2023.04.01～2023.05.01）线上自学Rust编程和OS基础，并进行[Rust语言编程自学](https://github.com/LearningOS/rust-based-os-comp2022/blob/main/scheduling.md#step-0-%E8%87%AA%E5%AD%A6rust%E7%BC%96%E7%A8%8B%E5%A4%A7%E7%BA%A6714%E5%A4%A9)、[Rust语言编程实验](https://github.com/LearningOS/rustlings)、[RISC-V处理器学习](https://github.com/LearningOS/rust-based-os-comp2022/blob/main/scheduling.md#step-1-%E8%87%AA%E5%AD%A6risc-v%E7%B3%BB%E7%BB%9F%E7%BB%93%E6%9E%84%E5%A4%A7%E7%BA%A627%E5%A4%A9)
- 第二阶段：（2023.05.01～2023.07.01）OS内核学习与实验
  - [C-based uCore Tutorial Kernel学习&实验](https://github.com/LearningOS/uCore-Tutorial-Guide-2023S)
  - [Rust-based rCore Tutorial Kernel学习&实验](https://github.com/LearningOS/rCore-Tutorial-Guide-2023S)
- 可选：（2023.07.01～2023.08.20）竞赛级训练：[OS Kernel supporting Linux Apps实验](https://github.com/LearningOS/oscomp-kernel-training) ,主要是**用Rust语言设计实现支持Linux APP的OS Kernel**，大约要支持<100个左右的Linux Syscalls，能通过上百个Linux App测试用例。如果有其它有趣的想法或愿意参加更有挑战的训练（比如实现支持Rust协程的OS，支持unikernel&微库形态的OS等），请与助教和老师联系。

如有兴趣参加，请在2023年04月01日前请在[报名登记处]()填写相关个人信息，并加入[相关微信群]()。获得邀请后，将开始参与本次训练营活动。完成本次活动第一阶段（2023.04.01～2023.05.01）的同学如果通过review，将可在2023.05.01～2023.07.01，开展第二阶段[OS Kernel supporting Linux Apps实验](https://github.com/LearningOS/oscomp-kernel-training)。训练营结束后，部分表现突出的同学将获得训练营优秀证书。鼓励同学继续以开源社区的方式参与到企业/科研院所的操作系统实习/实践/工作/学习等相关的活动。

> 我们也在持续探索和改进开源操作系统训练营，即这个活动不仅仅局限在 2022.11.01～2023.02.01。我们希望建立的是一种长期持续发展的操作系统训练营模式，即各种学习资源都开源并整理集中在一起，导师/助教和学生/爱好者之间基于要做的实验或项目不定期/定期的进行交流。学生/爱好者完成了一定程度的学习和训练后，除了自身得到能力的提升外，还可获得相关证书和就业/学习等机会和相关推荐等，推动他在未来的进一步发展。

## 目标：

**培养具有开源思想的合作者，搭建开源合作平台。**

**探索把现代系统语言Rust和灵活开放的系统结构RISC-V带入到操作系统的架构与设计的创新中来，思考未来的操作系统应该是什么样。**

## 宗旨：

**希望本活动的组织，能为操作系统爱好者提供一个活跃的开源社区环境，为对Rust、RISC-V和操作系统感兴趣的人士营造一个平等的学习与交流空间，吸引更多对操作系统感兴趣的人士参与。**

## 相关信息：

- [参加2020--2022 OS训练营学生的blog](https://rcore-os.github.io/blog/)，鼓励参加2023 OS训练营的同学把自己在学习过程中的感悟/收获等写成blog，生成pr，并提交到 <https://github.com/rcore-os/blog> 上，让更多人看到你的进步！
- **注意** 为及时了解和指导同学的学习和实践情况并推动学生相互帮助，本次活动要求学生把每周学习实践的过程记录（Markdown格式）放在github上自己的公开repo中。可参见[每日学习实践的具体例子](https://github.com/GCYYfun/DailySchedule)和[2020年OS训练营同学的每日学习情况汇总](https://github.com/rcore-os/rCore-Tutorial/issues/18 ) 。请参加实习的同学把记录每天的进展的git repo网址 更新到[2023年OS训练营同学的每日学习情况汇总](https://github.com/LearningOS/rust-based-os-comp2023/issues/1) 中。要求每位同学在自己的git repo中记录自己的每周进展，其他同学也可以参考学习。
- **注意** 第一阶段学习中的技术问题，建议基于[OS训练营github discussion](https://github.com/LearningOS/rust-based-os-comp2023/discussion) 发出并讨论。


## 第一阶段活动安排

### 总体学习要求和成绩考核方式

- 在[学习实践过程记录表](https://github.com/LearningOS/rust-based-os-comp2023/discussions/170)上登记自己每日/周学习记录情况的repo网址，并在这个repo上记录每日/周学习记录情况  (成绩分数：20%)
  - [学习记录的标杆1](https://github.com/LearningOS/record)，浙江大学本科生徐文浩的2020开源操作系统训练营的过程记录，是大家学习的榜样，供大家学习参考。
  - [学习记录的标杆2](https://kiprey.github.io/tags/uCore/)：湖南大学本科生肖政杭的自学ucore for x86的过程记录，是大家学习的榜样，供大家学习参考。

- 在[第一阶段学习的讨论](https://github.com/LearningOS/rust-based-os-comp2023/discussions/)上的提问和回答问题情况 (成绩分数：30%)
- 要求的[Rust-lang Lab Test based on Rustlings（采用Github Classroom模式的Rustling小练习）](https://classroom.github.com/a/U37u3veU) 的完成情况 (成绩分数：70%)


#### step 0 自学rust编程（大约7~14天）

前提条件： 要求有基本数据结构，算法基础，相对了解或熟悉C语言等编程.

1. 自学基础知识：[阅读书籍/课程/视频等资源汇总](https://github.com/rcore-os/rCore/wiki/study-resource-of-system-programming-in-RUST)

   - 推荐：[Rust语言圣经(Rust教程 Rust Course和配套练习)](https://course.rs/)
   - 推荐：[Rust速查表（cheatsheet）](https://cheats.rs/) 该项目不仅提供了基础的语法速查，还有执行顺序详解和编写时需要关注的注意事项。项目还包含了示例代码（EX）、书籍（BK）、标准（STD）等相关资料的扩展。
   - 推荐：[清华计算机系大一学生2022暑期课程：Rust程序设计训练（有课程视频）](https://lab.cs.tsinghua.edu.cn/rust/)

2. 自学编程

   - [Rust-lang Lab Test based on Rustlings](https://classroom.github.com/a/U37u3veU)（采用Github Classroom模式的Rustling小练习，点击上述链接，形成自己的练习用repo）
     - 要求：**必须完成** 。每完成几个小练习，就执行 ``git add; git commit -m"update"; git push`` 命令，把更新提交到GithubClassroom的CI进行自动评测。要求小练习全部通过GithubClassroom的CI自动评测。
     - [学习系列视频：Rust中文社群线上学习室--通过 Rustlings 学 Rust](https://space.bilibili.com/24917186/video)

       **提示：基于github classroom的开发方式**

       基于github classroom，可方便建立开发用的git repository，并可基于github的 codespace（在线版ubuntu +vscode）在线开发使用。整个开发环境仅仅需要一个网络浏览器。

       > codespace 不是必须的。如果是本地的ubuntu中建立开发环境，可在shell中执行 `make ubuntu_local_setenv` 来自动安装配置开发环境（执行需要 `sudo` root 权限，仅需要执行一次）。

       1. 在网络浏览器中用自己的 github id 登录 github.com。
       2. 接收 [Rust-lang Lab Test based on Rustlings 的github classroom在线邀请](https://classroom.github.com/a/U37u3veU)  ，根据提示一路选择OK即可。
       3. 完成第二步后，你的rustings实验练习 的 github repository 会被自动建立好，点击此github repository的链接，就可看到你要完成的实验了。
       4. 在你的第一个实验练习的网页的中上部可以看到一个醒目的 `code`  绿色按钮，点击后，可以进一步看到 `codespace` 标签和醒目的 `create codesapce on edu` 绿色按钮。请点击这个绿色按钮，就可以进入到在线的ubuntu +vscode环境中
       5. 再按照下面的环境安装提示在vscode的 `console` 中安装配置开发环境：rustc等工具。
       6. 然后就可以基于在线vscode进行测试 (执行命令 `rustlings watch` ），编辑代码的循环实验过程了。

   - （Option）[32 Rust Quizes](https://dtolnay.github.io/rust-quiz/1)
     - 要求：小练习全部通过。（**非必须完成**）
   - （Option）[exercisms.io 快速练习(88+道题目的中文详细描述)](http://llever.com/exercism-rust-zh/index.html)
     - 要求：大部分练习会做或能读懂。（**非必须完成**）
     - [exercism.io官方站点](https://exercism.io/)

#### step 1 自学risc-v系统结构（大约2~7天）

前提条件：要求有基本计算机组成原理，计算机系统结构基础。

阅读《计算机组成与设计（RISC-V版）》第一、二章，可以在整体结构上对 RISC-V 体系建立基本认知。再进行后面的学习比较有效果。

#### 自学材料和练习要求:

1. 阅读书籍和在线课程

   - 自学[PPT for RISC-V特权指令级架构](https://content.riscv.org/wp-content/uploads/2018/05/riscv-privileged-BCN.v7-2.pdf)
   - 自学[RISC-V手册：一本开源指令集的指南](http://riscvbook.com/chinese/RISC-V-Reader-Chinese-v2p1.pdf) 重点是第10章
   - （Option）自学[RIS-V特权指令级规范](https://riscv.org/technical/specifications/) 重点是与OS相关的特权硬件访问的规范内容（Privileged Spec）
   - （Option）自学[RISC-V汇编手册](https://github.com/riscv-non-isa/riscv-asm-manual/blob/master/riscv-asm.md)
   - （Option）[计算机组成与设计：RISC-V 教材](https://item.jd.com/12887758.html) 这是完整的课程教材，不要求全部看完，请根据自己的需求选择。
   - （Option）[计算机组成与设计：RISC-V 浙大在线课程](http://www.icourse163.org/course/ZJU-1452997167) 这是完整的一门课，不要求全部看完，请根据自己的需求选择。

2. 其他参考学习信息

   - （Option）[Berkeley CS61C: Great Ideas in Computer Architecture (Machine Structures)](http://www-inst.eecs.berkeley.edu/~cs61c/sp18/)

   > Option的含义是：如果有足够的时间建议看看，否则在后续要用到时或需要查询进一步信息时再查阅这些内容。

3. 通过要求

   - 掌握RUST编程，理解RISC-V与OS相关的硬件特性（中断，异常，系统调用，寄存器，特权级，MMU...）。

One More Thing：当你看到这，感觉第一阶段还没开始，还在想下一步要干啥时，我们的建议是：**Just Do It NOW!**
