# gmca4go
go语言的自签国密数字证书程序

# 用法
## 命令行
Usage:
  gmca [flags]
  gmca [command]

Available Commands:
  completion  Generate the autocompletion script for the specified shell
  exportca    Export ca cert.
  help        Help about any command
  root        Generate root key and cert.
  server      Generate server key and cert.
  version     Print the version number of gmca

Flags:
  -h, --help   help for gmca

Use "gmca [command] --help" for more information about a command.

## gmca root
用于生成根证书

## gmca server test
生成CN为test的服务器证书

## gmca export ca
导入内置的ca证书和密钥

## gmca pfx -p 123 server test
生成CN为test的服务器证书，同时生成pfx文件，pfx文件的密码为123
