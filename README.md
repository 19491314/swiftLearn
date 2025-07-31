# swiftLearn
# Swift 语言学习示例

这个项目包含了几个Swift语言学习示例，帮助你快速掌握Swift的核心概念。

## 文件说明

### 1. SwiftBasics.swift
基础语法学习示例，包含：
- 变量和常量声明
- 数组和字典使用
- 可选类型处理
- 函数定义和调用
- 闭包语法
- 类和结构体
- 枚举定义
- 协议使用

### 2. SimpleCalculator.swift
实用项目示例，包含：
- 类的完整实现
- 枚举的高级用法
- 错误处理机制
- 扩展功能
- 私有属性和方法
- 计算属性

## 如何运行

### 方法1：使用命令行
```bash
# 运行基础示例
swift SwiftBasics.swift

# 运行计算器示例
swift SimpleCalculator.swift
```

### 方法2：使用Xcode
1. 打开Xcode
2. 创建新的Playground
3. 将代码复制到Playground中运行

### 方法3：使用Swift REPL
```bash
# 启动Swift REPL
swift

# 在REPL中粘贴代码运行
```

## 学习要点

### 基础概念
- **变量 vs 常量**: `var` 用于变量，`let` 用于常量
- **类型推断**: Swift可以自动推断类型
- **可选类型**: 使用 `?` 表示可能为nil的值
- **字符串插值**: 使用 `\(变量)` 在字符串中插入值

### 高级特性
- **闭包**: 匿名函数，可以捕获外部变量
- **协议**: 定义接口，支持协议扩展
- **错误处理**: 使用 `do-catch` 处理错误
- **扩展**: 为现有类型添加新功能

### 最佳实践
- 使用 `guard` 进行早期返回
- 优先使用结构体而非类（除非需要引用语义）
- 合理使用可选类型，避免强制解包
- 使用 `enum` 定义相关常量

## 下一步学习

1. **iOS开发**: 学习UIKit或SwiftUI
2. **网络编程**: 使用URLSession进行网络请求
3. **数据持久化**: Core Data或UserDefaults
4. **并发编程**: GCD和async/await
5. **测试**: 学习单元测试和UI测试

## 资源推荐

- [Swift官方文档](https://docs.swift.org/swift-book/)
- [Swift编程语言指南](https://swift.org/documentation/)
- [iOS开发者文档](https://developer.apple.com/ios/)

祝你学习愉快！🎉 
