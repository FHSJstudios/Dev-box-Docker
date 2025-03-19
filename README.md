## How to Use


### 快速开始,需要执行的命令
```bash
# 全量安装组件（新增）
bash init.sh --all
# 安装oh-my-zsh及其依赖
bash init.zsh-initall.sh
# 安装Dokploy应用
curl -sSL https://dokploy.com/install.sh | sh

### 基础初始化
```bash
# 全量安装组件（新增）
bash init.sh --all
# 或使用短选项
bash init.sh -a

# 仅初始化基础环境
bash init.sh

# 安装Docker（短选项）
bash init.sh -id

# 安装ZSH环境（短选项）
bash init.sh -iz

# 安装Dokploy应用（短选项）
bash init.sh -ik

# 完整安装所有组件（兼容旧版本）
bash init.sh --install-docker --install-zsh --install-dokploy

# 使用混合参数安装
bash init.sh -id -iz -ik