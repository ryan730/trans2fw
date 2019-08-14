### 使用pub global命令将文件包注册到全局
pub global activate trans2fw

### 使用pub global run命令运行注册的脚本文件 #
pub global run trans2fw

### 运行 `trans2fw` 工具,根据提示输入
```dart
$ trans2fw

[✓] 请输入需要转换的文件目录(相对于项目目录): lib-cp
[✓] 是否覆盖原有文件 ?  (y/N) y
{path: lib-cp, cover: true}
使用输入文件目录:lib-cp
被转换的文件::lib-cp/Pagination.dart::32
...
```
