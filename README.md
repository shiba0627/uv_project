## uvのインストール
```
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
"C:\Users\<ユーザー名>\.local\bin"をpathに追加
```

## uvでプロジェクトを作成
```
uv init uv_project
cd uv_project
code .
uv venv
uv run python main.py
```

## gitにpush
```
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/shiba0627/uv_project.git
git push -u origin main
```