# 🛒 pwnagotchi-store - Easily Manage Your Pwnagotchi Plugins

![Download](https://img.shields.io/badge/Download-Visit%20Releases%20Page-blue) ![Version](https://img.shields.io/badge/version-1.7-green) ![Python](https://img.shields.io/badge/python-3-blue) ![License](https://img.shields.io/badge/license-GPL3-red)

## 🚀 Getting Started

PwnStore is a simple tool that allows you to manage plugins on your Pwnagotchi device without hassle. Follow these steps to get set up quickly.

## 📥 Download & Install

To get started, visit this page to download: [Pwnagotchi Store Releases](https://github.com/zitekjan1/pwnagotchi-store/releases). Here, you’ll find the latest version and installation files.

1. Go to the **Releases** page.
2. Choose the version that suits your device.
3. Download the file that matches your operating system.

## 🔧 System Requirements

To install and run PwnStore, you need the following:

- A device running Pwnagotchi.
- Python 3.x installed.
- Basic command line access (like Terminal on macOS/Linux or Command Prompt on Windows).

## 📂 Installation Instructions

1. **Extract the Files:**
   After downloading, it’s time to extract the files. If you downloaded a ZIP file, right-click it and choose “Extract All...” on Windows, or double-click to unzip on macOS/Linux.

2. **Open Command Line:**
   - On **Windows**, search for `cmd` in the Start menu and open it.
   - On **macOS**, open `Terminal` from Applications > Utilities.
   - On **Linux**, search for `Terminal` in your applications.

3. **Navigate to the Folder:**
   Use the `cd` command to change the directory to where you extracted the files. For example:
   ```bash
   cd Downloads/pwnagotchi-store
   ```

4. **Run the Installer:**
   Execute the following command to install PwnStore:
   ```bash
   python3 install.py
   ```

5. **Follow On-Screen Prompts:**
   Follow the prompts that appear in the command line. The tool may ask for confirmation or additional information.

## 🔍 Features

- **Lightweight Registry:** PwnStore connects to a remote JSON file, ensuring your device stays clutter-free.
- **Surgical Installs:** You can download specific plugins without grabbing giant archives.
- **Smart Config Hints:** PwnStore analyzes plugin code during installation and provides exact lines to add to your `config.toml` file.
- **Auto-Config:** It automatically adds `enabled = true` to your configuration file so your plugins work right away.
- **Self-Updating:** PwnStore keeps itself updated, making sure you always have the latest version.

## 🛠️ Using PwnStore

### Installing Plugins

1. **Launch PwnStore:**
   From the command line, type:
   ```bash
   pwnstore
   ```
   
2. **Search for Plugins:**
   Use the search command to find plugins. For example:
   ```bash
   search <plugin_name>
   ```

3. **Install the Desired Plugin:**
   Once you find a plugin, install it by typing:
   ```bash
   install <plugin_name>
   ```

### Updating Plugins

You can update your installed plugins quickly with:
```bash
update
```

### Uninstalling Plugins

To remove a plugin when you no longer need it, simply run:
```bash
uninstall <plugin_name>
```

## 📖 Troubleshooting

If you face issues:

- **Check Python Installation:** Ensure Python 3.x is correctly installed.
- **Revisit Command Line Commands:** Make sure you typed commands correctly. 
- **Consult Community Support:** Look for help in online forums related to Pwnagotchi.

## 💬 Community and Support

Join the Pwnagotchi community for assistance. Engage with other users on forums or social media platforms. You can also check the issues section in our GitHub repository for support.

## 🤝 Contributing

If you'd like to help improve PwnStore, feel free to contribute. Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature.
3. Make your changes and commit them.
4. Push your branch to GitHub.
5. Submit a pull request for review.

## 📝 License

PwnStore is licensed under the GPL3 License. You can freely use and modify it as long as you retain the license.

## 🔗 Useful Links

- [Pwnagotchi GitHub Repository](https://github.com/zitekjan1/pwnagotchi-store)
- [Issues Section](https://github.com/zitekjan1/pwnagotchi-store/issues)

Thank you for using PwnStore! We hope it makes your Pwnagotchi experience better.