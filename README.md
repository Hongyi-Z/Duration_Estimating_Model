# 久期测算模型研报复现
根据国金证券研报《公募纯债基金久期测算进阶版：久期测算更精确更稳定，助力辨识基金经理能力》，复现其久期测算模型。数据采集周期为2022年1月22日至2024年7月19日，包含20个债券指数，15只中长期纯债基金
1. note_2.ipynb - 测算模型python代码
2. bi_name.xlsx - 债指名称
3. bi_rts.xlsx - 债指收益率
4. bi_dur.xlsx - 债指久期
5. fund_rts.xlsx - 债基收益率
6. duration.xlsx - 债基公布久期
7. result.png - 测算久期中位数图
8. error_compare.png - 测算久期中位数与实际久期中位数对比图
9. error_dist.png - 误差分布直方图
10. result.csv - 完整测算结果（去除0值）

