儿童结构性SE估算 - 程序版本 3.0 / 算法冻结版 v1.0

核心逻辑：
1. 年龄+性别查标准 AL_ref、K_ref、SE_ref。
2. Kmean=(K1+K2)/2。
3. ΔAL = AL_child - AL_ref。
4. ΔSE_AL = -2.5 × ΔAL。
5. ΔK = Kmean_child - K_ref。
6. ΔSE_K = -ΔK。
7. SE_structural = SE_ref + ΔSE_AL + ΔSE_K。

本版本不使用 AL/CR、不使用回归斜率 β。
