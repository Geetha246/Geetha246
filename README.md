***User Guide for Vayyar CAN Gateway***

***Table of Contents***

[[_TOC_]]

# 1 Relevant Environment
    1. Working environment of CANdevStudio in WSL.
    2. RadarReply on Vayyar EVK to be connected via WSL IP Address.
    3. Virtual CAN or the CAN device to be connected.
    
# 2 Prerequisites
    1. WSL
    2. Windows compatible version: Windows 10, Version 1903, Build 18362 or higher.
    3. Xserver
    4. CANdevStudio
    5. Vayyar EVK V8.0.1
    6. CAN Adapter module

# 3 WSL2 Installation and Windows Requirement for WSL2

  ## 3.1 Setting WSL
      1. To check WSL Version in command line (in windows): 
        **wsl -l -v** 

      2. If WSL version is 1, invoke the below command to upgrade the version to WSL2.
        **wsl --set-version Ubuntu-18.04 2** 

