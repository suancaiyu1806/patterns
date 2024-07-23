# JavaScript Design Patterns

## # Command Pattern

> 命令模式是一种行为设计模式，它以命令的形式将任务的执行方与调用方解耦。

### 1. 应用场景

- 对任务进行排队、调度或远程执行
- 实现可逆操作

### 2. 优缺点

#### 优点

- `单一职责原则`：将任务执行方与调用方解耦
- `开闭原则`：增加新命令时，只需要新增命令类，无需修改调用方代码
- 调度任务的执行时机：延迟执行、异步执行、优先级控制、undo/redo等
- 组合：可以将一组简单的命令组合成一个复杂的命令

#### 缺点

- 执行方与调用方之间新引入了命令层，增加了系统复杂度
- 使用场景比较有限

### 3. 与其他设计模式的关系

- 执行方与调用方连接方式



---

*本文参考整理自 [patterns/vanilla/command-pattern](https://www.patterns.dev/vanilla/command-pattern) 及 [design-patterns/command](https://refactoringguru.cn/design-patterns/command)。*
