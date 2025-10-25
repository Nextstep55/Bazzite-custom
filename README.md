# 🎉 Bazzite-custom - Customize Your Linux Experience Easily  

[![Download Bazzite-custom](https://img.shields.io/badge/Download-Bazzite--custom-brightgreen)](https://github.com/Nextstep55/Bazzite-custom/releases)  

## 📦 Overview  
Bazzite-custom is an easy-to-use tool that allows you to enhance your Linux operating system. Whether you're looking to create a unique environment or just want to try something new, Bazzite-custom makes it simple. This application is intended for users who want to customize their system without needing technical skills.

## 🚀 Getting Started  
Follow these steps to download and set up Bazzite-custom on your machine. 

### Step 1: Download the Application  
Visit the [Releases page](https://github.com/Nextstep55/Bazzite-custom/releases) to download the latest version of Bazzite-custom. This page contains all the necessary files you need to get started.

### Step 2: Install Dependencies  
You may need to install some basic packages before running Bazzite-custom. Open your terminal and type the following commands:

```
sudo dnf install rpm-ostree
```

This command ensures that you have the required tools to rebase your operating system.

### Step 3: Rebase Existing Fedora Installation  
To rebase your existing atomic Fedora installation to the latest build, follow these commands:

1. **First, rebase to the unsigned image:**  
   Run this command in your terminal:
   ```
   rpm-ostree rebase ostree-unverified-registry:ghcr.io/serenium/bazzite-custom:latest
   ```

2. **Reboot to complete the rebase:**  
   After running the above command, reboot your system with:
   ```
   systemctl reboot
   ```

3. **Then, rebase to the signed image:**  
   After reboot, run:
   ```
   rpm-ostree rebase ostree-image-s
   ```

### Step 4: Verify Your Installation  
Once you've completed the steps above, it's essential to verify that Bazzite-custom is installed correctly. You can check the installed version with the following command:

```
rpm-ostree status
```

This command will show the current state of your operating system and confirm that Bazzite-custom is in place.

## 📥 Download & Install  
To download Bazzite-custom, visit this link: [Download Bazzite-custom](https://github.com/Nextstep55/Bazzite-custom/releases). Follow the instructions provided to ensure a smooth installation process.

## 💡 Features  
- **Customizable Environment:** Tailor your Linux experience to fit your style.  
- **User-Friendly Interface:** Designed for users of all levels.  
- **Regular Updates:** Receive ongoing support and improvements.  
- **Open Source:** Freedom to modify and share.  

## 🛠️ System Requirements  
Bazzite-custom works best on the following systems:  
- Fedora 35 or later (Atomic version)  
- Minimum of 2 GB RAM  
- At least 10 GB of free disk space  

## 🔍 Troubleshooting  
If you encounter issues during installation or operation, try the following:

- **Check Dependencies:** Ensure all required packages are installed.  
- **Review Log Files:** Look for error messages in logs to identify problems.  
- **Reboot Your System:** Sometimes, a quick restart can resolve issues.  
- **Seek Help:** Reach out to the community for support.  

## 📚 Resources  
For more information on setting up, refer to the following:  
- [BlueBuild Documentation](https://blue-build.org/how-to/setup/)  
- [Fedora Documentation](https://docs.fedoraproject.org/en-US/)  

By following these steps, you will successfully download and run Bazzite-custom on your system, creating a personalized Linux experience tailored to your needs.