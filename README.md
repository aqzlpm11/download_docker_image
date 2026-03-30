# Docker Image Downloader

这个项目通过 GitHub Actions 自动下载并保存 `vllm-ascend` Docker 镜像。

## 功能

- 自动从 `quay.io` 拉取 `quay.io/ascend/vllm-ascend:v0.14.0rc1-openeuler` 镜像。
- 将镜像保存为 `.tar` 归档文件。
- 将生成的 tar 文件上传为 GitHub Actions 构件（Artifact）。

## 使用方法

1. 在 GitHub 仓库页面点击 **Actions** 选项卡。
2. 在左侧边栏中选择 **Docker Image Downloader** 工作流。
3. 点击 **Run workflow** 下拉菜单，然后点击 **Run workflow** 按钮。
4. 等待工作流执行完毕。
5. 在执行记录的 **Summary** 页面底部的 **Artifacts** 区域下载 `vllm-ascend-image`。

## 镜像详情

- **原始镜像**: `quay.io/ascend/vllm-ascend:v0.14.0rc1-openeuler`
- **保存后的文件名**: `vllm-ascend-v0.14.0rc1-openeuler.tar`
- **Artifact 保留时长**: 1 天
