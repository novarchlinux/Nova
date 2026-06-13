# 🚀 NovArch Calamares Repository

<p align="center">
  <b>Custom Calamares packages for NovArch Linux</b><br>
  Modern • Lightweight • KDE Integrated
</p>

---

## 📖 About

This repository contains the custom **Calamares Installer** packages used by **NovArch Linux**.

The packages hosted here are used for:

* 💿 Live ISO installation
* 🖥️ Graphical system deployment
* ⚙️ Automated partitioning and setup
* 🎨 KDE Plasma integration
* 🔧 NovArch-specific installer customizations

---

## 📦 Repository Structure

```text
x86_64/
├── novarch-calamares.db.tar.gz
├── novarch-calamares.files.tar.gz
├── calamares-*.pkg.tar.zst
└── calamares-debug-*.pkg.tar.zst
```

---

## 🛠️ Using This Repository

Add the repository to your `/etc/pacman.conf`:

```ini
[novarch-calamares]
Server = https://novarchlinux.github.io/calamares/x86_64
```

Then refresh package databases:

```bash
sudo pacman -Sy
```

---

## 🎯 Project Goals

* ✅ Reliable graphical installation
* ✅ Clean KDE Plasma experience
* ✅ Seamless NovArch deployment
* ✅ Easy maintenance and updates
* ✅ Modern Linux installer workflow

---

## 🌟 Related Projects

### 🌐 NovArch Website

Official website and project information.

### 💿 NovArch Distribution

Source code and build scripts for NovArch Linux.

### 📚 Documentation

Installation guides, configuration references and development notes.

---

## 🤝 Contributing

Contributions, bug reports and suggestions are welcome.

Feel free to open an issue or submit a pull request.

---

## 📜 License

This repository distributes packages built from upstream projects.

Licensing remains subject to the original upstream software licenses.

---

<p align="center">
  Made with ❤️ for NovArch Linux
</p>

