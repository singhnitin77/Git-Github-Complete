# Command Line Tool

## PWD
### Print Working Directory i.e Directory in which terminal is opened or to check in which folder you are.

```bash
  pwd
```
---
## CD

### Using cd we can travel in between the folders.

```bash
  cd
```

### This will take directly to home directory.

```bash
  cd ~
```

### This will take directly to the root.

```bash
  cd /
```
---
## LS
### To see content of a folder.

```bash
  ls
```

### To see content of a folder in a list format.

```bash
  ls -l
```
```bash
  ls -a
```
Also
```bash
  ls -al
```
---

## MKDIR
### To make a folder.

```bash
  mkdir
```

### This will make a folder with name CLI.
```bash
  mkdir CLI
```

### This will make 3 different folders with name as f1, f2, f3.
```bash
  mkdir f1 f2 f3
```
### If we want f4 folder & inside it another folder named as f5 at the same time.
```bash
  mkdir -p f4/f5
```
---
## TOUCH
### To make a new file.

```bash
  touch
```

### This will make a index.txt file.
```bash
touch index.txt
```
---
## RM
### To delete files.
**We can only remove files using rm command not directory**

```bash
  rm
```

### To delete a file named as file.txt which is inside f2 directory.
```bash
rm f2/file.txt
```
---
## RMDIR
### To delete a directory.

```bash
  rmdir
```

### To delete a directory named as f2 which is having content inside it.
```bash
rm -R f2
```
---
## CP
### To copy.

```bash
  cp
```
---
## MV
### To move.

```bash
  mv
```
---