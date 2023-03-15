# NugetBuildTransitive
Nuget包的buildTransitive行为示例

当 ProjectA-net6.0 引用 ProjectB Nuget 包时，buildTransitive行为正常。  
当 ProjectA-net48 引用 ProjectB Nuget 包时，buildTransitive行为异常，没有拷贝文件到输出目录。
