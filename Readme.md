# Material icons for ExtJS

classic版本的material icon

fork 自[ExtJS-Material-Icons](https://github.com/RichardStyles/ExtJS-Material-Icons)

将 [material-design-color-palette.css](https://github.com/zavoloklom/material-design-color-palette/tree/master/css) 合并了进去

## 用法
1. clone项目
2. 新建一个workspace，sencha.exe -sdk ext-6.2.0 generate workspace ext-workspace，将上述整个项目移到 ext-workspace\packages\local下
3. 到项目目录下执行   sencha package repo init -name "Your Name" -email "support@mycompany.com"初始化发布信息，修改package.json里的creator与name一致，再执行sencha.exe package build
4. 到ext-workspace\build\material-icons\找到material-icons.pkg，拷贝到需要引用的项目目录下
5. 新项目下执行 sencha.exe package add material-icons.pkg
6. 执行上述动作后，不要立即删除pkg，执行以下 sencha app watch,会自动将pkg解压到 packages\remote\material-icons目录，然后就可以安全删除了