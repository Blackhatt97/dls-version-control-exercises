## Cheatsheet

A collection of useful shell commands to use throughout the exercises:

```sh
# Create empty directory
mkdir getting-started
# Change to a directory
cd getting-started

# Go back one folder
cd ..
# Go back 2 folders
cd ../..

# Create a new empty file
touch new-file.txt
touch me # Gotta love unix
# Or this command:
echo -n > new-file.txt # -n tells echo to not output trailing newline

# List files in current directory
ls
# List all files (incl. hidden files) in the current directory:
ls -a
# List files in the previous directory
ls ..

# Print current directory
pwd

# Delete a file (use at your own risk)
rm new-file.txt

# Write stuff to a file
echo "Hello World!" > new-file.txt
# Append stuff to a file
echo "Hello World!" >> new-file.txt
```
