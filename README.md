EditorConfig
===
**.editorconfig** for every project.

#What is EditorConfig
> EditorConfig helps developers define and maintain consistent coding styles
> between different editors and IDEs. The EditorConfig project consists of a
> file format for defining coding styles and a collection of text editor
> plugins that enable editors to read the file format and adhere to defined
>styles. EditorConfig files are easily readable and they work nicely with
> version control systems.
 -- [http://editorconfig.org](http://editorconfig.org/)

#What is in the configuration?
- **Default**
    - charset = utf-8
    - end_of_line = lf 
    - trim_trailing_white_space = true
    - insert_final_new_line = true
- **Javascript/NodeJS**  [reference](https://github.com/anyTV/JS-conventions#manifesto)
    - indent_style = space
    - indent_style = 4
- **Python** [reference](https://github.com/anyTV/Python-conventions#code-layout)
    - indent_style = space
    - indent_style = 4
- **PHP** [reference](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md#1-overview)
    - indent_style = space
    - indent_style = 4
- **HTML File** 
    - indent_style = space
    - indent_style = 4
- **Bash** [reference](https://google.github.io/styleguide/shell.xml?showone=Indentation#Indentation)
    - indent_style = space
    - indent_style = 2
- **Markdown** 
    - trim_trailing_whitespace = false
    - indent_style = space
    - indent_size = 4
- **GO lang** [reference](https://golang.org/cmd/gofmt/)
    - indent_style = tab
- **Makefile**
    - indent_style = tab
- **.ini File**
    - indent_style = space
    - indent_style = 4
- **.json File** 
    - indent_style = space
    - indent_style = 2
- **.yml File** 
    - indent_style = space
    - indent_style = 2
- **.babelrc** 
    - indent_style = space
    - indent_style = 2

#How to use?
- Copy .editorconfig from this repository to the root of your project repository.
- Install EditorConfig plugins for your repository. You can get the plugins [here](http://editorconfig.org/#download).
