# 1. Lab Environment Setup Guide
This comprehensive guide is crafted for the AI Training Course, targeting individuals eager to master the fundamentals of artificial intelligence and TensorFlow programming. It provides a clear, step-by-step approach to understanding core AI concepts and practical implementation using TensorFlow, a leading open-source framework for machine learning. The document includes detailed instructions for setting up the development environment, allowing you to configure the language and tools based on your specific system requirements, whether you're using Windows, macOS, or Linux. Additionally, it covers prerequisites such as installing Python, TensorFlow libraries, and other essential dependencies, ensuring a smooth setup process tailored to your local environment. This resource is ideal for beginners and intermediate learners aiming to build a strong foundation in AI development.

## Description

This document covers the following parts:
- Windows Lab Environment Setup
- Huawei Cloud User Guide

## Background Knowledge Required
This course is a bsic course for  Huawei certification. To better understand this course, familiarize yourself with the following requirements:
- Python Fundamentals for AI
- Basic Concepts of TensorFlow

## Step-by-Step Guide to Downloading and Installing Anaconda on Windows
Anaconda is a powerful Python distribution that includes essential tools for data science, machine learning, and scientific computing. Follow these steps to install Anaconda on your Windows PC.

### Step 1: Download Anaconda
- Go to the Anaconda Website:
- Open your browser and visit: https://www.anaconda.com/download
- Choose the Windows Installer:
- Under "Windows," click the 64-Bit Graphical Installer (recommended for most users).
- If your PC is 32-bit (uncommon), choose the 32-bit version.
- Start the Download:
- Click Download and wait for the .exe file (e.g., Anaconda3-2024.02-Windows-x86_64.exe) to finish downloading.

### Step 2: Install Anaconda
Run the Installer:
- Locate the downloaded .exe file (usually in Downloads) and double-click it.
- Follow the Setup Wizard:
- Click Next on the welcome screen.
- Read and accept the License Agreement (click I Agree).
- Choose Just Me (recommended) unless you need it for all users.
- Select Installation Location:
- The default folder (C:\Users\<YourUsername>\Anaconda3) is fine. Click Next.
- Advanced Options (Important!) ✅:
- ✅ Check "Add Anaconda3 to my PATH environment variable" (helps run Anaconda from Command Prompt).
- ✅ Check "Register Anaconda3 as my default Python" (recommended).
- Click Install and wait for the installation to complete (may take a few minutes).
- Finish Installation:
- Once done, click Next → Finish.

## Step 3: Verify Installation
**Method 1**: Using Anaconda Navigator (GUI)
Press Windows Key and search for Anaconda Navigator, then open it.
If it launches, Anaconda is installed correctly.

**Method 2**: Using Command Prompt (Recommended)
Open Command Prompt (Press Win + R, type cmd, and hit Enter).
Run ( ``bash```) : ``` conda --version ```
If it shows a version (e.g., conda 24.x.x), it’s working.
Check Python: python --version
