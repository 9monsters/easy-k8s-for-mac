# easy-k8s-for-mac 
 ![](https://img.shields.io/badge/NineSwordsMonster-easy--k8s--for--mac-66CCFF)
 
![GitHub](https://img.shields.io/github/license/NineSwordsMonster/easy-k8s-for-mac)

![GitHub last commit](https://img.shields.io/github/last-commit/NineSwordsMonster/easy-k8s-for-mac)
![GitHub issues](https://img.shields.io/github/issues/NineSwordsMonster/easy-k8s-for-mac)
![GitHub pull requests](https://img.shields.io/github/issues-pr/NineSwordsMonster/easy-k8s-for-mac)

![workflows stable](https://github.com/NineSwordsMonster/easy-k8s-for-mac/workflows/k8s%20image%20sync%20stable/badge.svg)
![workflows edge](https://github.com/NineSwordsMonster/easy-k8s-for-mac/workflows/k8s%20image%20sync%20edge/badge.svg)
![workflows latest](https://github.com/NineSwordsMonster/easy-k8s-for-mac/workflows/k8s%20image%20sync%20latest/badge.svg)


因某些因素，国内开启k8s 时镜像时有无法下载的情况。因此本仓库会同步各`channel` `k8s` 版本，以开启 k8s预下载镜像

## 使用方法
```sh
git clone 
cd easy-k8s-for-mac
sh load_image.sh
```

## 维护

1. 修改目录 `collection` 下各`channel`对应`k8s`版本

2. 修改 `.github/workflows/$channel.yml`
```yaml
kubernetes_version: $version
```
