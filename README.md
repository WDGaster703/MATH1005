# MATH1005 - 复变函数与积分变换

![Static Badge](https://img.shields.io/badge/(2023秋之前)考试课-red)
![Static Badge](https://img.shields.io/badge/(2024秋之后)考查课-green)
![Static Badge](https://img.shields.io/badge/%E5%AD%A6%E5%88%86-2.5-moccasin)

![Static Badge](https://img.shields.io/badge/%E6%88%90%E7%BB%A9%E6%9E%84%E6%88%90-gold)
![Static Badge](https://img.shields.io/badge/%E4%BD%9C%E4%B8%9A-20%25-wheat)
![Static Badge](https://img.shields.io/badge/%E6%9C%9F%E6%9C%AB%E8%80%83%E8%AF%95-80%25-wheat)

## 教材和参考书

- 复变函数与积分变换 / 包革军、邢宇明、盖云英编–3版.–北京：科学出版社，2013.3，ISBN:978-7-03-036913-0

- 复变函数与积分变换简明教程 / 包革军、邢宇明、宋威、凌怡编–北京：科学出版社，2020.12，ISBN：978-7-03-064742-9

- 复变函数 / 史济怀、刘太顺 著–安徽：中国科技大学出版社，1998.12，ISBN：978-7-31-200999-0

- _Complex Analysis_ - Stein & Shakarchi

## 授课教师
- 包益欣
  - 教学风格：待补充
  - 听课建议：待补充

- 高瑜
  - 教学风格：纯板书，上课后会把他的讲义发到群里。「slides/2024复变函数与积分变换讲义-高瑜老师.pdf」
  - 听课建议：强烈听课，老师上课真的特别好。
  > 特别好的老师，老师上课逻辑特别清晰，板书非常有条理，而且老师也特别有耐心，学生听不懂时他会停下来重新解释。而且课后也会给同学详细解答疑问。文 / [Gaster](https://github.com/WDGaster703)，2025.1

> [!NOTE]
> 2025.1 补充：包老师已经不在深圳任教，但是包老师对深圳校区作出很大贡献，仍保留。
- 包革军
  - 校用教材《复变函数与积分变换 简明教程》的编者之一
  - 关于他的描述，在 [微积分 B](https://hoa.moe/docs/fresh-spring/math1015b/) 中已经提到过了。不会考勤。

    > 超级好的老师，都给我去听他的课 😭。平时和考前会安排线下答疑。 文 / [Maxwell Jay](https://github.com/MaxwellJay256)
    
    > 附议，很好的老师。 文 / [Hye](https://github.com/Co-ding-Man)
    
    > 同意，他真的对学生非常负责，他也是我到目前唯一去过线下答疑的老师。 文 / [psp_dada](https://github.com/pspdada)，2024.7.12

## 关于考试

2018 到 2020 年的考试难度都非常低，2021 年后考试难度相对高了一些，之后考试题难度变化不大。

考试的总体难度比起微积分、线性代数这些要简单许多，并且很多课上很难的知识在考试中考得非常简单（例如傅里叶变换和拉普拉斯变换对，只考了非常基础的那几个）。

对于中等水平以上的学生，这应该是相当容易拿高分的数学课。

## 学习建议

其实大家对复变函数应该不会陌生，因为在 [电路 IA](https://github.com/HITSZ-OpenAuto/EE1011A) 中，我们已经学过在频域上求解正弦电路和用拉普拉斯变换解决电路暂态响应的问题。这两部分内容都属于复变函数和积分变换的应用。

教材可以用《复变函数与积分变换 简明教程》，也可以用《复变函数与积分变换》（不简明教程），但使用简明教程不会影响学习效果（主要还是以课上为主）[^1][^2]。

整个课程的教学内容相比微积分等要少很多，个别地方的内容相对比较难理解，作业难度比考试高很多（有很多证明题），因此期末复习时还是以往年的考试题为主，不要太过于纠结于作业题。

此外建议多和老师交流问题，直接问老师比起在学生群里和同学讨论的效率会高很多。我期末前找 bgj 聊了两次天之后感觉收获比在自救群里盯梢一个星期还大。

最后抛开考试，这门课的内容与后面的专业课关联还是很强的（你在 [电路 IA](https://github.com/HITSZ-OpenAuto/EE1011A) 中已经体会过一次了），因此还是要好好学习。

>  文 / [Maxwell Jay](https://github.com/MaxwellJay256), 2023.11

如前所述，《复变函数与积分变换》这门课是后续许多专业课的基础。特别是傅里叶变换与拉普拉斯变换，是十分常用且有用的工具。但由于课时有限，与自动控制理论相关的一些经典内容，比如奈奎斯特稳定性判据的数学基础——辐角原理等，在“简明教程”中没有得到介绍。

这门课难点在于理解、证明，但又由于是工科数学课程，其实并不很为难大家。具体表现为考试题比作业题要简单不少。对于不满足于应试、想要加深理解的同学来说，仔细理解经典命题的证明过程，体会其中的思想方法，是很有帮助的。当然，对于工科同学而言，计算是基本功，通过一定的量的练习，需要能熟练掌握常见的积分变换对以及常用的方法、性质。~~你也不想到时候求不出二阶系统的阶跃响应时域表达式吧。~~

关于这门课的内容，我写过一份讲义（已上传至该项目中），依照“简明教程”的结构，涵盖其中的第 2-5 章，相对基础，自认为足以用于梳理课内主干内容。此外，包益欣老师的讲义内容丰富，相较于教材更具深度，对学习这门课很有帮助；2020 级大数据专业一位同学写过一份《复变函数简明教程的简明教程》（同上），也很不错，比我的讲义写得好。

> 本书适用于需要快速查看定理的同学，以及想要对数学增进一些了解的工科同学，和想要稍微预习或者复习一下复变函数的同学。 ——《复变函数简明教程的简明教程》

> 文 / [Hye](https://github.com/Co-ding-Man), 2023.12

对于自动化、电气等专业的工科生来说，复变函数和积分变换是贯穿大学生涯的两个很重要的部分：

- 复变函数部分给出了复数的相关概念、定理、性质以及最关键的**留数定理**。在大三的自动控制原理等课中都会直接用到留数定理。
- 积分变换部分给出了日后处处都能用到但是再也不会当作重点来讲的**傅里叶变换**和**拉普拉斯变换**。这两个变换是后面自动控制原理、信号分析与系统等课程的基础，也是工科生必须要掌握的知识。

这门课的内容相对于微积分这门课程来说，难度不大，但是需要花费一定的时间去理解和记忆。因此，即使这门课在一些情况下变成了考查课，若后续还有相关课程，建议还是要好好学习。

> 文 / [psp_dada](https://github.com/pspdada), 2024.12

[^1]: 《复变函数与积分变换 简明教程》相较于《复变函数与积分变换》（第 3 版）进行了一些精简，具体有：删去了“保形映射”一章，省略了解析函数的物理意义、相关函数、傅里叶变换的应用、多维傅里叶变换、辐角原理与儒歇定理等内容。这些内容有的是较深入的理论知识，有的是较实际的应用场景，对于巩固复变函数与积分变换知识其实是有帮助的，如果是按照“简明教程”学习的同学，可以自行学习了解这些内容。删去后，使得内容更加精简、基础，便于压缩课时（这也正是“简明”的目的之一）。
[^2]: 简明教程相比不简明教程，全书在定理、公式上有更多错误并且难以发现，因此不推荐。

