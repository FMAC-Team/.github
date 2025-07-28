# FMAC-Team

🔐 **FMAC** (File Monitor and Access Control) is an open-source initiative focused on building a lightweight, extensible, and secure file access control framework for Android and Linux systems. Our goal is to provide kernel-level monitoring, flexible access policies, and a modern user-facing interface.

---

## ✨ Vision

We believe system security should be accessible to everyone. FMAC empowers users to:

- 🔍 Audit critical file access in real time
- 🔒 Enforce fine-grained read/write rules for sensitive paths
- 🧩 Extend behavior using modular hooks
- 📱 Configure rules via a dynamic, Material You–based mobile interface

---

## 🚧 Projects

| Project | Description |
|---------|-------------|
| [`fmanager`](https://github.com/FMAC-Team/fmanager) | Flutter-based frontend with Material 3 design, dynamic theming, and rule editing |
| [`fmac`](https://github.com/FMAC-Team/fmac) | Kernel module for syscall interception and path-based access control |

---

## 🛠 Technologies

- 📱 Flutter 3 (Material You + Android 15 support)
- 🧬 C/C++ Linux kernel module development

---

## 🧪 Getting Started

The project is under active development. To try it out:

- Install [`fmanager`](https://github.com/FMAC-Team/fmanager) on an Android device
- Load the FMAC kernel module manually or via init
- Configure path rules and observe file access events

> Note: Root access and kernel module support are required.

---

