第一章：随机事件
- 1.1 样本空间和随机事件 (Sample Space and Random Events) P4-5 1, 2, 4
  - 样本空间 (Sample Space):
    - 解释： 一个实验所有可能的结果的集合。就像一个“结果清单”，列出所有可能性。
    - 示例： 抛一枚硬币，样本空间是 {正面，反面}；掷一个骰子，样本空间是 {1, 2, 3, 4, 5, 6}。
  - 随机事件 (Random Event):
    - 解释： 样本空间的一部分，即实验结果的某个集合。它描述了我们感兴趣的实验结果。
    - 示例： 掷骰子出现偶数（即{2, 4, 6}）是一个随机事件；抛硬币出现正面是一个随机事件。
- 1.2 事件的关系和运算 (Relationships and Operations of Events) P6-7 1, 4, 5, 6, 8
  - 事件的关系 (Relationships of Events):
    - 解释： 事件之间的关系，比如一个事件是否包含另一个事件、事件是否会同时发生等。
    - 示例：
      - 包含关系: 如果事件 A 是“掷骰子出现大于 3 的点数”，事件 B 是“掷骰子出现 6”，那么 A 包含 B。
      - 互斥关系: 如果事件 A 是“掷骰子出现偶数”，事件 B 是“掷骰子出现奇数”，那么 A 和 B 互斥（不能同时发生）。
      - 对立关系： 如果事件A是掷骰子出现偶数，那么事件A的对立事件是掷骰子出现奇数。
  - 事件的运算 (Operations of Events):
    - 示例：
      - 并 (A∪B): “事件 A 或事件 B 发生”。比如，事件 A 是“掷骰子出现偶数”，事件 B 是“掷骰子出现大于 4 的点数”，A∪B 是“掷骰子出现偶数或大于4 的点数”。
      - 交 (A∩B): “事件 A 和事件 B 同时发生”。比如，事件 A 是“掷骰子出现偶数”，事件 B 是“掷骰子出现大于 4 的点数”，A∩B 是“掷骰子出现大于4 的偶数”，即掷骰子出现6。
      - 补 (A̅): “事件 A 不发生”。比如，事件 A 是“掷骰子出现偶数”，A̅ 是“掷骰子出现奇数”。
第二章：事件的概率
- 2.2 古典概型 (Classical Probability) P18-19 1, 3
  - 解释： 当所有结果都是等可能时，一个事件的概率等于该事件包含的结果数除以总的结果数。
  - 示例： 掷一个均匀的骰子，出现 3 的概率是 1/6，出现偶数的概率是 3/6 = 1/2。
- 2.3 几何概型 (Geometric Probability) P19-20 1, 4, 5
  - 解释： 当结果对应于一个几何区域时，事件的概率等于该事件区域的大小除以总区域的大小。
  - 示例： 在一个半径为 1 的圆内随机选一点，该点落在内切正方形内的概率等于正方形的面积除以圆的面积。
- 2.4 概率的公理化定义 (Axiomatic Definition of Probability)
  - 解释： 概率必须满足的基本规则，确保概率的计算是合理的。
    - 非负性： 任何事件的概率不能是负数，总是大于等于0。
    - 规范性： 整个样本空间（所有可能的结果）的概率必须是1。
    - 可加性： 如果两个事件是互斥的（不能同时发生），那么它们并集的概率等于它们各自概率的和。
第三章：条件概率与事件的独立性
- 3.1 条件概率 (Conditional Probability) P29-30 1, 2, 3, 5, 7
  - 解释： 当我们知道某个事件已经发生时，另一个事件发生的概率。
  - 示例： 如果已知“你今天去上课了”，那么“你今天上课时带了课本”的概率，就是条件概率。
- 3.2 全概率公式 (Total Probability Theorem) P31-32 1, 2, 4, 5
  - 解释： 当我们把样本空间分成几个部分时，可以用这些部分计算整个事件的概率。
  - 示例： 一个工厂有两条生产线，第一条生产线生产 60% 的产品，其中 3% 为次品，第二条生产线生产 40% 的产品，其中 5% 为次品。要计算从工厂抽到的产品是次品的概率，就需要用全概率公式。
- 3.3 贝叶斯公式 (Bayes' Theorem) P32-34 3, 4, 6
  - 解释： 从已知结果反推原因的概率。
  - 示例： 知道某人检测结果是阳性，想反推他患病的概率，需要用到贝叶斯公式。
- 3.4 事件的独立性 (Independence of Events) P34-35 2, 3, 4, 6
  - 解释： 一个事件的发生不影响另一个事件发生的概率。
  - 示例： 抛两次硬币，第一次抛硬币的结果不影响第二次的结果，所以两次抛硬币的结果是独立的。
- 3.5 伯努利试验和二项概率 (Bernoulli Trials and Binomial Probability) P35-36 1, 3, 5
  - 解释： 一系列重复且独立的、只有两个可能结果的实验。
    - 伯努利试验: 每次试验只有两个可能的结果，成功或失败，而且每次试验的结果相互独立，比如抛硬币，每次抛硬币的结果（正面或反面）都是一个伯努利试验
    - 二项概率: 多次伯努利试验中，成功k次的概率，比如抛10次硬币，其中3次正面朝上的概率服从二项分布。
  - 示例： 抛硬币，每次抛出正面或反面；某产品出厂，要么是合格品，要么是不合格品。
第四章：随机变量及其分布
- 4.1 随机变量及分布函数 (Random Variables and Distribution Functions) P49-51 1, 3, 4
  - 随机变量 (Random Variable):
    - 解释： 一个变量，它的取值取决于随机实验的结果。随机变量的取值是变化的，不是固定的值
    - 示例： 抛硬币 3 次，正面出现的次数就是一个随机变量；一个班级里学生的考试成绩就是一个随机变量。
  - 分布函数 (Distribution Function):
    - 解释： 描述随机变量取值小于等于某个特定值的概率。
    - 示例： 比如，对于某个随机变量X，分布函数F(x)表示的是P(X<=x).
- 4.2 离散型随机变量 (Discrete Random Variables) P51-56 1, 2, 5, 8, 10, 15
  - 解释： 取值只能是有限个或可数无限个的随机变量，比如0，1，2，3....等。
  - 示例： 一天内进出图书馆的人数、一个篮球队在一场比赛中的得分、投掷骰子出现的点数。
    - 常用分布： 二项分布（多次伯努利实验成功的次数）、泊松分布（某段时间内发生的次数）
- 4.3 连续型随机变量 (Continuous Random Variables) P56-60 1, 2, 3, 5, 9, 10, 11, 12
  - 解释： 取值可以连续变化的随机变量，可以取任意实数。
  - 示例： 人的身高、体重、气温、灯泡的使用寿命。
    - 常用分布： 正态分布（钟形分布）、均匀分布（每个值出现的可能性相同）、指数分布（描述等待时间）
第五章：二维随机变量及其分布
- 5.2 二维离散型随机变量 (Two-Dimensional Discrete Random Variables) P74-77 1, 2, 3, 4
  - 解释： 研究两个离散型随机变量同时取值的概率分布。比如两个骰子点数的情况。
  - 示例： 同时掷两个骰子，得到的点数(X, Y)就是一个二维离散型随机变量
- 5.4 边缘分布 (Marginal Distribution) P78-81 1, 2
  - 解释： 从二维或多维随机变量的联合分布中，单独求某个随机变量的分布。可以看做对联合分布的压缩
  - 示例： 如果我们知道两个骰子的联合分布，那么我们可以利用边缘分布求出第一个骰子的点数的分布情况
- 5.5 随机变量的独立性 (Independence of Random Variables) P81-85 1, 2, 3
  - 解释： 两个随机变量互不影响，一个随机变量的值不会影响另一个随机变量的值。
  - 示例： 两次抛硬币的实验中，每次抛出的结果是相互独立的。
第六章：随机变量的函数及其分布
- 6.1 一维随机变量的函数及其分布 P102-106 1, 2, 3, 6, 7, 9
  - 解释： 如果已知随机变量X的分布情况，求g(X)的分布情况，其中g是X的函数。
  - 示例： 如果X表示一个随机变量，求X的平方分布
- 6.2 多维随机变量的函数及其分布 P106-110 1, 2, 4
  - 解释： 如果已知随机变量X, Y 的联合分布情况，求g(X, Y)的分布情况，其中g是X和Y的函数。
  - 示例： 如果X和Y表示两个随机变量，求X+Y的分布
第七章：随机变量的数字特征
- 7.1 数学期望与中位数 (Mathematical Expectation and Median) P134-138 1, 2, 8, 13, 16
  - 数学期望 (Expectation):
    - 解释： 随机变量取值的平均值，代表中心位置。可以认为是在重复多次实验的情况下，随机变量取值的平均值
    - 示例： 掷骰子的期望是3.5，表示多次掷骰子的平均值在3.5附近
  - 中位数 (Median):
    - 解释： 将随机变量的取值分成两半的那个值。
    - 示例： 如果一个班级学生的成绩中位数是80分，表示有一半学生的成绩低于80分，一半高于80分
- 7.2 方差和标准差 (Variance and Standard Deviation) P139-140 1, 3, 5, 8
  - 方差 (Variance):
    - 解释： 衡量随机变量取值相对于期望值的离散程度，也就是随机变量的波动范围。
    - 示例： 如果一个班级学生成绩方差较大，则表示学生之间的成绩差距比较大，反之如果方差较小，则表示学生之间的差距比较小
  - 标准差 (Standard Deviation):
    - 解释： 方差的平方根，更直观地描述数据的波动。
    - 示例： 标准差可以直观的表示数据的波动范围，例如，如果一组数据的平均值是50，标准差是10，说明数据大部分分布在40到60之间
- 7.3 协方差和相关系数 (Covariance and Correlation Coefficient) P140-142 1, 2, 5, 6
  - 协方差 (Covariance):
    - 解释： 衡量两个随机变量是否同步变化。
    - 示例： 人的身高和体重的协方差通常为正，表明身高越高，体重通常也越高
  - 相关系数 (Correlation Coefficient):
    - 解释： 标准化后的协方差，更容易描述两个随机变量线性关系的强弱。
    - 示例： 相关系数取值在-1到1之间，如果为1表示完全正相关，如果为-1表示完全负相关，如果为0表示不相关
- 7.4 切比雪夫不等式及大数律 (Chebyshev's Inequality and Law of Large Numbers) P142-143 1, 3
  - 切比雪夫不等式 (Chebyshev's Inequality):
    - 解释： 提供随机变量的取值与其期望偏差大小的概率界限。
    - 示例： 随机变量X的期望是0，方差是1，那么根据切比雪夫不等式，P(|X|>2) <= 1/4
  - 大数律 (Law of Large Numbers):
    - 解释： 当样本量足够大时，样本的平均值会趋近于总体的平均值。
    - 示例： 如果我们多次抛硬币，随着抛掷次数的增加，正面朝上的频率会越来越接近于50%
第八章：统计量和抽样分布
- 8.1 统计与统计学 (Statistics and Statistical Science): P161 2, 4
  - 解释： 统计学是一门关于如何收集、分析、解释和展示数据的科学。
- 8.2 统计量 (Statistic): P161-165 1, 2, 3
  - 解释： 从样本数据计算出来的量，用于估计总体参数。
  - 示例： 样本均值，样本方差，样本中位数等。
- 8.3 抽样分布 (Sampling Distribution): P166-168 1, 3, 6
  - 解释： 统计量的分布。例如，多次重复抽取样本计算得到的样本均值，这些样本均值形成的分布。
  - 示例： 如果从一个正态总体中随机抽取样本，那么样本均值服从正态分布
第九章：点估计
- 9.2 估计方法 (Estimation Methods): P178-182 1, 2, 4, 5, 6
  - 解释： 如何通过样本数据来估计总体的未知参数。
  - 示例： 矩估计，极大似然估计。
- 9.3 点估计的优良性 (Goodness of Point Estimator): P184-186 1, 2, 3, 6
  - 解释： 如何评估估计的质量。
  - 示例： 无偏性（平均来看估计值和真值相等），有效性（方差比较小），相合性（当样本量增加时，估计值越来越接近真实值）。
第十章：区间估计
- 10.2 正态总体下的置信区间 (Confidence Interval for Normal Population) P198-200 1, 3, 6
  - 解释： 如何给出总体参数的一个取值范围，并保证这个范围以一定的概率包含真实值。
  - 示例： 我们希望估计总体均值的置信区间，需要根据样本均值和样本方差，以及所要求的置信水平，来计算得到。
第十一章：假设检验
- 11.2 显著性水平检验法与正态总体检验 (Significance Level Testing and Testing for Normal Populations): P214-215 1, 2, 3, 5, 6
  - 解释： 如何通过样本数据，来判断关于总体的某个假设是否成立。
  - 示例： 验证某药品是否对某种疾病有效，或者某个生产线的合格率是否合格

- 集合运算：
  - 并集：$$A \cup B$$
    交集：A $$\cap$$B 或 $$AB$$
  - 差集：$$A - B$$
- 概率性质：
  - 互斥事件： $$P(A \cup B) = P(A) + P(B)$$ (如果 A,B 互斥)
  - 相互独立事件： $$P(AB) = P(A)P(B)$$ (如果 A,B 相互独立)
  - 补集：$$P(\overline{A}) = 1 - P(A)$$
  - 一般的并集： $$P(A \cup B) = P(A) + P(B) - P(AB)$$
  - $$P(A \cup B \cup C) = P(A) + P(B) + P(C) - P(AB) - P(AC) - P(BC) + P(ABC)$$
- 条件概率：
  - $$P(A|B) = \frac{P(AB)}{P(B)}$$
- 伯努利分布
  - 期望： $$E(X)=np$$
  - 方差： $$D(X) = np(1-p)$$
  - $$P(X=k)=C_n^k p^k(1-p)^{n-k}$$
- 随机变量的函数期望：
  - 例如： $$E(g(X))$$
- 离散型随机变量的分布函数：
  - $$F(x) = P(X \leq x)$$
- 事件的发生情况
  - P(A+B)发生一个事件  =$$P(A) + P(B) – 2P(AB)$$
    P(A $$\cup$$B)发生一个或者两个事件
- 一些推导公式
  - $$B = A B \cup \overline {A}B$$
  - $$A \cup B = A \cup \overline {A}B$$
- 概率的证明：
  - $$P(A_1A_2…A_n) = P(A_1)P(A_2|A_1)…P(A_n|A_1A_2…A_{n-1})$$
  - 若 $$P(A|B)=1$$ 则 $$P(A \cup B)=P(A)$$
- 二项分布：
  - 期望：$$E(X) = np$$
  - 方差：$$D(X) = np(1-p)$$
- 分布函数相关：
  - $$F(x) = aF_1(x) - bF_2(x)$$ （新的分布函数由两个已知分布函数线性组合而成）
- 连续随机变量概率密度函数：
  - 总概率为1：$$\int_{-\infty}^{\infty}f(x)dx = 1$$
  - 给定区间概率： $$P(X \le a) = \int_{-\infty}^{a}f(x)dx$$
  - 单点概率为0：$$P(X=a)=0$$
- 相互独立随机变量：
  - 方差：$$D(X+Y)=D(X)+D(Y)$$
  - 期望：$$E(XY)=E(X)E(Y)$$
  - 期望：$$E(X+Y)=E(X)+E(Y)$$
- 指数分布：
  - 期望 E(X) = $$\lambda
$$   , 其中$$\lambda
$$是指数分布参数
  - 方差 $$D(X)=\lambda^2$$
- 联合分布律相关：
  - 求特定事件的概率：例如 $$P\{X+Y < 1\}$$
- 正态分布：
  - $$X \sim N(\mu, \sigma^2)$$
- 相关系数:
  $$\rho(X, Y) = \frac{Cov(X, Y)}{\sqrt{D(X)}\sqrt{D(Y)}}$$ (其中 $$ Cov(X, Y)=E(XY)-E(X)E(Y)$$ )
说明:
- 公式中的符号：
  - $$E(X)$$ 表示随机变量 $$X$$ 的期望值。
  - $$D(X)$$ 表示随机变量 $$X$$ 的方差。
  - $$P(A)$$ 表示事件 $$A$$ 发生的概率。
  - $$F(x)$$表示随机变量的分布函数
  - $$f(x)$$表示随机变量的概率密度函数
  - $$Cov(X, Y)$$表示随机变量X和Y的协方差。
任何错误联系Au1Bhi@163.com
