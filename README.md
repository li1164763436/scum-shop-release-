# SCUM 商城更新镜像

此仓库是 SCUM 商城客户端更新文件的 GitHub 容灾镜像。

- 主更新源：`https://update.scum0.cn/release-v1/version.json`
- 镜像清单：`https://raw.githubusercontent.com/li1164763436/scum-shop-release-/main/version.json`
- 发布文件采用 SHA256 内容寻址，并由客户端验证签名、文件大小和 SHA256。
- 此仓库不包含签名私钥、客户数据库、运行配置、日志、上传文件或许可证数据。

更新内容由正式发布工具生成，请勿手工修改 `version.json`、`repository/manifests/` 或 `repository/objects/`。
