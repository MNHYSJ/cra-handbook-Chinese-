终端虚拟环境：
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
.\.venv\Scripts\activate

运行：
mkdocs serve


更新：
git add .
git commit -m "update something"
git push
mkdocs gh-deploy
