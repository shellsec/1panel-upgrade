# 1Panel升级脚本

## 项目简介
来源：https://github.com/okxlin/ToolScript/tree/main/1Panel/1panel-upgrade
本项目包含两个用于升级1Panel面板的脚本：

1. `1panel-upgrade_cn.sh` - 国内版升级脚本
2. `1panel-upgrade_international.sh` - 国际版升级脚本

## 功能说明

方便本地化版升级脚本，支持多种模式(稳定版/测试版)
cd /opt && wget -N --no-check-certificate https://mirror.ghproxy.com/https://github.com/shellsec/1panel-upgrade/raw/refs/heads/master/1panel-upgrade_cn.sh
cd /opt && wget -N --no-check-certificate https://mirror.ghproxy.com/https://github.com/shellsec/1panel-upgrade/raw/refs/heads/master/1panel-upgrade_international.sh
cd /opt && bash 1panel-upgrade_cn.sh

两个脚本的主要功能相同，都用于自动升级1Panel面板到最新版本，主要区别在于：

1. **国内版**：
   - 使用国内资源服务器 `resource.fit2cloud.com`
   - 支持多种模式(稳定版/测试版)

2. **国际版**：
   - 使用国际资源服务器 `resource.1panel.pro`
   - 仅支持稳定版

## 使用说明

1. 确保已安装1Panel面板
2. 使用root或sudo权限运行对应脚本
3. 按照提示完成升级

## 注意事项

1. 请根据您的1Panel版本选择正确的升级脚本
2. 升级前建议备份重要数据
3. 确保服务器能够访问对应的资源服务器# 1panel-upgrade
