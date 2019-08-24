# cps-cheatsheets

inspired by [devhints.io](https://devhints.io/)

most cheatsheet snippet forked from [rstacruz/cheatsheets](https://github.com/rstacruz/cheatsheets), although i makes some parse-style changes to better suite  [coderplanets.com](https://www.coderplanets.com) use cases.


# contribute

以 [elixir 社区的 cheatsheets](https://coderplanets.com/elixir/cheatsheet) 为例: 

对应的源文件为当前仓库下的 [elixir.md](https://github.com/coderplanets/cps_cheatsheets/blob/master/elixir.md)（以语言或框架的的名字为文件名），文件中的 `{{ ::cards-header:: }}` `{{ ::card-item:: }}` `{{ ::group:: }}` 会被当做标识符用于将相关内容解析为卡片的形式，相关对应关系如下所示：

![image](https://user-images.githubusercontent.com/6184465/63632238-13575d80-c665-11e9-939c-754879d3f0a2.png)

{{ ::group:: }} 用作每一个大类的分隔符，比如分隔 Basic Types 和 Control Flow, Control Flow 与 Types 等等

![image](https://user-images.githubusercontent.com/6184465/63632345-edcb5380-c666-11e9-82e6-bcac2d0d3620.png)

