# Installation and setup step for termux

### 1.-> First download the Termux app with the link provided below please do not download it from the store cause many features are restricted in that verison. `[Download Termux](https://drive.google.com/drive/folders/100vDBFAnnHc5d2xVcQKZsCPLF0kC_IbS)`

### 2.-> Update termux: `pkg update -y`

### 3.-> upgrade termux: `pkg upgrade -y`

### 7.-> Give termux storage privilege: `termux-setup-storage`

         when you run this a system prompt will pop up on your screen asking if you want to give termux storage privilege: just click allow/accept.

### 4.-> Install git: `pkg install git -y`

### 4.-> Install a text-editior of your choice like vim or emacs: `pkg install vim -y` or `pkg install emacs -y`

         you can also install both to enjoy the best of both worlds 😂.


### 4.-> To Install a C/C++/C# Complier: `pkg install clang -y`

### 4.-> To Install a Python interpreter: `pkg install python3 -y`

### 7.-> Install x11-repo: `pkg install x11-repo`

        This is subjective, it's only necessary if you want to connect to any remote server **[SANDBOX]** using ssh.

### 7.-> Install root-repo: `pkg install root-repo`

        This is subjective, it's only necessary if you want to connect to any remote server **[SANDBOX]** using ssh.

### 4.-> install openssh: `pkg install openssh`

        This is subjective, it's only necessary if you want to connect to any remote server **[SANDBOX]** using ssh.

### 5.-> Install proot: `pkg install proot -y`

         This is subjective, if you want to install and use a linux distro in your termux then this is needed else you don't need it.

### 6.-> Install wget: `pkg install wget -y`

         This is subjective, if you want to install and use a linux distro in your termux then this is needed else you don't need it.
