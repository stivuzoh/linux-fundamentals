# linux-fundamentals
This a repo to show  linux fundamentals 
# 🚀 Linux Server Management Tutorial on AWS EC2

This tutorial will guide you through the essential Steps for launching, connecting, updating, and managing a Linux server on AWS EC2.  
Each step is illustrated with screenshots 📸 for better understanding.

---

## Step 1️⃣ – Launch an EC2 Instance
![Step 1](Step1%20AMI%20chosen%20and%20instance%20ready%20to%20launch.png)  
➡️ Navigate to AWS EC2 dashboard and click **Launch Instances**.

---

## Step 2️⃣ – Pem key created
![Step 2](Step2%20Pem%20key%20created%20and%20instanced%20launched.png)  
➡️ create a .pem key to log in🐧.

---

## Step 3️⃣ – Instance running
![Step 3](Step3%20instance%20running.png)  
➡️  free-tier eligible instance, such as **t2.micro** chosen.

---

## Step 4️⃣ – Configure Security Group
![Step 4](Step4%20copy%20SSH%20client%20key.png)  
➡️ Allow **SSH (port 22)** so you can connect via terminal 🔑.

---

## Step 5️⃣ – Mobaxterm installed and ready 
![Step 5](step5mobaxterm.png)  
➡️ Review configuration, then click **Launch** 🚀.

---

## Step 6️⃣ – Connect to Instance
![Step 6](Step6%20Connecting%20linux%20server%20%20through%20SSH%20key.png)  
➡️ Use the provided SSH command to connect from your terminal 💻.

---

## Step 7️⃣ – Update Package Lists
![Step 7](Step7%20Updating%20Packages.png)  
➡️ Run:  
```bash
sudo apt update
```  
🔄 This refreshes available package information.

---

## Step 8️⃣ – Install a Package (tree)
![Step 8](Step8%20tree%20package%20installed.png)  
➡️ Run:  
```bash
sudo apt install tree
```  
🌳 This installs the **tree** command to view directory structures.

---

## Step 9️⃣ – Upgrade Installed Packages
![Step 9](Step9%20Updating%20installed%20packages.png)  
➡️ Run:  
```bash
sudo apt upgrade
```  
⬆️ This upgrades all installed packages to latest versions.

---

## Step 🔟 – Remove a Package
![Step 10](Step10%20removing%20packages.png)  
➡️ Run:  
```bash
sudo apt remove tree
```  
❌ This removes the installed **tree** package.

---

## Step 1️⃣1️⃣ – Terminate the Instance
![Step 11](Step11%20To%20stop%20or%20terminate%20an%20instance.png)  
➡️ From the EC2 dashboard, **terminate** the instance when you’re done 🛑.

---

# 🎉 Congratulations!
1 have successfully learned how to:  
✅ Launch an EC2 instance  
✅ Connect via SSH  
✅ Manage packages (install, update, remove)  
✅ Terminate the instance safely  

🚀 Now I am ready to manage Linux servers on AWS 
