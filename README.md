# 1Panel升级脚本

## 项目简介

来源：<https://github.com/okxlin/ToolScript/tree/main/1Panel/1panel-upgrade>

本项目包含两个用于升级1Panel面板的脚本：

1. `1panel-upgrade_cn.sh` - 国内版升级脚本
2. `1panel-upgrade_international.sh` - 国际版升级脚本

## 功能说明

### 脚本下载

```bash
# 国内版
cd /opt && wget -N --no-check-certificate https://gh-proxy.com/https://github.com/shellsec/1panel-upgrade/raw/refs/heads/master/1panel-upgrade_cn.sh

# 国际版
cd /opt && wget -N --no-check-certificate https://gh-proxy.com/https://github.com/shellsec/1panel-upgrade/raw/refs/heads/master/1panel-upgrade_international.sh

# 运行国内版
cd /opt && bash 1panel-upgrade_cn.sh
```

### 版本区别

| 特性 | 国内版 | 国际版 |
|------|--------|--------|
| 资源服务器 | `resource.fit2cloud.com` | `resource.1panel.pro` |
| 支持模式 | 稳定版/测试版 | 仅稳定版 |

## 使用说明

1. 确保已安装1Panel面板
2. 使用root或sudo权限运行对应脚本
3. 按照提示完成升级

## 注意事项

1. 请根据您的1Panel版本选择正确的升级脚本
2. 升级前建议备份重要数据
3. 确保服务器能够访问对应的资源服务器
