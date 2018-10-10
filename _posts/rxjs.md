
## 基本概念
* Observable(可观察对象)：表示一个概念，这个概念是一个可调用的未来值或者事件的集合
* Observer(观察者)：一个回调函数的集合，监听由Observable 提供的值
* Subscription(订阅)：表示 Observable 的执行，主要用于取消 Observable的执行
* Operators(操作符)：
* Subject
* Schedulers

## Observable
* 创建
* 订阅
* 执行
* 清理

## 创建操作符
* 单值： of, empty, never
* 多值： from
* 定时： interval, timer
* 事件： fromEvent
* Promise: fromPromise
* 自定义： create

## 转换操作符
* 改变数据形态： map, mapTo, pluck
* 过滤：filter, skip, first, last, take
* 时间轴 delay, timeout, throttle, debounce, audit, bufferTime
* 累加： reduce, scan
* 异常处理： throw, catch, retry, finally
* 条件执行： takeUntil, delayWhen, retryWhen, subcribeOn, ObserveOn
* 转换： switch

## 组合
* concat
* merge
* race
* forkJoin
* zip
* combineLatest
