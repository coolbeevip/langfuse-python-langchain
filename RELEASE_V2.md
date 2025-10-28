# Langfuse V2 支持 Langchain V1

基于 Langfuse [v2.60.10](https://github.com/langfuse/langfuse-python/tree/v2.60.10)
参考 Langfuse PR [feat(langchain): add v1 support](https://github.com/langfuse/langfuse-python/pull/1411)

## 依赖要求
- python >= 3.11

```shell
poetry lock 
poetry install --all-extras
```

```shell
poetry build
twine upload --repository-url https://nexus.example.com/repository/pypi-hosted/ dist/*
```