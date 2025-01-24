## Scripts Overview
### 1 Backup Script
 - Purpose: Creates a backup of specified files or directories by copying them to a designated backup folder.

#### Features
 - Automatically creates a timestamped folder for each backup.
 - Supports multiple files and directories.
 - Ensures existing backups remain intact.

#### Usage
```bash
./backup.sh [source_path] [backup_destination]
```
### 2 Compress Script
 - Purpose: Compresses files or directories into a .tar.gz archive.

#### Features
 - Supports multiple files and directories for compression.
 - Creates compressed archives with customizable names.

#### Usage
```bash
./compress.sh [output_archive_name] [file1] [file2] ... [fileN]
```

### 3 Compact or Descompact Script
 - Purpose: The user will be able to interact and make the choice to zip or unzip, 
   in addtion to being able to choose where they want the file to be saved.

#### Features
 - Create compressed or descompress multiple files.
 - The user can choose where they want the file to be saved.

#### Usage
```bash
./compedescomp.sh
	compactar
		./home/your-local-destiny
			./file-to-compress(1) ./file-to-compress(2) ./file-to-compress(n)
```
#### Or
```bash
./compedescomp.sh
	descompactar
		./home/your-file-for-descompat
			./local-to-destiny
```


### Prerequisites
 - Ensure you have the following installed on your system:
 - Bash (for running the shell scripts).
 - tar (for compression operations).
