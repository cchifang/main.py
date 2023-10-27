# financiak_Basic
# 复利计算器
* 简介:
这个程序是一个用 Python 编写的复利计算器，它可以帮助您计算复利，并将结果保存到文本文件中。您可以在设置文件 setting.xml 中指定计算所需的参数，然后运行程序以获得结果。

## 使用方式
* 步骤 1：设置参数
打开 setting.xml 文件，并根据您的需求编辑以下参数：
```
<data>
    <x>10000</x>  <!-- 本金 -->
    <s>10</s>     <!-- 年利率 -->
    <y>20</y>     <!-- 投资年份 -->
</data>
<x>: 输入您的本金金额。
<s>: 输入年利率。
<y>: 输入投资年份。
```


* 步骤 2：运行程序
运行程序，它会读取 setting.xml 中的参数，计算复利，并将结果保存到 result.txt 文件中。

* 步骤 3：查看结果
打开 result.txt 文件，您将看到以下信息：
```
本金:10000
年利率:10
投资年分:20
------以下是您可以得到的總金額------
22064.47元
这是您的计算结果，包括本金、年利率、投资年份和最终总金额。
```
**注意事项**
请确保 setting.xml 文件中的参数是整数或浮点数，并按照示例格式进行编辑。
确保您已安装 Python，并且已将程序文件和 setting.xml 文件保存在同一目录中。
如果需要更改计算参数，只需编辑 setting.xml 文件，然后重新运行程序。
这个程序可以帮助您快速计算复利，希望您能方便地使用它。如果您有任何问题或建议，请随时联系我们。

祝您投资顺利！
