# Liii STEM的表格编号与引用

文档来自 [Liii STEM 官网](https://liiistem.cn/docs/guide-table.html)。该官网的文档会持续更新，墨干通常会及时同步更新内容，但可能存在一定延迟，请以官方文档为准。

## 一、功能介绍  

该功能旨在实现您文章中表格的**自动编号**，双向链接以保证序号的**自动更新**，以及在下文中规范而便捷地**引用**您的表格。本指南将帮助您实现下图展示的效果。  
![图1](../../images/tab_1.png)   

## 二、操作流程

#### *STEP 1.* 插入表格  
- 在工具栏依次点击`插入` -> `表格` -> `小表格`（如下图所示）  
![图2](../../images/tab_2.png)  
- 点击工具栏上带有"+"或"×"的上下左右`箭头`，以添加或删除行和列（如下图所示）
![图3](../../images/tab_3.png)  
>  注：一般情况下，在您插入表格后系统会自动编号。如发现未编号，您可将光标置于表格上，点击工具栏上的`Ⅳ`式样按键（如下图所示）自行实现。  
>  ![图4](../../images/tab_4.png)  

#### *STEP 2.* 表格命名

- 将光标置于表格说明的末尾，确保输入法为英文模式   
- 点击`\`，输入`label`，（或使用快捷键：`ctrl`＋`!`），点击`回车`  
- 输入您表格的名称，如"Table1"，点击`回车`（如下图所示）  
![图5](../../images/tab_5.png)  

#### *STEP 3.* 建立双向链接

- 在您需要引用该表格的地方   
- 点击`\`，输入`ref`，点击`回车`   
- 再次输入您刚才命名的表格名称，点击`回车`（如下图所示）    
![图6](../../images/tab_6.png)  

#### *STEP 4.* 插入Non-breaking Space

- 将光标置于您想插入的位置    
- 按住`空格`，点击`tab`（如下图所示）    
![图7](../../images/tab_7.png)    
> 注：Non-breaking Space，即"不间断空格"，可以确保前后两部分位于同一行，不会因为换行而断开。