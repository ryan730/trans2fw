### trans2fw 是一个快速将 `flutter native`  开发的文件转换成 `flutter-web` 的工具。
> 目前工具只对【官方常用的代码库】转换成web版本，后续会增加更多第三方库的支持。
> 包括但不限于如下:
```dart
package:flutter/material.dart -> package:flutter_web/material.dart
package:flutter/widgets.dart -> package:flutter_web/widgets.dart
package:flutter/cupertino.dart -> package:flutter_web/cupertino.dart
package:flutter/services.dart -> package:flutter_web/services.dart
package:flutter/rendering.dart -> package:flutter_web/rendering.dart
dart:ui -> package:flutter_web_ui/ui.dart
```


### 使用前准备
- [请了解 `Flutter-web` 官方说明](https://github.com/flutter/flutter_web/blob/master/README.md)
- [请了解 `Flutter-web` 的迁移指南](https://github.com/flutter/flutter_web/blob/master/docs/migration_guide.md)

### 使用pub global命令将文件包注册到全局
```dart
pub global activate trans2fw
```

### 使用pub global run命令运行注册的脚本文件 
```dart
pub global run trans2fw
```

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
