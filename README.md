# UniGal


## UniGal-介绍

UniGal是一个希望能通过统一的语法标准和格式，允许从各种不同的引擎导入，并允许各游戏引擎的开发者构建支持UniGal的导入工具，实现类似ONNX一样的跨框架的方案支持，允许开发者快速从一套框架迁移到另一套更适合的框架，实现迈向开放世界的第一步。

UniGal是一个完整的项目，分为[Script](https://github.com/Uni-Gal/UniGal-Script)(脚本语法)、[Diagram](https://github.com/Uni-Gal/UniGal-Diagram)(流程图语法)、[Complier&Interpreter](https://github.com/Uni-Gal/UniGal-Complier-Interpreter)(编译器和解释器)三部分。您可以点击进入不同子项目的仓库查看。此外，UniGal也有自己的异常处理提案UEP，若要进一步了解请移步[ExceptionProposal(UEP)](https://github.com/Uni-Gal/UniGal-ExceptionProposal)。

## UniGal-下载

#### UniGal-Script

A kind of mark script for separate different part of Galgame script 

Uni-Gal-UniGal-Script-v0.0.2-57-gfa94efe

[zip **CRC32**59864506](https://github.com/Uni-Gal/UniGal-Script/zipball/master) [tar **CRC32**40A6330D](https://github.com/Uni-Gal/UniGal-Script/tarball/master)

#### UniGal-Diagram

Offer a visuable way to switch and show the different possibility of a Galgame 

Uni-Gal-UniGal-Diagram-01283b6

[zip **CRC32**115495DC](https://github.com/Uni-Gal/UniGal-Diagram/zipball/main) [tar **CRC32**7FF3353D](https://github.com/Uni-Gal/UniGal-Diagram/tarball/main)

#### UniGal-Complier&Interpreter

Complier and official Interpreter of UniGal-Script 

Uni-Gal-UniGal-Complier-Interpreter-0d3b772

[zip **CRC32**EB7F021F](https://github.com/Uni-Gal/UniGal-Complier&Interpreter/zipball/main) [tar **CRC32**8446DA39](https://github.com/Uni-Gal/UniGal-Complier&Interpreter/tarball/main)

#### UniGal-ExceptionProposal

The warnings and errors of UniGal summarised into a documented proposal 

Uni-Gal-UniGal-ExceptionProposal-7bdb82e

[zip **CRC32**3A691B8A](https://github.com/Uni-Gal/UniGal-ExceptionProposal/zipball/main) [tar **CRC32**9C35151B](https://github.com/Uni-Gal/UniGal-ExceptionProposal/tarball/main)



## UniGal-代码格式

### UniGal-Script

UniGal-Script是一种转为描述该框架设计的简单易用的语句。

```XML
<?xml version="1.0" encoding="utf-8"?>
<unigal>
  <head>
  </head>
  <body>
    <text>
      <name>
      </name>
      <content>
      </content>
    </text>
  </body>
</unigal>
```

要查看完整的代码格式和文档，您可以[点击这里查看](https://github.com/Uni-Gal/UniGal-Script/blob/master/Docs/zh_CN/UniGal-main.md#%E5%85%A8%E9%83%A8%E5%8A%9F%E8%83%BD%E7%9A%84%E4%BB%A3%E7%A0%81%E7%A4%BA%E8%8C%83%E5%8E%9F%E5%9E%8Bprototype)完整文档或[点击这里查看](https://github.com/Uni-Gal/UniGal-Script/blob/master/Docs/zh_CN/UniGal-main.md#%E5%85%A8%E9%83%A8%E5%8A%9F%E8%83%BD%E7%9A%84%E4%BB%A3%E7%A0%81%E7%A4%BA%E8%8C%83%E5%8E%9F%E5%9E%8Bprototype)目录树

### UniGal-Diagram

```XML
<node>
  <identification>
  </identification>
  <description>
  </description>
  <type>
    <switch>
    </switch>
    <action operation="add"><!--此外还有sub,multiply,divide,square,not-->
    </action>
  </type>
  <loop>
  </loop>
  <nextlist>
  </nextlist>
  <sourcelist>
  </sourcelist>
  <addtional><!--以下均为选加，也可以需要啥加啥-->
  </addtional>
</node>
```

要查看完整的代码结构和文档，您可以[点击这里查看](https://github.com/Uni-Gal/UniGal-Diagram/blob/main/prototype.xml)

### UniGal-Complier&Interpreter

```
Waiting to fill
```



## 联系与支持

~~联系我们（X）~~

联系我（√）

Email：keaitianxinmail@qq.com
