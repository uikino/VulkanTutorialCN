# VulkanTutorialCN
Vulkan中文教程v1.0

原文地址：https://vulkan-tutorial.com/

原译者仓库：https://github.com/fangcun010/VulkanTutorialCN

由于本人才疏学浅，翻译难免有误，望各位不吝惜指正。


## 如何编译
1. 安装monaco字体或者在tex中修改为你自己喜欢的字体
2. 安装texlive，并且确保texlive已经添加到当前环境变量
3. 执行```xelatex -no-pdf  -synctex=1 -interaction=nonstopmode Vulkan编程指南.tex``` 生成xdv中间文件
4. 执行```xdvipdfmx  -E Vulkan编程指南```生成pdf文件


更换字体。英文字体：Monaco，中文字体：Source Han Sans CN
修正 ```VK_LAYER_LUNARG_standard_validation``` 为 ```VK_LAYER_KHRONOS_validation```

