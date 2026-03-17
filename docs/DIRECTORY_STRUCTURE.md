# 目录结构说明

## 完整目录树

marketing_ab_testing/
├── README.md                          # 项目主文档
├── CHANGELOG.md                       # 版本更新日志
├── requirements.txt                   # Python 依赖包列表
├── .gitignore                         # Git 忽略文件配置
│
├── data/                              # 数据目录
│   ├── raw/                          # 原始数据（不提交到 Git）
│   │   └── .gitkeep                  # 占位文件 + 数据下载说明
│   └── processed/                    # 处理后的数据
│       └── .gitkeep                  # 占位文件
│
├── notebooks/                         # Jupyter Notebooks
│   └── 01_marketing_ab_test.ipynb   # 完整分析流程
│
├── src/                              # 源代码
│   └── ab_utils.py                  # A/B 测试工具函数库
│
├── docs/                             # 文档目录
│   ├── data_dictionary.md           # 数据字典
│   ├── experiment_summary.md        # 实验结论卡
│   ├── PROJECT_ROADMAP.md           # 项目路线图
│   ├── RESUME_TEMPLATE.md           # 简历写法参考
│   ├── DIRECTORY_STRUCTURE.md       # 本文件
│   ├── figures/                     # 图表输出
│   │   └── .gitkeep
│   └── screenshots/                 # 截图（可选）
│
├── scripts/                          # 脚本目录
│   └── quick_start.sh               # 快速启动脚本
│
└── results/                          # 分析结果
    └── .gitkeep                      # 占位文件
