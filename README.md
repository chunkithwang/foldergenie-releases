# FolderGenie Releases

FolderGenie 的更新发布仓库。App 内的 Sparkle 从这里的 `appcast.xml` 检查更新，安装包挂在 Releases 里。

- 正式版：`generate_appcast <目录>`
- 测试版：`generate_appcast --channel beta <目录>`

生成的 appcast 条目由本机钥匙串里的 EdDSA 私钥签名，请勿手动修改签名字段。
