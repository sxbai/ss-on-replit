# ss-on-replit  

## 使用说明
- replit环境选择`Blank Repl` 或 `Bash`
- 核心文件 `replit.nix` 和 `.replit`  
执行`run.sh`脚本之前先替换`replit.nix` 和 `.replit` (建议手动上传替换)
## 脚本来源
- [ ] 修改自Github开源项目 [https://github.com/Snawoot/ss-replit](https://github.com/Snawoot/ss-replit)
- [x] 修改原脚本`make_url.sh`部分参数(生成ss://链接部分,原脚本生成链接导入shadowsocks win端提示错误)
- [x] 适配shadowsocks win客户端(将v2ray-plugin.exe放在shadowsocks-win同文件夹下)直接选择`二维码导入`或`URL导入`
## 附件下载
| 软件名      | 下载地址     |
| :---        | :---        |
| shadowsocks-Windows | https://github.com/shadowsocks/shadowsocks-windows/releases |
| shadowsocks-MacOS | https://github.com/shadowsocks/ShadowsocksX-NG/releases |
| shadowsocks-Android | https://github.com/shadowsocks/shadowsocks-android/releases |
| v2ray-plugin-Win/Mac/Linux | https://github.com/shadowsocks/v2ray-plugin/releases |
| v2ray-plugin-Android | https://github.com/shadowsocks/v2ray-plugin-android/releases |

### v2ray-plugin补充
- v2ray-plugin-Windows **32位系统**选`v2ray-plugin-windows-386` **64位系统**选`v2ray-plugin-windows-amd64`
- v2ray-plugin-MacOS **Intel芯片**选`v2ray-plugin-darwin-amd64` **M系列芯片**选`v2ray-plugin-darwin-arm64`
- v2ray-plugin-Android **通用**选`v2ray--universal` **arm64**选`v2ray-arm64-v8a` **arm32**选`v2ray-armeabi-v7a` **X86**选`v2ray-x86` **X86_64位**选`v2ray-x86_64`
