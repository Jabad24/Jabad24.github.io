Arch Install and Setup Documentation 

To begin with I read the Arch Wiki and  installed/downloaded the archlinux-2025.11.01-x86_64.iso file, uploaded it, and created my virtual machine. I ran into a problem right from the start. I didn't set enough memory, so I had to restart my VM right away. I changed the settings, and after getting the internet connection, I started installation. I got to disk formatting and setup; I partitioned and formatted the disk and mounted it—the installation process allowed for the package installation for the new system. I configured my timezone with timedatectl set-timezone America/New_York and created an administrator user with my name passwd useradd -m -G wheel josue passwd josue Then I did the same for Codi's username. From there, I could start installing the GUI packages. I encountered some issues where some of the packages didn't install completely, but I was able to reinstall them and finish the installation. After that I added in color coding. Green meaning a correct bash script was written and red for an incorrect script 
<img width="512" height="41" alt="unnamed (1)" src="https://github.com/user-attachments/assets/6125a70f-7460-4d87-9c77-a575e344acb9" />

I began to install the ssh then but I ran into a bit of trouble because it wouldn't install. After some trial and error I figured it out. 
<img width="512" height="127" alt="unnamed (2)" src="https://github.com/user-attachments/assets/ad7047d4-9baa-42ef-83b8-a66d41e5ddde" />


I also created six custom aliases in my shell configuration to make command-line navigation easier. Two of these aliases were alias ll='ls -lh' and alias la='ls -A'. The ll alias displays files in a long, human-readable format, while la lists all files, including hidden ones. I also included an alias for my linux to always stay updated when I bash in “update”

  <img width="488" height="99" alt="unnamed (3)" src="https://github.com/user-attachments/assets/5c89ee94-70c8-4172-a542-4e3d0a221f77" />
 
All in all I did not run into many problems. My biggest problem I had was setting the amount of storage when running the VM because if I didn't set enough I would have to start all over again. 
