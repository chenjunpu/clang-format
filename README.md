# clang-format
.clang-format文件，Xcode自定义代码格式化样式文件。

[ClangFormat-Xcode](https://github.com/travisjeffery/ClangFormat-Xcode)

[XcodeClangFormat](https://github.com/mapbox/XcodeClangFormat)

```
# 基础格式
BasedOnStyle: Google

# 缩进宽度
IndentWidth: 2

# 圆括号的换行方式
BreakBeforeBraces: Attach

# 支持一行的 if
AllowShortIfStatementsOnASingleLine: false

# 支持一行的循环语句
AllowShortLoopsOnASingleLine: false

# switch 的 case 缩进
IndentCaseLabels: true

# 针对 OC 的 block 中的缩进宽度
ObjCBlockIndentWidth: 2

# 针对 OC，属性名后加空格
ObjCSpaceAfterProperty: true

# 协议列表后是否有空格
ObjCSpaceBeforeProtocolList: true

# 每行字符的长度
ColumnLimit: 100

# 指针符号对其方式
PointerAlignment: Right

# 注释对齐
AlignTrailingComments: true

# 注释在方法后时空格
SpacesBeforeTrailingComments: 1

# 括号后加空格
SpaceAfterCStyleCast: false

# 容器中插入空格
SpacesInContainerLiterals: false

# 不在小括号里加空格
SpacesInParentheses: false

# 不在中括号里加空格
SpacesInSquareBrackets: false

# 在构造函数初始化时按逗号断行，并以冒号对齐
BreakConstructorInitializersBeforeComma: true

# 赋值运算符前加空格
SpaceBeforeAssignmentOperators: true

# 连续的空行保留几行
MaxEmptyLinesToKeep: 1

# 头文件是否按首字母排序
SortIncludes: false
```
