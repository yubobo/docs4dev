## 53.当前跟踪组件

勇敢支持“当前跟踪组件”概念，只有在您拥有时才能使用没有其他方法可以获得参考.这是为JDBC连接而创建的，因为它们通常在跟踪组件之前初始化.

实例化的最新跟踪组件可通过 `Tracing.current()` 获得.您也可以使用 `Tracing.currentTracer()` 来获取跟踪器.如果您使用这些方法之一，请不要缓存结果.相反，每次需要时都要查找它们.