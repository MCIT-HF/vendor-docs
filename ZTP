# Zero Touch Activation: Firmware Upgrade Instructions
**For Cisco Room Kit Pro, Room Bar, Room Bar Pro, Room Kit EQ, and Cisco Codec Pro**

---

## Overview
Before a Cisco codec can complete Zero Touch Activation through the navigator, it must be running **RoomOS 26.5.0 or higher**. These instructions walk you through upgrading older devices or factory-fresh units to the required firmware version.

**Time required:** ~5–10 minutes (including device restart)

---

## Before You Start

✓ Codec is connected to the network (wired Ethernet)  
✓ All peripherals are physically connected and powered on  
✓ You can access the codec from the in-room computer via web browser  

---

## Step 1: Access the Developer API

1. Open a web browser on the in-room computer.
2. Navigate to the codec's IP address (e.g., `http://10.0.1.56`)
3. Sign in with:
   - **Username:** `admin`
   - **Password:** (leave blank)

4. In the left menu, select **Developer API** (under **SYSTEM MAINTENANCE** section).

---

## Step 2: Find the Upgrade Command

Below is the command you'll need based on your codec model:

### **Room Bar, Room Bar Pro, Room Kit EQ, Codec Pro**
Copy this command:
```
xCommand SystemUnit SoftwareUpgrade URL: "https://binaries.webex.com/collaboration-endpoint-ce-production-beta/20260309114216/zenith.pkg" Forced: True
```

### **Codec Pro G2** *(coming soon — keep these instructions for future installations)*
When you install Codec Pro G2 models, use this command instead:
```
xCommand SystemUnit SoftwareUpgrade URL: "https://binaries.webex.com/collaboration-endpoint-ce-production-beta/20260309114216/luna.pkg" Forced: True
```

---

## Step 3: Execute the Upgrade

1. On the **Developer API** page, paste your command into the **Execute Commands and Configurations** text field.

2. Click the **Execute** button.

3. You'll see a confirmation message appear — this means the upgrade has started.

---

## Step 4: Wait for Device Restart

1. **Sign out of the web page** (you can close the browser window).

2. Watch the codec display — you'll see it power down and restart automatically.

3. This process takes **2–3 minutes**. Do not interrupt power.

4. Once the device restarts and comes back online, the Cisco navigator will appear on the display.

---

## Step 5: Proceed with Onboarding

Once the device has restarted and the navigator screen appears, select **Automatic Onboarding** to continue with Zero Touch Activation. The device is now ready to complete the rest of the setup process.

---

## If Something Goes Wrong

If the device does not restart, or if you see an error message during the upgrade:

1. **Do not retry the command.**
2. Contact your Collab Analyst with:
   - Codec model
   - IP address
   - Error message (if any)
   - Timestamp of when the upgrade was attempted

We'll troubleshoot from there.

---

## Questions?

Reach out to the Collab Analyst before proceeding if you have any questions about this process.
