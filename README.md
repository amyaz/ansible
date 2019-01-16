# 如何使用 Ansible 管理你的工作站配置

------

#### 简介

使用 Ansible 自动化工作站配置，使新安装的机器快速搭建好工作环境。

#### 使用

安装 Ansible ：
```
sudo apt update
sudo apt install git ansible
```

应用 playbook ：
```
sudo ansible-pull -U https://gitee.com/amyaz/ansible.git
```