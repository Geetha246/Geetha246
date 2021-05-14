# 3 WSL2 Installation and Windows Requirement for WSL2

  # 3.1 Setting WSL
      1. To check WSL Version in command line (in windows): 
        ```bash
        wsl -l -v 
        ```
      2. If WSL version is 1, invoke the below command to upgrade the version to WSL2.
        ```bash
        wsl --set-version Ubuntu-18.04 2 
        ```

  # 3.2 Initial Setup in WSL2
      1. Update the WSL, in WSL shell
         **sudo apt update**

      2. Upgrade the WSL, in WSL shell
         **sudo apt upgrade**

      3. Restart the WSL, in Windows Command Prompt
         **wsl --shutdown**

      4. Install/build essential libraries (includes many libraries ex. gcc, g++ ...), in WSL shell

         **sudo apt-get install build-essential flex bison libssl-dev libelf-dev**
         **sudo apt install unzip**

      5. Install cmake, in WSL shell invoke
         a. For version 3.10.0
         **sudo apt install cmake**

         b. For version 3.16.5

         **sudo apt-get install build-essential flex bison libssl-dev libelf-dev**
         **wget** [Download cmake version 3.16.5] https://github.com/Kitware/CMake/releases/download/v3.16.5/cmake-3.16.5.tar.gz
         **tar -zxvf cmake-3.16.5.tar.gz**
         **cd cmake-3.16.5**
         **sudo ./bootstrap**
         **sudo make**
         **sudo make install**
