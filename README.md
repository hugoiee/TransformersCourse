# TransformersCourse

## ✨项目使用说明
```shell
# 0.激活环境
source .venv/bin/activate

# 1.修改 requirements.in，加入 xxx(要安装的依赖包)

# 2.更新锁文件
uv pip compile requirements.in -o requirements.txt

# 3.更新环境
uv pip sync requirements.txt

# 4.离开项目
deactivate
```
