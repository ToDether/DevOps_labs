
| Команда Linux | Призначення, короткий опис | Приклади використання  |
|-----------|-------------------------|---------------|
| `ls` | Lists the contents of the current directory. | ![1](https://github.com/ToDether/DevOps_labs/assets/127844719/1cd53e69-d6f5-4388-9e18-f55b9ee95750)|
| `ls -R` | Lists all files in the directory and subdirectories recursively. |![2](https://github.com/ToDether/DevOps_labs/assets/127844719/fc929ac1-9315-4d6b-8df3-eeea9c5a5fbe)|
| `ls -a` | Lists all entries including hidden files starting with '.' | ![3](https://github.com/ToDether/DevOps_labs/assets/127844719/4075c2b6-bc25-4478-bb93-e0e67fa2025e)|
| `ls -al` | Lists detailed information about all files, including hidden ones. |![4](https://github.com/ToDether/DevOps_labs/assets/127844719/0a47a51c-e2c7-4ff6-b44d-9f5d746b0135)|
| `cd` or `cd ~` | Changes the current directory to the home directory. |![5](https://github.com/ToDether/DevOps_labs/assets/127844719/7276b445-f674-4178-840d-d067cd06e3d4)|
| `cd ..` | Moves one directory up in the hierarchy. |![6](https://github.com/ToDether/DevOps_labs/assets/127844719/3ae8cb84-ad86-4916-94de-4a858ed634f7)|
| `cd /` | Changes the current directory to the root directory. | ![7](https://github.com/ToDether/DevOps_labs/assets/127844719/e1200fa4-c3e2-4a9a-9363-d6dccecef01e)|
| `cat > filename` | Creates a new file or overwrites an existing file and allows you to enter content. | ![alt text](../image-19.png) |
| `cat filename` | Displays the contents of a file. | ![alt text](../image-20.png) |
| `cat file1 file2 > file3` | Concatenates file1 and file2 and writes the output to file3. | ![alt text](../image-21.png) |
| `mv file "new file path"` | Moves or renames a file to a new location. | ![alt text](../image-22.png) |
| `mv filename new_file_name` | Renames a file. | ![alt text](../image-23.png) |
| `sudo` | Executes a command with superuser (root) privileges. | ![alt text](../image-24.png) |
| `rm filename` | Removes (deletes) a file. | ![alt text](../image-25.png) |
| `man` | Displays the manual page for a command. | ![alt text](../image-26.png) |
| `history` | Displays the command history. | ![alt text](../image-27.png) |
| `clear` | Clears the terminal screen. | ![alt text](../image-28.png) |
| `mkdir directoryname` | Creates a new directory. | ![alt text](../image-29.png) |
| `rmdir` | Removes an empty directory. | ![alt text](../image-30.png) |
| `mv` | Moves or renames files or directories. | Rename file:![alt text](../image-31.png) Move file: ![alt text](../image-32.png) |
| `pr -x` | Formats text files for printing, '-x' sets the number of columns. | ![alt text](../image-33.png) |
| `pr -h` | Adds a header to the file when printing, '-h' specifies the header. | ![alt text](../image-34.png) |
| `pr -n` | Adds line numbers to the file. | ![alt text](../image-35.png) |
| `lp -n c` or `lpr -# c` | Sends a file to the printer, '-n' specifies the number of copies. | `lp -n 2 file.txt` - prints two copies of file.txt |
| `lp -d` or `lpr -P` | Specify the destination | `lp -d printer_name file.txt` or `lp -P printer_name file.txt` |
| `apt-get` | APT package handling utility in Debian and Ubuntu, used for installing, updating, and removing packages. | ![alt text](../image-37.png) |
