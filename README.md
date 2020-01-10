# magic
魔法函数
{
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## 魔法函数"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "在 Code Cell 里，可以运行一些 “魔法函数”（Magic Functions），这是秉承了 IPython 的特性。绝大多数在 IPython 里能够使用的魔法函数在 Jupyterlab 里都可以直接使用。完整的 IPython 魔法函数请参照：\n",
    "\n",
    "> https://ipython.readthedocs.io/en/stable/interactive/magics.html\n",
    "\n",
    "Jupyterlab 里较为常用的魔法函数整理如下：\n",
    "\n",
    "| 魔法函数             | 说明                                                         |\n",
    "| -------------------- | ------------------------------------------------------------ |\n",
    "| `%lsmagic`           | 列出所有可被使用的 Jupyter lab 魔法函数                      |\n",
    "| `%run`               | 在 Cell 中运行 `.py` 文件：`%run file_name`                  |\n",
    "| `%who`               | 列出所有当前 Global Scope 中的变量；类似的还有：`%who df`，`%whos` |\n",
    "| `%env`               | 列出当前的环境变量                                           |\n",
    "| `%load`              | 将其他文件内容导入 Cell，`%load source`，`source` 可以是文件名，也可以是 URL。|\n",
    "| `%time`              | 返回 Cell 内代码执行的时间，相关的还有 `%timeit`             |\n",
    "| `%writefile`         | 把 Cell 的内容写入文件，`%write file_name`；%write -a file_name，`-a` 是追加 |\n",
    "| `%matplotlib inline` | 行内展示 matplotlib 的结果                                   |\n",
    "| `%%bash`             | 运行随后的 shell 命令，比如 %%bash ls；与之类似的还有 `%%HTML`，`%%python2`，`%%python3`，`%%ruby`，`%%perl`……                      |"
   ]
  },
