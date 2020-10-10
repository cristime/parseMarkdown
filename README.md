## Python 解析 Markdown

#### 如何安装？

1.  Linux(使用 apt 包管理器)

   ```bash
   $ bash "$(curl -fsSL https://raw.githubusercontent.com/cristime/parsemarkdown/main/setup.sh)"
   ```

2. 其他方式

   > 1. 安装 git, python3.7+
   > 2. pip3 install markdown 或 pip install markdown
   > 3. git clone https://github.com/cristime/parsemarkdown.git
   > 4. cd parsemarkdown

#### 如何使用？

1. 
	```bash
	$ python3 parse.py "此 Markdown 文件的正常名（不包括扩展名）"
	```

2. 此时文件夹中会出现一个 *html* 文件，在浏览器中打开它
3. Enjoy it~

