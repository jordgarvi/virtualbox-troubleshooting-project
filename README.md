# VirtualBox Troubleshooting & Documentation Project

## 🛠️ Project Goal
To demonstrate the setup, configuration, and troubleshooting of VirtualBox for virtual machine deployment and IT support scenarios. This showcases my ability to work with hypervisors and solve real world technical issues, key skills for IT support and cloud related roles.

---

## 📥 Step 1: Download and Install VirtualBox

- Visited [virtualbox.org](https://www.virtualbox.org)
- Downloaded the Windows installer (version 7.1.6)
- Started the installation with default settings

![Screenshot of VirtualBox Download](images/download.png)

---

## ⚙️ Step 2: Create Virtual Machine

- 🖥️ [Step 2: Create Virtual Machine](notes/vm-setup.md)

---

## 💿 Step 3: Attach Ubuntu ISO

- Opened VirtualBox VM settings → Storage
- Attached `ubuntu-22.04.iso` to the virtual optical drive on SATA Port 1
- Ensured ISO is correctly selected to boot from during VM startup

![Ubuntu ISO Attached to Optical Drive](images/step-3-storage-settings.png)

---

## 🧪 Step 4: Ubuntu Installation & Troubleshooting

- 🧪 [Step 4: Ubuntu Installation & Troubleshooting](notes/ubuntu-setup.md)

---

## Step 5: Create Snapshot

### 🎯 Goal
To save the current clean state of the system, enabling a safe rollback if issues arise during later installations or testing.

### 🖼️ Screenshots
| Before Snapshot | Snapshot Dialog | Snapshot Created |
|------------------|------------------|------------------|
| ![](images-step-05-before-snapshot.png) | ![](images-step-05-snapshot-dialog.png) | ![](images-step-05-snapshot-created.png) |

### 🗒️ Notes
- Snapshot Name: `Ubuntu Clean Install`
- Description: Snapshot of freshly installed Ubuntu with all initial config complete.
- Why: Acts as a safety net before networking and testing.


