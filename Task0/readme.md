**git init name**    
创建本地库   
 		
**git clone url**     
克隆远程库    克隆远程库，本地会生成与远程库相同本地库，可进行上传操作。

**git clone -b 分支名称   url（默认master）**  
克隆远程分支库，结果与上类似。

**cd  name**          
对生成的本地库进行操作，需要进入库文件夹

**git branch**         
查看本地库所有分支

**git branch 分支**   
创建分支

**git checkout 分支**   
切换分支

**git add __.__**    
添加文件 文件输入之后需要加空格 ，否则可能报错

**git commit -m ""**  添加版本信息

**git remote add name url**  
添加远程地址

**git remote -v**  
查看远程地址(默认创建地址名称为 origin)

**git pull**        
与远程同步，避免差异太大，每次上传前pull一下最好

**git push**      
默认上传，一般是上一次上传地址 或者 git push origin master 

**git push name maste**r   
上传，上传到地址为name的master主线主线，一般不建议这么使用


	一般本地库与远程库的分支名称，库名称相同，进行操作，最好一一对应。
