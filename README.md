<img src="https://avatars.githubusercontent.com/u/53193414?s=200&v=4" alt="logo" width="200" height="200" align="right">

## 特别提示 

- **本人不对任何人因使用本固件所遭受的任何理论或实际的损失承担责任！**
- **本固件禁止用于任何商业用途，请务必严格遵守国家互联网使用相关法律规定！**

## <h1 align="center">云编译：MT路由器</h1>

## 📖 脚本名称包含“237”都是闭源驱动（推荐）

1. 名称包含“237”：闭源驱动（推荐）
- 名称包含“Evn”：使用变量 和 引用 scripts 文件夹
- 名称包含“msd_lite”：编入第三方“msd_lite”
- 名称包含“golang”：升级 golang1.27 版本，才能编译 Passwall 最新版

---

## 📖 Evn脚本说明

2. 云编译Evn脚本说明：
- Evn脚本修改自 WoChen5770 仓库：https://github.com/WoChen5770/openwrt-7dr7299
- Evn脚本跟随 WoChen5770 仓库，拉取第三方 luci-app-daed（二合一插件）来替换“dae、luci-app-dae”和“daed、luci-app-daed”2个插件
- Evn脚本重新拉取第三方来替换 msd_lite插件，若要编译源码自带，请修改“scripts/diy-script.sh”文件，注释掉相关命令
- 在 scripts/Redmi-AX6000 目录包含红米“AX6000-110m大分区”文件和 config 配置文件
- 在根目录升级 golang1.27 版本，必须修改“scripts/diy-6.6.sh”文件
- 在 scripts/diy-script.sh 文件中，可修改路由器默认IP地址
- 在 configs 目录只包含 TP-Link 7DR7299 基础配置文件“config”，可自定义配置文件“CUSTOMIZE.txt”
---

## 📖 红米AX6000-LEDE/110m大分区（开源）

3. 使用脚本“Build_ax6000_LEDE_110m.yml”

   编译适用于hanwckf 大佬的 u-boot/immortalwrt-110m 大分区的固件

---

## 📖 红米AX6000-immortalwrt/110m大分区（开源）

4. 使用脚本“Build_ax6000_immortalwrt_110m.yml”

   编译适用于hanwckf 大佬的 u-boot/immortalwrt-110m 大分区的固件

---


