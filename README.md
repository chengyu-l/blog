## Welcome to GitHub Pages

建立 Hugo 项目
一个 Hugo 项目就是一个站点，创建命令如下：
hugo new site [project-name]
复制代码例如我的站点名称是 blog,创建命令如下：
hugo new site blog
复制代码创建完成后，在 blog 文件夹下会生成以下文件结构：
.
├── archetypes # 存放生成博客的模版
├── assets # 存放被 Hugo Pipes 处理的文件
├── config # 存放 hugo 配置文件 支持 JSON YAML TOML 三种格式配置文件
├── content # 存放 markdown 文件
├── data # 存放 Hugo 处理的数据
├── layouts # 存放布局文件
├── static # 存放静态文件 图片 CSS JS文件
└── themes # 存放主题


启动 Hugo
进入 blog/themes/even/exampleSite 文件夹，将 config.tom 文件拷贝到项目根目录下，同时将 blog/themes/even/exampleSite/content 文件夹覆盖掉根目录下的 content 。
命令行输入以下命令，启动 Hugo :
hugo server
复制代码在浏览器打开 http://localhost:1313/ 即可查看效果。

打包
为了部署到线上，需要将 Markdown 文件打包成 HTML 文件。打包命令如下，even 是主题名：
hugo -t even



You can use the [editor on GitHub](https://github.com/chengyu-l/blog/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/chengyu-l/blog/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
