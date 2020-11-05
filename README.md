# 实习日志生成器
## 安装以下依赖
```
pip install python-docx
```

## 如何使用
1. 安装上面的依赖。
2. 编辑 `config.json`，添加你所看的论文，做过的实验，并选择是否包含吴恩达的课程。
3. 运行脚本：`python main.py`
4. 生成的文件在 generated 目录下。


## 打包
```bash
pyinstaller --hiddenimport win32timezone -F main.py
```

## 注意
1. 仅供用于完成重复性内容的书写，其余部分请自行补全，请认真对待实习日志！
2. 由因使用本生成器所导致的任何后果均由使用者本人承担。