- Switch to [English](#english-version)

<p lang="zh">

# 关于该仓库的声明：

我上传这些资料，旨在和广大学习者自由交流讨论。该库文件中：至少包括**SolusMan-SupplementMIRA.pdf**和**SourceCode**目录下的**png, jpg, ggb**文件，除去‘by-nc-sa.png’，都是在**CC0**协议下的。至少包括**SourceCode**目录下的**SolusMan-SupplementMIRA.tex**、**Ch012345.tex**、**Settings.tex**，是在**CC BY NC SA**条款约束下的，仅允许非商业用途的修改、复制、转发、衍生等，并且需要为副本/衍生作品使用与原作相同的协议（传染性）。这是因为原作SupplementMIRA和MIRA是在**CC BY NC**下发布的。所以其衍生作品允许（哪怕是一点点）商用是非法的，其许可证也是无效的。

> 该仓库是GitHub与Gitee双向同步的；这是因为对国人来说，访问Gitee比访问GitHub容易。


---

# 关于库中文件的说明：

### **SourceCode**文件夹

这个文件夹包含ttf和otf字体文件、tex源代码、调用的sty头文件。这些文件用于生成**SolusMan-SupplementMIRA.pdf**。主要就是，用**TeXstudio**, **Texmaker**或者其他IDE，亦或者编译器，编译**SolusMan-SupplementMIRA.tex**，输出PDF二进制版本。

> 该目录下的.ttf和.otf字体文件在(L)GPL条款下。该目录下**Headers**文件夹中**extrarrows.sty**在LGPL条款下。

为了更高的实时编译效率，我将代码架构为 **Settings**（Settings.tex）、**Chxxx**（Ch012345.tex）、**Main**（SolusMan-SupplementMIRA.tex）。

### **SolusMan-SupplementMIRA.pdf**

##### Licensed under CC BY NC SA 4.0

见**SolusMan-SupplementMIRA.pdf**第一页。

### **MyConfigures**

这是我个人编写LaTeX代码时使用的**TeXstudio**配置。

### 「附：如何配置LaTex」 Trisquel/Ubuntu系统Terminal下

> sudo apt install texlive
>
> sudo apt install texlive-xetex
>
> sudo apt install texlive-lang-chinese
>
> sudo apt install texstudio

即可。其他系统下，差不多也就 texlive、xetex、中文语言包、texstudio 这些。

</p>

# English Version

<p lang="en">

# About this repo:

The purpose of me uploading these materials, is to communicate with as many learners, teachers, scholars, etc. as possible. The files in this repo, at least containing **SolusMan-SupplementMIRA.pdf** and **.png, .jpg, .gbb** files under the **SourceCode** directory, except for `by-nc-sa.png', are all licensed under **CC0**; files at least containing **SolusMan-SupplementMIRA.tex**, **Ch012345.tex**, **Settings.tex** in the **SourceCode** directory, are licensed under **CC BY NC SA**.

You are free to (re)distribute, modify, or copy any part or whole of those files, as long as in non-commerical use, and as long as you release your Derivative Work under the same License. See **LICENSE** for more details.


# About the files:

### The **SourceCode** directory

Including font files in .ttf, .otf, source files in .tex, header files in .sty. These files are used in generating **SolusMan-SupplementMIRA.pdf**, by **TeXstudio**, or **Texmaker** or other IDE, or simply a compiler.

> The .ttf, .otf font files are licensed under (L)GPL. **extrarrows.sty** in the **Headers** directory is licensed under LGPL.

In order to reduce compile time during coding and testing, I seperate my source code into parts including **Settings**(Settings.tex), **Chxxx**(Ch012345.tex), **Main**(SolusMan-SupplementMIRA.tex).

### **SolusMan-SupplementMIRA.pdf**

##### Licensed under CC BY NC SA 4.0

See the first page of **SolusMan-SupplementMIRA.pdf**. You may need a translator.

### **MyConfigures**

My personal configures for **TeXstudio**.

#### How to configure your LaTex by Terminal under the Trisquel/Ubuntu system ? Just type:

> sudo apt install texlive
>
> sudo apt install texlive-xetex
>
> (optional) sudo apt install texlive-lang-chinese
>
> sudo apt install texstudio


</p>
