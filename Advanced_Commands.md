# Advanced Linux Commands 

### Search for a pattern in a file (case-sensitive)
```bash
grep "pattern" filename.txt
```

### Search for a pattern (case-insensitive)
```bash
grep -i "pattern" filename.txt
```

### Recursively search for a string in all files in a directory
```bash
grep -r "pattern" /path/to/directory
```

### Show line numbers with matched text
```bash
grep -n "pattern" filename.txt
```


### Replace text in a file (does not modify original file)
```bash
sed 's/old/new/' filename.txt
```

### Replace all occurrences in a file
```bash
sed 's/old/new/g' filename.txt
```

### Replace and save changes to the same file (in-place)
```bash
sed -i 's/old/new/g' filename.txt
```

### Print specific fields from a file or command output
```bash
awk '{print $1}' filename.txt
```

### Print lines that match a pattern
```bash
awk '/pattern/ {print}' filename.txt
```

### Securely copy a file to a remote server
```bash
scp file.txt user@remote:/path/to/destination/
```

### Copy a directory to a remote server (with -r flag)
```bash
scp -r folder/ user@remote:/path/
```

### Create a hard link to a file
```bash
ln original.txt hardlink.txt
```

### Create a symbolic (soft) link
```bash
ln -s original.txt symlink.txt
```