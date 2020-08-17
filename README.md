# ipconfig-flushdns

Windows环境下刷新dns缓存

新建文件，拷贝以下代码并保存为`.bat`

```bash
echo off
cls
ipconfig /release
ipconfig /flushdns
ipconfig /renew
exit

```

