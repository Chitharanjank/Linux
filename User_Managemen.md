# User Management Commands for Beginners

### Show current user
```bash
whoami
```

### Show details of current user
```bash
id
```

### Become root user
```bash
sudo su -
```

### Add a new user with home directory
```bash
sudo useradd -m username
```

### Create home directory automatically 
```bash
sudo mkhomedir_helper username
```

### Set password for a user
```bash
sudo passwd username
```

### Switch to another user (login shell)
```bash
su username
```

### Delete a user
```bash
sudo userdel username
```

### Create a new group
```bash
sudo groupadd groupname
```

### Add user to a group
```bash
sudo usermod -aG groupname username
```

### Delete a user from group
```bash
sudo gpasswd -d username groupname
```

### Delete a group
```bash
sudo groupdel groupname
```

### Change file owner
```bash
sudo chown username file.txt
```

### Change file owner and group
```bash
sudo chown username:groupname file.txt
```

### Lock a user account
```bash
sudo usermod -L username
```

### Unlock a user account
```bash
sudo usermod -U username
```
