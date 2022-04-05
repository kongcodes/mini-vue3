# mini-vue3

本项目采用 TDD 驱动测试的开发方式，抽离出了 **vue3** 的核心逻辑，完成了一个最小 **vue3** 模型的实现。

## 使用了哪些技术栈

:rocket: Jest

:rocket: TypeScript

:rocket: rollup

## 实现了什么功能

### reactivity

:white_check_mark: reactive 的实现

:white_check_mark: ref 的实现

:white_check_mark: readonly 的实现

:white_check_mark: effect 的实现

:white_check_mark: track 依赖收集

:white_check_mark: trigger 触发依赖

:white_check_mark: 支持 effect.scheduler

:white_check_mark: 支持 effect.stop

:white_check_mark: 支持 isReactive

:white_check_mark: 支持嵌套 reactive

:white_check_mark: 支持 isProxy

:white_check_mark: 支持 isReadonly

:white_check_mark: 支持 shallowReadonly

:white_check_mark: 支持 isRef

:white_check_mark: 支持 unRef

:white_check_mark: 支持 proxyRefs

:white_check_mark: computed 的实现

### runtime-core 初始化

:white_large_square: 支持组件类型

:white_large_square: 支持 element 类型

:white_large_square: 初始化 props

### compiler-core

:white_large_square: 解析插值

:white_large_square: 解析 element

:white_large_square: 解析 text
