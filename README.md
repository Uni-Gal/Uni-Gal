## UniGal


### UniGal-介绍

UniGal是一个希望能通过统一的语法标准和格式，允许从各种不同的引擎导入，并允许各游戏引擎的开发者构建支持UniGal的导入工具，实现类似ONNX一样的跨框架的方案支持，允许开发者快速从一套框架迁移到另一套更适合的框架，实现迈向开放世界的第一步。

### UniGal-代码格式

UniGal-Script是一种转为描述该框架设计的简单易用的语句。It includes conventions for

```XML
<?xml version="1.0" encoding="utf-8"?>
<unigal>
  <head>
    <src>
      BKE
    </src>
  </head>
  <body>
    <text>
      <name>
        NULL
        <comment>
          //姓名
        </comment>
      </name>
      <content>
        <part>
          坐在车厢里的人总会向外眺望。
        </part>
        <comment>
          //文本内容
        </comment>
      </content>
    </text>
    <text>
      <name>
        NULL
        <comment>
          //姓名
        </comment>
      </name>
      <content>
        <part>
          眺望的理由多种多样：
        </part>
        <action>
          newline
        </action>
        <part>
          晕车，发呆，欣赏风景……
        </part>
        <comment>
          //文本内容
        </comment>
      </content>
    </text>
    <text>
      <name>
        NULL
        <comment>
          //姓名
        </comment>
      </name>
      <content>
        <part>
          亦或者只是下意识地一瞥。
        </part>
        <comment>
          //文本内容
        </comment>
      </content>
    </text>
    <text>
      <name>
        NULL
        <comment>
          //姓名
        </comment>
      </name>
      <content>
        <part>
          但人们心中压抑的冲动都是相似的。
        </part>
        <comment>
          //文本内容
        </comment>
      </content>
    </text>
  </body>
</unigal>
```



——————————————————————————-

维护人员相关内容



For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Uni-Gal/Uni-Gal.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

You can use the [editor on GitHub](https://github.com/Uni-Gal/Uni-Gal.github.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.