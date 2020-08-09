## 四、matlab.m脚本文件

## 1.M文件

matlab允许编写两种程序文件

- 脚本
  - 脚本文件是以`.m`扩展名的程序文件。在这些文件中，可以编写一系列要一起执行的命令。脚本不接收输入，不返回任何输出。它们对工作空间中的数据进行操作。
- 函数
  - 函数文件也是以`.m` 的程序文件。函数可以接受输入和返回输出。内部变量是函数的局部变量

**使用** *matlab* **编辑器或任何其他文本编辑器来创建.m文件**

**脚本文件包含多个连续的***matlab***命令行和函数调用**

**可以通过在命令行中键入其名称来运行脚本**

## 2.创建和运行脚本文件

- 要创建脚本文件，需要使用文本编辑器，可以通过两种方式打开matlab编辑器：
  - 使用命令提示符
  - 使用IDE
- 如果使用命令提示符，请在命令提示符下键入`edit`并回车，这将打开编辑器。可以直接键入edit，然后直接输入文件名(扩展名为`.m`)
  - 上述命令将在默认的matlab目录中创建该文件。如果要将所有程序文件储存在特定文件夹中，则必须提供整个路径
  - 创建文件夹  `mkdir` 再转到所创建的目录下 `cd` 再 `edit 文件名.m`
- 如果使用IDE，请选择*“新建”*->“脚本”。
- 创建并保存文件后，可以通过两种方式运行：
  - 单击编辑器窗口上的“运行”按钮
  - 只需在命令提示符下键入文件名（无扩展名）即可： >>prog1
  - 示例：代码
    - 文件路径：![avatar]（E:\MatlabNote\progs）


[第四章参考](https://www.yiibai.com/matlab/matlab_m_files.html "点我")