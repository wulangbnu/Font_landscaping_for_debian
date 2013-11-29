Font landscaping for debian 

1.System -> Preference -> Appearance -> Fonts -> Rendering -> Details -> Hinting -> Slight
2.copy directory  etc_fonts to /etc/fonts/
  sudo cp -r etc_fonts/*   /etc/fonts/  
3.cocy directory  usr_share_fonts to /usr/share/fonts/
  sudo cp -r usr_share_fonts/*   /usr/share/fonts/ 
4.just reboot you computer ans enjoy it!


debian中文字体美化

1.系统->首选项->外观->字体->渲染->细节->微调->轻微 
2.复制　etc_fonts　文件夹内所有文件到 /etc/fonts/ , 并赋予用户读权限
  sudo cp -r etc_fonts/*   /etc/fonts/  
3.复制　usr_share_fonts　文件夹内所有文件到  /usr/share/fonts/ ,  并赋予用户读权限
  sudo cp -r usr_share_fonts/*   /usr/share/fonts/ 
4.重启电脑即可
    
wulangbnu  20131129
