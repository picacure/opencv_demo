# opencv_demo
opencv demo and extension


## setup on mac

+ 下载opencv for mac安装源文件，解压缩
+ 安装cmake程序。笔者使用的是Homebrew，在终端中输入：“brew install cmake”，自动安装cmake。
+ 进入存放解压后的opencv文件夹，新建一个空的文件夹release

          mkdir release
               
          cd release
          
          cmake -G "Unix Makefiles" ..
          
          make
          
          sudo make install
     
+ 安装好的lib文件存放在“/usr/local/lib”文件夹，h文件存放在“/usr/local/include”



# REF

+ [Link](http://tilomitra.com/opencv-on-mac-osx/)
