# Docker Image Downloader

This project automatically downloads and saves the `vllm-ascend` Docker image using GitHub Actions.

## Features

- Automatically pulls the `quay.io/ascend/vllm-ascend:v0.14.0rc1-openeuler` image from `quay.io`.
- Saves the image as a `.tar` archive.
- Uploads the generated tar file as a GitHub Actions Artifact.

## Usage

1. Go to the **Actions** tab in your GitHub repository.
2. Select the **Docker Image Downloader** workflow from the left sidebar.
3. Click the **Run workflow** dropdown and then the **Run workflow** button.
4. Wait for the workflow to complete.
5. Download `vllm-ascend-image` from the **Artifacts** section at the bottom of the workflow run's **Summary** page.

## Image Details

- **Source Image**: `quay.io/ascend/vllm-ascend:v0.14.0rc1-openeuler`
- **Saved Filename**: `vllm-ascend-v0.14.0rc1-openeuler.tar`
- **Artifact Retention**: 1 day
