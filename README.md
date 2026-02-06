# ZIMO Docs – Quick Start

## Clone repo
```bash
git clone https://github.com/zimo-subsea/zimo-docs.git
cd zimo-docs
```

## Create & activate venv (Windows)
```
python -m venv .venv
.venv\Scripts\Activate.ps1
```
## Install dependencies
```
pip install -r requirements.txt
```
## Run locally
```
mkdocs serve
```
Open: http://127.0.0.1:8000

## Edit docs
Edit files in /docs

Config lives in mkdocs.yml

## Commit & push
```
git add .
git commit -m "docs: update"
git push
```
Deploy site
```
mkdocs gh-deploy
```
