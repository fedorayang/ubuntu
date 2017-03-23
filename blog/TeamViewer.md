sudo apt-get install libdbus-1-3:i386 libasound2:i386 libexpat1:i386 libfontconfig1:i386 libfreetype6:i386 libjpeg62:i386 libpng12-0:i386 libsm6:i386 libxdamage1:i386 libxext6:i386 libxfixes3:i386 libxinerama1:i386 libxrandr2:i386 libxrender1:i386 libxtst6:i386 zlib1g:i386 libc6:i386

sudo dpkg -i teamviewer*.deb

这是一个32位的deb包。Debian 6/Ubuntu 10等旧发行版本可以下载64位deb包，因为它们没有Multiarch多架构功能。对于Ubuntu 16.04，我们必须下载32位deb包，因为Ubuntu 16.04具备多架构功能，即使是64位的Ubuntu 16.04系统也能安装32位的deb包。

如果你需要从Android手机或Android平板远程控制Ubuntu系统，可以在Android系统里安装TeamViewer for Remote Control应用，输入Ubuntu系统的ID就OK了。

