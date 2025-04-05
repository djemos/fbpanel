**fbpanel**   
fbpanel is a lightweight GTK2-based panel for UNIX desktop,  
which provides graphical information and feedback about desktop activity  
and allows interaction with the window manager.  
It features a taskbar, pager, launchbar, show desktop, image viewer, clock, and system tray.  
This is a modified 7.2 version for Slackel linux. Greek translation added by Dimitris Tzemos to fbpanel-7.2.  
You have also to install wm-logout package.  

To download and create the package type:  
  
mkdir build   
cd build  
git clone https://github.com/djemos/fbpanel.git fbpanel-7.2   
  
tar -czvf fbpanel-7.2.tar.gz fbpanel-7.2  
mv fbpanel-7.2/SLKBUILD ./  
mv fbpanel-7.2/el_GR.UTF-8.po ./  
mv fbpanel-7.2/el_GR.UTF-8.mo ./  
mv fbpanel-7.2/disable-scroll.patch ./  
mv fbpanel-7.2/fbpanel-addon.tar.gz ./  
mv fbpanel-7.2/default-en ./  
mv fbpanel-7.2/default-el ./  
  
fakeroot slkbuild -X  
  
To install the package type:  
for 64bit:  
sudo spkg fbpanel-7.2-x86_64-1dj.txz  
  
or for 32 bit:  
sudo spkg fbpanel-7.2-i586-1dj.txz   
  

![fbpanel-el](https://github.com/user-attachments/assets/a7cfa42b-4044-454d-8571-6946ae77f8f9)

![fbpanel-en](https://github.com/user-attachments/assets/2dd8a085-3d3c-4661-8145-f78c4a431113)





