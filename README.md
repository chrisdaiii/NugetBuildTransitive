# NugetBuildTransitive
Nuget包的buildTransitive行为示例

当 ProjectA-net6.0 引用 ProjectB Nuget 包时，buildTransitive行为正常。  
当 ProjectA-net48 引用 ProjectB Nuget 包时，buildTransitive行为异常，没有拷贝文件到输出目录。

[关联Issue](https://github.com/NuGet/Home/issues/12483)

[NuGet来自基于约定的工作目录](https://learn.microsoft.com/zh-cn/nuget/create-packages/creating-a-package)

![Image](https://github.com/13750573877/NugetBuildTransitive/blob/5098f16de7137059203921ea9d6799cb7f06bee4/Structure.PNG)
