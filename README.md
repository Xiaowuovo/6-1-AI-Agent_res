# 📦 6-1-AI-Agent 资源仓库

开发环境安装包资源库

---

## 📋 安装包清单

### 1. **Visual Studio 2019 Community**
- 文件: `vs_community__2019.exe`
- 大小: 2.01 MB
- 版本: VS 2019
- 说明: Visual Studio 2019 引导安装程序

### 2. **VS Community 完整版**
- 文件: `vs_community.exe`
- 大小: 4.22 MB
- 版本: VS 2019
- 说明: Visual Studio 2019 完整安装程序

### 3. **Git for Windows**
- 文件: `Git-2.43.0-64-bit.exe`
- 大小: 58.05 MB
- 版本: 2.43.0
- 说明: Git 版本控制系统

### 4. **TortoiseGit**
- 文件: `TortoiseGit-2.15.0.0-64bit.msi`
- 大小: 21.51 MB
- 版本: 2.15.0.0
- 说明: Git 图形化客户端

### 5. **测试文件**
- 文件: `111.exe`
- 大小: 2.01 MB
- 说明: 测试用文件

---

## 🔗 使用方式

### 在代码中引用

```python
# auto_installer.py 中的配置
github_base_url = "https://raw.githubusercontent.com/Xiaowuovo/6-1-AI-Agent_res/main/"

# 下载URL
vs2019_url = github_base_url + "vs_community__2019.exe"
git_url = github_base_url + "Git-2.43.0-64-bit.exe"
tortoisegit_url = github_base_url + "TortoiseGit-2.15.0.0-64bit.msi"
```

### 直接下载

```bash
# VS2019
https://raw.githubusercontent.com/Xiaowuovo/6-1-AI-Agent_res/main/vs_community__2019.exe

# Git
https://raw.githubusercontent.com/Xiaowuovo/6-1-AI-Agent_res/main/Git-2.43.0-64-bit.exe

# TortoiseGit
https://raw.githubusercontent.com/Xiaowuovo/6-1-AI-Agent_res/main/TortoiseGit-2.15.0.0-64bit.msi
```

---

## 📊 统计信息

| 项目 | 数值 |
|------|------|
| 安装包总数 | 5个 |
| 总大小 | ~87 MB |
| 最后更新 | 2025-11-15 |

---

## 🚀 推送历史

### 2025-11-15
- ✅ 添加 Git-2.43.0-64-bit.exe (58.05 MB)
- ✅ 添加 vs_community.exe (4.22 MB)
- ✅ 添加 vs_community__2019.exe (2.01 MB)
- ✅ 添加 TortoiseGit-2.15.0.0-64bit.msi (21.51 MB)

---

## 💡 注意事项

1. **大文件**: 这些是大文件，Git push/pull 需要较长时间
2. **Git LFS**: 如果文件超过100MB，建议使用 Git LFS
3. **网络**: 国内访问 GitHub raw 可能较慢，建议使用代理
4. **更新**: 定期更新到最新版本的安装包

---

## 🔧 维护指南

### 添加新的安装包

```bash
# 1. 复制文件到此目录
cp <installer> C:\Users\Administrator\Desktop\公司事件1\agent比赛\code\6-1-AI-Agent_res

# 2. 添加到 Git
git add <installer>

# 3. 提交
git commit -m "feat: Add <installer_name>"

# 4. 推送
git push
```

### 更新现有安装包

```bash
# 1. 替换文件
cp <new_installer> C:\Users\Administrator\Desktop\公司事件1\agent比赛\code\6-1-AI-Agent_res

# 2. 提交更新
git add <installer>
git commit -m "update: Update <installer_name> to version X.X.X"

# 3. 推送
git push
```

---

## 📝 相关链接

- 主项目仓库: https://github.com/Xiaowuovo/6-1-AI-Agent
- 资源仓库: https://github.com/Xiaowuovo/6-1-AI-Agent_res

---

**最后更新**: 2025-11-15
