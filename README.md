# cmpe-283-2

## I finished this homework all by my self.

## How did I complete the assignment
1. Fork the repo https://github.com/jenniferhou762/linux
2. Clone it to local
3. Follow the link to prepre building the kernel https://wiki.ubuntu.com/Kernel/BuildYourOwnKernel
4. Check the kernel version by using uname -a, the result is: Linux qoshi-System 4.15.0-142-generic #146~16.04.1-Ubuntu SMP Tue Apr 13 09:27:15 UTC 2021 x86_64 x86_64 x86_64 GNU/Linux
5. Copy /boot/config-4.15.0-142-generic to linux repo, and make oldconfig.
6. Since I have a 8 core cpu machine, I am using make -j 8 modules && make -j 8 && sudo make modules_install && sudo make install to build and install the keneral.
7. Reboot the machine and verify the update using uname -a.
8. Make code change in cpuid.c and cmx.c.
9. Rebuild the kernel using  make -j 8 modules && make -j 8 && sudo make modules_install && sudo make install.
10. Reboot the system.
11. Verify the update using uname -a.
12. Follow https://help.ubuntu.com/community/KVM/Installation to setup KVM.
13. If you have the issue => https://askubuntu.com/questions/874976/unable-to-install-kvm-on-ubuntu-16-04, please visit this page https://askubuntu.com/questions/874976/unable-to-install-kvm-on-ubuntu-16-04.
14. Download another Linux image and use GUI to setup the nested VM.
15. Implement the test cases and tested.


