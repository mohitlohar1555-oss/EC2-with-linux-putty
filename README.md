# 🚀 AWS EC2 Linux Server Connection Using PuTTY

<p align="center">

# ☁️ AWS EC2 + 🐧 Linux + 🔐 SSH + 🖥️ PuTTY

### Securely Connect to an AWS EC2 Linux Server from Windows

</p>

---

## 📌 Project Overview

This project demonstrates how to launch and configure a virtual Linux
server using **Amazon EC2** and securely connect to that server from a
local Windows machine using **PuTTY**.

The complete workflow includes:

1. ☁️ Creating an AWS EC2 instance
2. 🐧 Selecting Ubuntu Linux
3. 🔑 Creating an AWS Key Pair
4. 🔐 Configuring the Security Group
5. 🚪 Allowing SSH traffic through Port 22
6. 📥 Downloading the `.pem` private key
7. 🔄 Converting `.pem` into `.ppk` using PuTTYgen
8. 🖥️ Configuring PuTTY
9. 🌐 Connecting using the EC2 Public IP
10. 🔑 Authenticating using the `.ppk` key
11. 🐧 Accessing the Linux terminal
12. 💻 Executing Linux commands

---

# 🎯 Project Objective

The main objective of this project is to understand how a Linux server
can be provisioned in the AWS Cloud and accessed remotely using SSH.

### The project helps us understand:

- ☁️ AWS EC2
- 🐧 Linux Server
- 🔐 SSH
- 🔑 AWS Key Pair
- 🛡️ Security Group
- 🚪 Port 22
- 🖥️ PuTTY
- 🔄 PuTTYgen
- 🌐 Public IP Address
- 💻 Remote Linux Terminal

---

# ☁️ What is AWS EC2?

**Amazon EC2 (Elastic Compute Cloud)** is an AWS service that allows
users to create and run virtual servers in the cloud.

These virtual servers are called **EC2 Instances**.

With EC2, we can:

- 🖥️ Create virtual machines
- 🐧 Run Linux servers
- 🪟 Run Windows servers
- ⚙️ Install applications
- 🌐 Host websites
- 🔐 Connect remotely
- 📦 Deploy applications
- 🚀 Build cloud infrastructure

---

# 🐧 What is Linux?

Linux is an open-source operating system widely used for:

- ☁️ Cloud servers
- 🚀 DevOps
- 🖥️ Web servers
- 📦 Containers
- 🔧 System administration
- 🌐 Networking
- 🛠️ Server management

In this project, Linux is running inside an AWS EC2 instance.

---

# 🖥️ What is PuTTY?

**PuTTY** is a free SSH client that allows users to connect securely
to remote servers from Windows.

Using PuTTY, we can:

- 🔐 Connect to Linux servers
- 💻 Access remote terminals
- ⚙️ Execute Linux commands
- 📁 Manage files
- 🛠️ Perform server administration

---

# 🔑 What is PuTTYgen?

**PuTTYgen** is a utility included with PuTTY.

It is used to generate and convert SSH keys.

In AWS, the private key is downloaded as:

```text
.pem
