# 使用 elegantBook.cls 做 pdf 的示例



elegantbook.cls 是一个写 tex文档的模板，你可以类比是写 C++ 时的 `#include`，把这玩意儿从 [Github仓库](https://github.com/ElegantLaTeX/ElegantBook)  直接下载下来，配合 tex video 会做出挺好看的 pdf 文档。它好像不更新了，没事。

**为什么有这个？** 一开始不会用，没有参照。它原来提供的 pdf 也只是像说一下讲自己的特点，没有具体将怎么怎么写的。我这里提供了一个介绍和 使用的示例。

## 仓库内容

```
├── example
│   ├── testl.tex       # 参考
│   ├── test2.tex
│   └── ...
├── figure              # 写法介绍pdf本身用的封面      
├── image               # 同上，本身用的图片
├── Makefile
├── ...
├── elegantbook.cls     # 核心，就是讲这个开源库的用法
├── howtowrite.tex      # 主文件，介绍pdf
└── README.md
```

介绍的 内容就是 howtowrite.tex，因为往后可能越写越多，就只放 tex，对应的pdf 可以见 [pan](https://pan.baidu.com/s/1T6SEseYnlIoAGFavyS-hXQ?pwd=2023) ，应该点开就直接能看到。有的好点的阶段性版本也挂在 tag 里；示例都在 example目录；Makefile 是清理编译生成的辅助文件用的，你不 clone 了直接编译的话没什么用。

## 使用方法

主要就是看 `howtowrite.pdf` 和 example目录里的 tex 文档。里面tex 和 pdf 两个都提供。你想 用哪个，就想看 pdf 里什么样子。再复制同名 tex文件里的内容就行。

> 只是 windows 用 `TeXstudio` 写文档用，其他系统和 IDE 不清楚。

