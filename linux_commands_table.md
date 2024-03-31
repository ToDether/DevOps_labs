
| Команда Linux | Призначення, короткий опис | Приклади використання  |
|-----------|-------------------------|---------------|
| `ls` | Lists the contents of the current directory. | ![1](https://github.com/ToDether/DevOps_labs/assets/127844719/1cd53e69-d6f5-4388-9e18-f55b9ee95750)|
| `ls -R` | Lists all files in the directory and subdirectories recursively. |![2](https://github.com/ToDether/DevOps_labs/assets/127844719/fc929ac1-9315-4d6b-8df3-eeea9c5a5fbe)|
| `ls -a` | Lists all entries including hidden files starting with '.' | ![3](https://github.com/ToDether/DevOps_labs/assets/127844719/4075c2b6-bc25-4478-bb93-e0e67fa2025e)|
| `ls -al` | Lists detailed information about all files, including hidden ones. |![4](https://github.com/ToDether/DevOps_labs/assets/127844719/0a47a51c-e2c7-4ff6-b44d-9f5d746b0135)|
| `cd` or `cd ~` | Changes the current directory to the home directory. |![5](https://github.com/ToDether/DevOps_labs/assets/127844719/7276b445-f674-4178-840d-d067cd06e3d4)|
| `cd ..` | Moves one directory up in the hierarchy. |![6](https://github.com/ToDether/DevOps_labs/assets/127844719/3ae8cb84-ad86-4916-94de-4a858ed634f7)|
| `cd /` | Changes the current directory to the root directory. | ![7](https://github.com/ToDether/DevOps_labs/assets/127844719/e1200fa4-c3e2-4a9a-9363-d6dccecef01e)|
| `cat > filename` | Creates a new file or overwrites an existing file and allows you to enter content. | ![cat  filename](https://github.com/ToDether/DevOps_labs/assets/127844719/5d884065-88e0-4276-a4c8-affb2cfc4221)|
| `cat filename` | Displays the contents of a file. | ![9](https://github.com/ToDether/DevOps_labs/assets/127844719/0844b36c-9a44-4ea6-80ce-b893a42eb263)|
| `cat file1 file2 > file3` | Concatenates file1 and file2 and writes the output to file3. | ![10](https://github.com/ToDether/DevOps_labs/assets/127844719/813c5246-2ab1-4dc7-a508-60397231de45)|
| `mv file "new file path"` | Moves or renames a file to a new location. | ![11](https://github.com/ToDether/DevOps_labs/assets/127844719/0ad70871-aa25-4167-a0d6-88f1fb9dd70e)|
| `mv filename new_file_name` | Renames a file. | ![12](https://github.com/ToDether/DevOps_labs/assets/127844719/cc4295e2-b0bb-4364-b2a5-8cf208dc2cea)|
| `sudo` | Executes a command with superuser (root) privileges. | ![13](https://github.com/ToDether/DevOps_labs/assets/127844719/a5089ade-69ee-4ded-8961-dda5fbdabea9)|
| `rm filename` | Removes (deletes) a file. | ![14](https://github.com/ToDether/DevOps_labs/assets/127844719/448df5de-262e-4a29-91c8-a93d1f3dc32f)|
| `man` | Displays the manual page for a command. |  |
| `history` | Displays the command history. | ![15_history](https://github.com/ToDether/DevOps_labs/assets/127844719/3b6b0f0d-10dc-40c5-bf22-3780de262096)|
| `clear` | Clears the terminal screen. | ![16](https://github.com/ToDether/DevOps_labs/assets/127844719/d991bf6e-a2e1-4909-b7a2-ef38c64eca3b)|
| `mkdir directoryname` | Creates a new directory. | ![alt text](../image-29.png) |
| `rmdir` | Removes an empty directory. | ![17 rmdir](https://github.com/ToDether/DevOps_labs/assets/127844719/bf45fa5e-244e-4622-a118-282b8a3e3de5)|
| `mv` | Moves or renames files or directories. | Rename file: ![18](https://github.com/ToDether/DevOps_labs/assets/127844719/397600a1-d432-4743-be43-e07fad0f3abf) Move file: ![18_2](https://github.com/ToDether/DevOps_labs/assets/127844719/e95d7a1b-7fd1-4667-85c7-2c529df92348)|
| `pr -x` | Formats text files for printing, '-x' sets the number of columns. | ![19](https://github.com/ToDether/DevOps_labs/assets/127844719/ba9115f7-6de8-44fd-93ad-8e247c7e7b3c)|
| `pr -h` | Adds a header to the file when printing, '-h' specifies the header. | ![20](https://github.com/ToDether/DevOps_labs/assets/127844719/81a97e99-5b8f-4e4a-be1e-3569e49c5941)|
| `pr -n` | Adds line numbers to the file. | ![21](https://github.com/ToDether/DevOps_labs/assets/127844719/335c6b61-c8b0-476c-bb3d-a4483473c2b2)|
| `lp -n c` or `lpr -# c` | Sends a file to the printer, '-n' specifies the number of copies. | `lp -n 2 file.txt` - prints two copies of file.txt |
| `lp -d` or `lpr -P` | Specify the destination | `lp -d printer_name file.txt` or `lp -P printer_name file.txt` |
| `apt-get` | APT package handling utility in Debian and Ubuntu, used for installing, updating, and removing packages. | ![22](https://github.com/ToDether/DevOps_labs/assets/127844719/3d3476d8-8a21-4507-975f-c90ec35cf376)|
