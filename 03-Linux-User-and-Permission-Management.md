## **5. User and Permission Management**

### **5.1 Managing Users**

- Add a new user:
    
    ```bash
    sudo adduser username
    ```
    
- Delete a user:
    
    ```bash
    sudo deluser username
    ```
    
- List all users:
    
    ```bash
    cat /etc/passwd
    ```
    

---

### **5.2 Managing Groups**

- Add a new group:
    
    ```bash
    sudo groupadd groupname
    ```
    
- Add a user to a group:
    
    ```bash
    sudo usermod -aG groupname username
    ```
    
- List groups:
    
    ```bash
    cat /etc/group
    ```
    

---

### **5.3 File and Directory Permissions**

- View file permissions:
    
    ```bash
    ls -l
    ```
    
- Change file permissions:
    
    ```bash
    chmod 755 filename
    ```
    
- Change file ownership:
    
    ```bash
    sudo chown user:group filename
    ```
    

---

### **5.4 Special Permissions**

- Setuid, Setgid, Sticky Bit.
- Example of sticky bit:
    
    ```bash
    chmod +t directoryname
    ```
    

---

## **6. Basic Networking**

### **6.1 Understanding IP Addresses**

- Types of IP addresses: Public, Private, Loopback (`127.0.0.1`).
- View current IP address:
    
    ```bash
    ip a
    ```
    

---

### **6.2 Network Configuration**

- Check active network connections:
    
    ```bash
    netstat -tuln
    ```
    
- Configure network interfaces:
    
    ```bash
    sudo nano /etc/network/interfaces
    ```
    

---

### **6.3 Ping and Traceroute**

- Test network connectivity with `ping`:
    
    ```bash
    ping google.com
    ```
    
- Trace route of a packet:
    
    ```bash
    traceroute google.com
    ```
    

---

### **6.4 Downloading Files**

- Using `wget` to download files:
    
    ```bash
    wget <http://example.com/file>
    ```
    
- Using `curl` for downloading and testing URLs:
    
    ```bash
    curl -O <http://example.com/file>
    ```
