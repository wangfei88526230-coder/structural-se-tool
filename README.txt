儿童结构性SE估算工具 v1.1

新增：
- 选择3–12岁年龄
- 自动显示该年龄参考远视储备
- 自动计算“结构性SE − 年龄参考远视储备”

年龄参考远视储备来源：
Wang J, et al. Normative value of hyperopia reserve and myopic shift in Chinese children and adolescents aged 3–16 years.
Br J Ophthalmol. 2024;108(7):1024-1029. doi:10.1136/bjo-2023-323468.
注意：原文Table 3给的是年龄别参考远视储备 mean（均值/标准值），不是中位数。

核心公式：
Kmean = (K1 + K2) / 2
CR(mm) = 337.5 / Kmean(D)
AL/CR = AL × Kmean / 337.5
SEest(D) = 36.463 − 12.278 × AL/CR

用途边界：
- SEest不是散瞳验光结果
- 与年龄参考值的差值不是经过前瞻验证的个体近视风险阈值
- 仅供临床辅助比较
