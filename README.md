# DiskTool

DiskTool Windows 二进制发行包。

下载 [disktool.exe](./disktool.exe)。本版新增 `hash-file <文件路径>`，可计算镜像或备份文件的 SHA-256，用于完整性校验。

示例：

```powershell
.\disktool.exe hash-file D:\backup\disk.img
```

`SHA256SUMS` 保存当前发行文件的 SHA-256 校验值。镜像文件系统恢复功能需要单独配置 Sleuth Kit。
