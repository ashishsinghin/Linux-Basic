## **7. Process Management**

### **7.1 Viewing Running Processes**

- Commands:
    - `ps`: View active processes.
    - `top`: Interactive process viewer.
    - `htop`: Enhanced interactive process viewer (install required).
- Examples:
    
    ```
    ps aux
    top
    htop
    ```
    

---

### **7.2 Managing Processes**

- Kill a process:
    
    ```
    kill PID
    ```
    
- Kill all processes by name:
    
    ```
    killall process_name
    ```
    
- Stop, resume, and prioritize processes:
    
    ```
    fg
    bg
    nice -n priority command
    renice priority PID
    ```
    

---

## **8. Disk Management**

### **8.1 Disk Partitioning**

- View partitions:
    
    ```
    sudo fdisk -l
    ```
    
- Partition a disk:
    
    ```
    sudo fdisk /dev/sdX
    ```
    

---

### **8.2 Mounting and Unmounting Drives**

- Mount a drive:
    
    ```
    sudo mount /dev/sdX1 /mnt
    ```
    
- Unmount a drive:
    
    ```
    sudo umount /mnt
    ```
    

---

### **8.3 Disk Usage Analysis**

- Check disk usage:
    
    ```
    df -h
    ```
    
- Analyze directory size:
    
    ```
    du -sh directory_name
    ```
    

---

## **9. Package Management**

### **9.1 Working with Package Managers**

- **APT** (Debian/Ubuntu):
    
    ```
    sudo apt update
    sudo apt install package_name
    sudo apt remove package_name
    ```
    
- **YUM/DNF** (CentOS/Fedora):
    
    ```
    sudo yum install package_name
    sudo yum remove package_name
    ```
    

---

### **9.2 Updating the System**

- Update all packages:
    
    ```
    sudo apt upgrade
    sudo yum update
    ```
    

---

## **10. Shell Scripting Basics**

### **10.1 Writing Your First Shell Script**

- Create a script file:
    
    ```
    nano script.sh
    ```
    
- Add the following content:
    
    ```
    #!/bin/bash
    echo "Hello, World!"
    ```
    
- Make it executable:
    
    ```
    chmod +x script.sh
    ```
    
- Run the script:
    
    ```
    ./script.sh
    ```
    

---

### **10.2 Variables and Loops**

- Define a variable:
    
    ```
    NAME="Linux"
    echo "Welcome to $NAME"
    ```
    
- Create a loop:
    
    ```
    for i in {1..5}
    do
      echo "Iteration $i"
    done
    ```
    

---

### **10.3 Conditional Statements**

- Use `if` statements:
    
    ```
    if [ condition ]
    then
      echo "Condition met"
    else
      echo "Condition not met"
    fi
    ```
