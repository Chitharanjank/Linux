# Essential File & Text Commands in Linux

### Copy a file
```bash
cp source.txt destination.txt
```

### Copy a file into a directory
```bash
cp file.txt /path/to/folder/
```

### Copy a directory (recursively)
```bash
cp -r folder1/ folder2/
```

### Move a file
```bash
mv file.txt /path/to/new_location/
```

### Rename a file
```bash
mv oldname.txt newname.txt
```

### Find files by name
```bash
find /path/to/search -name "filename.txt"
```

### Find all `.txt` files in current directory and subdirectories
```bash
find . -type f -name "*.txt"
```

### Change file permissions (e.g., make a script executable)
```bash
chmod 755 script.sh
```

### Make file readable and writable by owner only
```bash
chmod 600 file.txt
```

### Change file ownership
```bash
chown username:groupname file.txt
```

### Display directory structure as a tree
```bash
tree
```

> If not installed, install with:
```bash
sudo apt install tree
```

### Count lines, words, and characters in a file
```bash
wc file.txt
```

### Count only lines
```bash
wc -l file.txt
```

### View first 10 lines of a file
```bash
head file.txt
```

### View first 20 lines
```bash
head -n 20 file.txt
```

### View last 10 lines of a file
```bash
tail file.txt
```

### View last 20 lines
```bash
tail -n 20 file.txt
```

### Follow real-time changes to a file (like logs)
```bash
tail -f logfile.log
```