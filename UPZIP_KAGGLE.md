# 一、如何解压7z类型文件？
# 解压7z文件所用的方式
```
%pip install py7zr
import py7zr
#7z文件所在的路径
a =py7zr.SevenZipFile(r'../input/cifar-10/train.7z','r')
a.extractall(path=r'./')
a.close()
```

# 二、如何解压zip类型文件
```
import zipfile
#zipfile解压
z = zipfile.ZipFile('../input/dogs-vs-cats/train.zip', 'r')
z.extractall(path=r"./")
z.close()
```
ref IMP: https://blog.csdn.net/weixin_42475060/article/details/119105588