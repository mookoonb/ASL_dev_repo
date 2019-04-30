# cocopods 升级命令大全



```
 依赖私有库验证
 
 --sources=http://192.168.127.69/YY/DTSpecs.git,https://github.com/CocoaPods/Specs.git
```

```
忽略所有warning

--allow-warnings

```

```
上传命令

pod repo push DTSpecs XXXXXXXX.podspecs

```


```
验证命令

pod lib lint 

```

```
清除缓存

--no-clean
```

```
命令组合

- pod lib lint --no-clean

- pod lib lint --no-clean --allow-warnings

- pod repo push DTSpecs XXXXXXXX.podspecs --allow-warnings --sources=http://192.168.127.69/YY/DTSpecs.git,https://github.com/CocoaPods/Specs.git 

- pod lib lint --no-clean --allow-warnings 
```

```
忽略所有warning

--allow-warnings

```

```
上传命令

pod repo push DTSpecs XXXXXXXX.podspecs

```


```
验证命令

pod lib lint 

```

```
清除缓存

--no-clean
```

```
命令组合

- pod lib lint --no-clean

- pod lib lint --no-clean --allow-warnings

- pod repo push DTSpecs XXXXXXXX.podspecs --allow-warnings --sources=http://192.168.127.69/YY/DTSpecs.git,https://github.com/CocoaPods/Specs.git 

- pod lib lint --no-clean --allow-warnings --sources=http://192.168.127.69/YY/DTSpecs.git,https://github.com/CocoaPods/Specs.git




```