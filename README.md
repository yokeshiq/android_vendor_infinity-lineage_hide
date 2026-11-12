# android_vendor_infinity-lineage_hide

移除编译配置中对 `ro.modversion` 系统属性的默认注入，消除构建指纹特征。

## 拉取部分代码（Cherry-Pick）

进入目标 ROM 源码的 `vendor/infinity` 目录执行：

```bash
cd vendor/infinity
git fetch [https://github.com/yokeshiq/android_vendor_infinity-lineage_hide.git](https://github.com/yokeshiq/android_vendor_infinity-lineage_hide.git) main
git cherry-pick acff0ee1
```

## 修改文件清单

- `config/version.mk`
