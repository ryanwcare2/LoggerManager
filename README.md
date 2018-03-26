# LoggerManager
A simple Swift logger to provide timestamp, filename, line number, and function context when logging.

Example:

```
func someMethod() {
    loggerManager.info("begin")
    loggerManager.error("some error message")
    loggerManager.info("end")
}
````

Log output:

```
info  : 2018-03-25 12:29:40.7290 : ViewModel.swift:56:someMethod() : begin
error : 2018-03-25 12:29:40.7291 : ViewModel.swift:57:someMethod() : some error message
info  : 2018-03-25 12:29:40.7292 : ViewModel.swift:58:someMethod() : end
```
