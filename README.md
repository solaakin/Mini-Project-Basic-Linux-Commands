# Mini-Project-Basic-Linux-Commands

# 1 What is a Linux Command?

 ### "A Linux command" is an instruction that you input into the Linux terminal to perform a specific task. It typically consists of:

 - **Command Name:** The main instruction which is (e.g., ls, cd, pwd).
   
- **Option or Flag:** Additional options to modify behavior are (e.g., ls -a, where -a is a flag).
  
- **Parameter or Argument:** The target (e.g., cd /home/user, /home/user is the argument).

 **Also NOTE:**  Linux is case-sensitive. CD and cd are different commands.

# 2 Manipulating Files and Directories

- **Creating a directory(mkdir)**

 ![mkdir](https://github.com/user-attachments/assets/bd1bcc79-7fd8-4b1b-bd1a-e21f80350983)

 - **Changing into a directory** (cd my Directory)

 ![CdMyDirectory](https://github.com/user-attachments/assets/0e0d391b-ce98-4a6d-8a15-2a5e77f6b486)

 - **creating a new file**  (touch my file.txt)

 ![ TouchMyFile](https://github.com/user-attachments/assets/fec64bbc-cda8-4708-b246-96b9c8ecba3d)

 - **veiwing file in a new directory**  (ls)

 ![ls](https://github.com/user-attachments/assets/b087e9f2-bd3f-4e0c-b37b-773bffecea8f)

 - **moving a file** (Directorymv)

 ![Directorymv](https://github.com/user-attachments/assets/d7bda5ca-7279-4ecb-af13-75fbf0f9d0ce)

 - **Deleting a file** (rm myfile.txt)

 ![ rm](https://github.com/user-attachments/assets/88476ce9-20aa-48d0-8b3b-431640ab41e7)

 - **Deleting a directory** (rmdir a directory)

 ![ rmdir](https://github.com/user-attachments/assets/58dc6a98-2a32-464e-b62a-89300268170b)

# 3  Using The sudo Command
- **Without the sudo**  (mkdir the root/my folder)
### The Result
#### mkdir (cannot delete directory '/root/myfolder':permission denied

 ![rootwithoutsudo](https://github.com/user-attachments/assets/25b698ca-9f03-4b4d-9cc8-30c6bc3bbd5c)

- **sudo creation**
  
  sudo mkdir /root/myfolder
  
 ![sudocreation](https://github.com/user-attachments/assets/a81feaa4-efe5-42c3-9033-144cc01dbb9c)

 - **Verify folder creation**

    sudo ls /root

 ![ Sudols](https://github.com/user-attachments/assets/a3a1a0ad-2e8d-4f8f-b159-1f669dccf928)

# 4 Pwd Command (Print Working Directory)

- **Command** (Pwd)

- **Output**  (/home/username)

- **Pwd command** indicate the absolute direction of the current working directory.

 ![pwd](https://github.com/user-attachments/assets/55a5c632-9501-4d75-8dc5-0b5da06cb6c9)

 # 5 Linux Directory Structure

 # The steps

 - / - Root directory (top of the hierarchy)
 - /bin - Essential binary files (e.g., basic commands like ls, cp)
- /etc - Configuration files
- /home - Home directories for users
- /root - Home directory for root user
- /var - Variable files (logs, spool files)
- /usr - User programs and data


 # Exploring with ls:

 ls /
ls /bin
ls /etc
ls /home
ls /root
ls /var
ls /usr


# 6. The cd Command (Change Directory)

- Navigate to root  (cd/pw)

- output      (/)

 ![ Cdroot](https://github.com/user-attachments/assets/1d7c707d-6f78-499e-992c-efb66fbc1c53)

  - List contents  (ls)

![1lsroot](https://github.com/user-attachments/assets/b7a6882f-79f2-441c-83d5-b72660b03aa4)

- Navigate into /usr:
- cd usr
- pwd

![ cdusr](https://github.com/user-attachments/assets/4481211d-1d13-4719-bce8-89d63c373ded)

# 7. Side Hustle Task 1 — Creating Directories

- **Create a photos directory inside /usr**

sudo mkdir /usr/photos

- Navigate into photos

cd /usr/photos

![ mkdirphotos](https://github.com/user-attachments/assets/25d78bd6-f87b-458a-98e0-8249adcd8953)

- **Create 3 random folders inside photos**:
  
sudo mkdir folder2 folder3 folder4

- Show newly created folders

ls

![ mkdirmultiplephotos](https://github.com/user-attachments/assets/6c681b2e-b7f0-47e3-97d4-a8452712a374)

- **Navigate into one folder**:
- 
cd folder1

- **Show full path**:
  
pwd

- **Output**:
  
/usr/photos/folder1

![cdfolder1](https://github.com/user-attachments/assets/aa0f6fe0-d30b-4e2d-af1f-a412b37363bb)

# 8. Using ls Command

- **List contents of a directory**:

  ls

- List recursively
 
  ls -R

  ![lsrecursive](https://github.com/user-attachments/assets/ebe4740d-1d87-4a2b-be64-7dfe19d48a15)

-** List hidden files**:
  
ls -a

![lshiddenfile](https://github.com/user-attachments/assets/04744089-c2dc-4d43-896b-6fd9dafd7db4)

- **List in human-readable format**:
  
ls -lh

![lslh](https://github.com/user-attachments/assets/9354b044-6e03-4d42-a739-eefe6be9e767)

# 9. Using cat Command

- **Display content of a file**:
  
cat /etc/os-release

- **Output Example**:
- 
NAME="Ubuntu"

VERSION="22.04.3 LTS (Jammy Jellyfish)"

ID=ubuntu

![ catetcos](https://github.com/user-attachments/assets/7db01d47-7fa4-48d1-8185-88de6b05e30c)

 # 10. Using the cp Command

 - **Copy a single file**:

cp file1.txt /home/username/

![ file1tohome](https://github.com/user-attachments/assets/16daa0e0-a5ff-4c3a-b162-c99c4ef167d0)

- **Copy multiple files**:

cp file1.txt file2.txt /home/username/

![23 cpmultiplefile](https://github.com/user-attachments/assets/008dae37-a74a-4a0a-ae65-7db67c6bfdc7)























