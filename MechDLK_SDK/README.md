# Mech-DLK SDK is OUT now! 🎉
Welcome! Fellow developers! 👋

Our Mech-DLK SDK is at your disposal NOW! Go develop your own programs.
## What's Mech-DLK SDK
Mech-DLK SDK is a secondary development software kit specifically designed to be used with Mech-DLK. Its main purpose is to help you easily do deep learning inference in your software systems. With Mech-DLK SDK, you can rapidly deploy deep learning models and flexibly integrate deep learning functionality into your own applications without reliance on Mech-Vision. Currently, development in C language is supported.

If you have any questions or have anything to share regarding our SDK, feel free to post on [Mech-Mind Online Community](https://community.mech-mind.com/).

## How to install Mech-DLK SDK

1. Create a local project folder on your device, say, “dlk_sdk”.

2. Clone the repository of [Mech-DLK SDK](https://github.com/MechMindRobotics/mechdlk_sdk.git) to the created local project folder.

3. Download the third-party libraries (3rd_dll.zip) and resources (resources.zip) that Mech-DLK SDK relies on from [Downloads](https://downloads.mech-mind.com.cn/?tab=tab-dlk-sdk).

4. Unzip the downloaded packages of third-party libraries and resources and copy and paste the respective folders to the created project folder.

## 👀 Glimpse of inference flow 
<div align="center">
  <img src="resources/inference-flow.png">
</div>

## C samples
The samples provided are in two categories: **Basic** and **Advanced**.

### 📌 Basic
Samples using single models exported from Mech-DLK to do inference of single images, as well as samples used to obtain and visualize results.

- [Classification](https://github.com/MechMindRobotics/mechdlk_sdk/blob/main/samples/c/Basic/Classification.c): an inference sample of the Classification model.

- [DefectSegmentation](https://github.com/MechMindRobotics/mechdlk_sdk/blob/main/samples/c/Basic/DefectSegmentation.c): an inference sample of the Defect Segmentation model.

- [FastPositioning](https://github.com/MechMindRobotics/mechdlk_sdk/blob/main/samples/c/Basic/FastPositioning.c): an inference sample of the Fast Positioning model.

- [InstanceSegmentation](https://github.com/MechMindRobotics/mechdlk_sdk/blob/main/samples/c/Basic/InstanceSegmentation.c): an inference sample of the Instance Segmentation model.

- [ObjectDetection](https://github.com/MechMindRobotics/mechdlk_sdk/blob/main/samples/c/Basic/ObjectDetection.c): an inference sample of the Object Detection model.

### 📌 Advanced
Samples for simultaneous inference of multiple images and inference of cascaded models.

- [CascadeModel](https://github.com/MechMindRobotics/mechdlk_sdk/blob/main/samples/c/Advanced/CascadeModel.c): an inference sample of cascaded models.

- [FolderImagesInfer](https://github.com/MechMindRobotics/mechdlk_sdk/blob/main/samples/c/Advanced/FolderImagesInfer.c): a sample used to show the inference of images in a folder one by one.

- [MultiImageInfer](https://github.com/MechMindRobotics/mechdlk_sdk/blob/main/samples/c/Advanced/MultiImageInfer.c): a sample of simultaneous inference of images.

## [Documentation](https://docs.mech-mind.net/en/dlk-sdk-manual/2.0.0/dlk-sdk.html)
Please refer to the [Getting Started](https://docs.mech-mind.net/en/dlk-sdk-manual/2.0.0/infer-tutorial.html) section for instructions on using Mech-DLK SDK for model inference.

You may also find other contents that can help you get started with Mech-DLK SDK. Check it out NOW!
- Installation
- [System requirements](https://docs.mech-mind.net/en/dlk-sdk-manual/2.0.0/software-installation.html#_system_requirements)
- [How to configure the environment](https://docs.mech-mind.net/en/dlk-sdk-manual/2.0.0/software-installation.html#_configure_environment)
- [How to build and run samples](https://docs.mech-mind.net/en/dlk-sdk-manual/2.0.0/samples/c-windows.html#_build_and_run_samples)
- [Mech-DLK SDK C APIs](https://docs.mech-mind.net/en/dlk-sdk-manual/2.0.0/api-reference/api-reference.html)
- [FAQ](https://docs.mech-mind.net/en/dlk-sdk-manual/2.0.0/faq/faq.html)