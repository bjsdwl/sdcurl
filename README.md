# sdcurl

# 1. 官方说明
```shell
https://curl.se/docs/install.html
```

# 2. 使用vcpkg安装
```shell
git clone https://github.com/Microsoft/vcpkg.git
cd vcpkg
./bootstrap-vcpkg.sh
```

# 3. 编译方式
## 3.1 动态库
```shell
./vcpkg install curl[tool]
```
## 3.2 静态库
```shell
./vcpkg install curl[tool]:x64-windows-static
```

最终生成的文件位置在vcpkg\installed\


