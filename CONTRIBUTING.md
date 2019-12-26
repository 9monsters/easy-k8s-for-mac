
## 维护

1. 修改目录 `collection` 下各`channel`对应`k8s`版本

2. 修改 `.github/workflows/$channel.yml`
```yaml
kubernetes_version: $version
```
