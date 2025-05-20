# GitHub趋势项目追踪与归档工作流

以下是一个精确的步骤描述，用于自动化获取GitHub趋势项目信息、整理并保存相关内容的过程。此工作流可定期执行，追踪GitHub热门项目的变化情况。

## 步骤概述

1. 准备工作目录结构
2. 获取GitHub trending项目信息并格式化保存
3. 创建日期命名的归档目录
4. 生成项目详细介绍文档

## 详细步骤

### 1. 准备工作目录结构

创建或清空必要的工作目录：

```bash
# 创建临时存储目录(.tmp)用于存放项目信息
mkdir -p .tmp

# 创建github目录用于存放归档数据
mkdir -p news/github

# 如需清空现有.tmp目录内容
rm -rf .tmp/*
```

### 2. 获取GitHub trending项目信息

通过网络请求或API获取GitHub trending页面数据，并将其格式化为Markdown表格：

```bash
# 创建trending_projects.md文件，包含以下列：
# - 序号
# - 项目名称
# - 项目地址
# - Star总数
# - 今日新增Star数

cat > .tmp/trending_projects.md << 'EOF'
| 序号 | 项目名称 | 项目地址 | Star数 | 今日新增Star |
|-----|--------|---------|-------|------------|
# 此处填入获取到的项目数据行
# 例如：| 1 | owner/repo | https://github.com/owner/repo | 12,345 | 678 |
EOF
```

实际应用中，可以使用爬虫、GitHub API或专门的工具来自动抓取trending数据。

### 3. 创建日期命名的归档目录

使用当前日期创建标准化的目录名：

```bash
# 获取当前日期并格式化为YYYYMMDD格式
CURRENT_DATE=$(date +%Y%m%d)

# 创建对应的日期目录
mkdir -p news/github/$CURRENT_DATE
```

### 4. 生成项目详细介绍文档

为每个trending项目创建中文简介，并整合到trending.md文件中：

```bash
# 创建trending.md文件头部
cat > news/github/$CURRENT_DATE/trending.md << EOF
# GitHub 热门项目简介 ($(date +%Y年%m月%d日))

以下是GitHub今日热门项目的简要介绍：
EOF

# 针对每个项目，获取详细信息并添加到trending.md
# 这一步可以通过脚本循环读取.tmp/trending_projects.md的内容
# 然后通过API或其他方式获取每个项目的详细信息
# 最后将格式化的内容追加到trending.md

# 对于每个项目，添加如下格式的内容：
# ## 序号. 用户名/仓库名
# 
# **项目地址**：URL
# **Star数**：总数 (今日+增量)
# 
# **简介**：中文项目描述，包含主要功能、用途和特点...
```

## 自动化建议

此工作流可以通过以下方式实现自动化：

1. **Shell脚本**：将上述步骤整合为单个shell脚本
2. **GitHub Actions**：设置定时workflow自动执行
3. **定时任务**：使用crontab设置每日自动执行

## 示例输出说明

执行完成后，将得到以下文件：

1. `.tmp/trending_projects.md`：包含结构化的趋势项目基本信息表格
2. `news/github/YYYYMMDD/trending.md`：包含详细的项目介绍文档

文件示例可参考：
- 趋势项目表格：包含14个热门项目的序号、名称、地址、Star数和今日增量
- 项目介绍文档：对每个项目提供格式一致的标题、链接、星标信息和中文简介

此工作流程可根据需要定期执行，方便跟踪GitHub上流行项目的发展趋势。 