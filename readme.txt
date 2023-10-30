開発向け

rootディレクトリ直下で実装

```
pip install --no-cache-dir --upgrade -r /code/requirements.txt

uvicorn app.main:app --host 0.0.0.0 --port 8081 --reload
```

