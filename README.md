# TestCVEFixesDatas
Over the past year, we tested the effectiveness of different artificial intelligence models in detecting security vulnerabilities. Table 1 presents the data we collected, while Figure 1 illustrates the performance of various models trained on the dataset from the paper and tested on CVEFixes dataset. Our experiments confirmed that the generalization capability of current AI-based security vulnerability detection still faces significant challenges. The journey toward intelligent security vulnerability detection remains long and arduous!

# The datasets we collected are as follows：

| DataSet          | Vuln   | Non-Vuln | Sum      |
|------------------|--------|----------|----------|
| CrossVul         | 568    | 568      | 1,136    |
| D2A              | 2,795  | 2,444    | 5,239    |
| CVEfixes         | 6,162  | 8,294    | 14,456   |
| Devign           | 12,460 | 14,858   | 27,318   |
| ReVeal           | 2,240  | 20,494   | 22,734   |
| Diversevul       | 18,945 | 311,547  | 330,492  |
| Draper           | 82,411 | 1,191,955| 1,274,366|
| Big-Vul          | 10,900 | 188,636  | 199,536  |
| PrimeVul         | 6,968  | 228,800  | 235,768  |
| SARD             | 6,784  | 24,588   | 31,372   |
| SVulD            | 5,260  | 23,470   | 28,730   |
| VulnPatchPairs   | 11,743 | 11,843   | 23,486   |
| Overall          | 176,692| 2,2040,274| 2,198,756|

# The generalization performance on the CVEfixes dataset is shown in the following figure.
![示例图片](https://github.com/用户名/仓库名/raw/main/example.png)
