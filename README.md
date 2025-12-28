# Linux_Basics_assignment
# 1. Creating and Renaming Files/Directories
Commands:
mkdir test_dir
cd test_dir
touch example_tutedude.txt
mv example_tutedude.txt renamed_example_tutedude.txt
<img width="900" height="298" alt="image" src="https://github.com/user-attachments/assets/a4cb46bb-8a72-49d4-897c-822c40c1d158" />

Explanation:
- mkdir creates a directory on the current path.
- touch creates an empty file without data.
- mv renames the file.
 
# 2. Viewing File Contents
Commands:
cat /etc/passwd
head -n 5 /etc/passwd
tail -n 5 /etc/passwd

Explanation:
- cat displays full file content.
- head shows first 5 lines.
- tail shows last 5 lines.
 <img width="900" height="931" alt="image" src="https://github.com/user-attachments/assets/aedd532c-cfb0-4557-bd3c-78de69fa5111" />

# 3. Searching for Patterns
Command:
grep "root" /etc/passwd

Explanation:
- grep searches for lines containing 'root'.
 <img width="900" height="99" alt="image" src="https://github.com/user-attachments/assets/d6ab6d1b-1f77-4a8e-bbaf-beec0bb8053d" />

# 4. Zipping and Unzipping
Commands:
zip -r madhu_zip_practice madhu_zip_practice
unzip test_dir.zip -d unzipped_dir

Explanation:
- zip compresses directory.
- unzip extracts files.
 <img width="900" height="363" alt="image" src="https://github.com/user-attachments/assets/8b1d3164-7245-43c1-9ef1-566e31071b81" />

# 5. Downloading Files
Command:
wget https://example.com/sample.txt

Explanation:
- wget downloads files from the internet.
 <img width="900" height="431" alt="image" src="https://github.com/user-attachments/assets/421dd112-3042-43d0-8e1d-b0b3bc0063d7" />

# 6. Changing Permissions
Commands:
touch secure.txt
chmod 444 secure.txt

Explanation:
- chmod 444 sets read-only permission for everyone.
 <img width="900" height="254" alt="image" src="https://github.com/user-attachments/assets/f84a11c8-1bc5-4b37-b13d-d4a9d76a65fe" />

# 7. Environment Variables
Command:
export MY_VAR="Hello, Linux!"

Explanation:
- export sets environment variables. 
<img width="900" height="102" alt="image" src="https://github.com/user-attachments/assets/717276a6-8ab0-486c-a151-9435e9939d8a" />

