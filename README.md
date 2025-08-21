## uvとは
pythonのパッケージ管理ツール。pipよりも高速。
[uv （pythonパッケージマネージャー）の使い方　簡易版](https://qiita.com/futakuchi0117/items/9ec8bd84797fed180647)
## uvのインストール
1. PowerShellでインストール
```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```
2. "C:\Users\<ユーザー名>\.local\bin"をpathに追加
1. もしくは、pipでも可
```bash
pip install uv
```
## uvコマンド
- プロジェクトの作成
```bash
uv init uv_project
```
- 仮想環境の作成
```bash
uv venv
```
- pythonを実行
```bash
uv run python main.py #pythonを実行
```

## gitにpush
```bash
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/shiba0627/uv_project.git
git push -u origin main
```