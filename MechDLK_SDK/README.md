# Mech-DLK SDK is OUT now! 🎉
Welcome! Fellow developers! 👋

Our Mech-DLK SDK is at your disposal NOW! Go develop your own programs.
## What's Mech-DLK SDK
Mech-DLK SDK is a secondary development software kit specifically designed to be used with Mech-DLK. Its main purpose is to help you easily do deep learning inference in your software systems. With Mech-DLK SDK, you can rapidly deploy deep learning models and flexibly integrate deep learning functionality into your own applications without reliance on Mech-Vision. Currently, development in C language is supported.

If you have any questions or have anything to share regarding our SDK, feel free to post on [Mech-Mind Online Community](https://community.mech-mind.com/).

## ✅ How to install Mech-DLK SDK

1. Create a local project folder on your device, say, “dlk_sdk”.

2. Clone the repository of Mech-DLK SDK to the created local project folder.

3. Download the third-party libraries (3rd_dll.zip) and resources (resources.zip) that Mech-DLK SDK relies on from [Downloads](https://downloads.mech-mind.com.cn/?tab=tab-dlk-sdk).

4. Unzip the downloaded packages of third-party libraries and resources and copy and paste the respective folders to the created project folder.

## 👀 Glimpse of inference flow 

Here is the inference flow. (image)

## C samples
The samples provided are in two categories: **Basic** and **Advanced**.

### 📌 Basic
Samples using single models exported from Mech-DLK to do inference of single images, as well as samples used to obtain and visualize results.

- [Classification](): an inference sample of the Classification model.

- [DefectSegmentation](): an inference sample of the Defect Segmentation model.

- [FastPositioning](): an inference sample of the Fast Positioning model.

- [InstanceSegmentation](): an inference sample of the Instance Segmentation model.

- [ObjectDetection](): an inference sample of the Object Detection model.

### 📌 Advanced
Samples for simultaneous inference of multiple images and inference of cascaded models.

- [CascadeModel](): an inference sample of cascaded models.

- [FolderImagesInfer](): a sample used to show the inference of images in a folder one by one.

- [MultiImageInfer](): a sample of simultaneous inference of images.

## [Documentation]()
Please refer to the [Getting Started]() section for instructions on using Mech-DLK SDK for model inference.

You may also find other contents that can help you get started with Mech-DLK SDK. Check it out NOW!
- Installation
- [System requirements]()
- [How to configure the environment]()
- [How to build and run samples]()
- [Mech-DLK SDK C APIs]()
- [FAQ]()