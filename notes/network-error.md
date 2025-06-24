## ✅ 1. Document Current Adapter State (Before Boot)

Captured the enabled state of the network adapter in VirtualBox **before booting Ubuntu**.

📷 Screenshot:  
![](../images/NA-enabled.png)

---

## ❌ 2. Disable the Network Adapter

Simulated a network connectivity failure by disabling the adapter via VirtualBox settings.

**Steps:**

1. Shut down the Ubuntu VM.
2. In VirtualBox:
   - Open *Settings* for the VM.
   - Go to the **Network** tab.
   - Uncheck **"Enable Network Adapter"**.
3. Boot the VM again with networking disabled.

📷 Screenshot:  
![](../images/NA-disabled.png)

