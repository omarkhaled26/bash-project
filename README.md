cat > README.md << 'EOF'
# 🧩 User and Group Management System

A **Bash-based tool** for managing users and groups on **CentOS Linux**, built with an interactive **Whiptail** interface.  
It provides a simple, menu-driven design that allows administrators to perform essential system management tasks without typing complex commands.

---

## ⚙️ Features
- Add, modify, delete, and list users and groups  
- Enable and disable user accounts  
- Change user passwords  
- View project info via an “About” section  
- Whiptail-based terminal menu with clean navigation  
- Modular design (each function is a standalone script)

---

## 🧰 Tools Used
- **Bash scripting**  
- **Whiptail** (for text-based UI)  
- **Linux system utilities:** `useradd`, `usermod`, `groupadd`, `passwd`, etc.  

---

## 📁 Project Structure
/root/project/
│
├── main.sh           # Main Whiptail menu
├── adduser           # Add new users
├── modifyuser        # Modify existing users (name, UID, group, etc.)
├── deluser           # Delete a user
├── listuser          # List all users
├── addgroup          # Add a group
├── modifygroup       # Modify existing groups
├── delgroup          # Delete a group
├── listgroup         # List all groups
├── disuser           # Disable a user account
├── enuser            # Enable a user account
├── chpasswd          # Change a user’s password
└── about             # Display project information

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/omarkhaled26/bash-project.git
   cd bash-project
