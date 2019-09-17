<a name="Log"></a>

## Log
日志类

**Kind**: global class  

* [Log](#Log)
    * [new Log(label)](#new_Log_new)
    * [.debug(message, [...args])](#Log+debug)
    * [.info(message, [...args])](#Log+info)
    * [.warn(message, [...args])](#Log+warn)
    * [.error(message, [...args])](#Log+error)
    * [.time(key, level)](#Log+time)
    * [.timeEnd(key, message, [...args])](#Log+timeEnd)

<a name="new_Log_new"></a>

### new Log(label)
初始化日志


| Param | Type | Description |
| --- | --- | --- |
| label | <code>string</code> | 日志前缀 |

<a name="Log+debug"></a>

### log.debug(message, [...args])
调试级别日志

**Kind**: instance method of [<code>Log</code>](#Log)  

| Param | Type | Description |
| --- | --- | --- |
| message | <code>string</code> | 日志内容 |
| [...args] | <code>any</code> | 内容参数 |

<a name="Log+info"></a>

### log.info(message, [...args])
信息级别日志

**Kind**: instance method of [<code>Log</code>](#Log)  

| Param | Type | Description |
| --- | --- | --- |
| message | <code>string</code> | 日志内容 |
| [...args] | <code>any</code> | 内容参数 |

<a name="Log+warn"></a>

### log.warn(message, [...args])
警告级别日志

**Kind**: instance method of [<code>Log</code>](#Log)  

| Param | Type | Description |
| --- | --- | --- |
| message | <code>string</code> | 日志内容 |
| [...args] | <code>any</code> | 内容参数 |

<a name="Log+error"></a>

### log.error(message, [...args])
错误级别日志

**Kind**: instance method of [<code>Log</code>](#Log)  

| Param | Type | Description |
| --- | --- | --- |
| message | <code>any</code> | 日志内容，可以为 Error 对象 |
| [...args] | <code>any</code> | 内容参数 |

<a name="Log+time"></a>

### log.time(key, level)
设置一个计时器

**Kind**: instance method of [<code>Log</code>](#Log)  

| Param | Type | Default | Description |
| --- | --- | --- | --- |
| key | <code>string</code> |  | 计时器标识 |
| level |  | <code>debug</code> | [string=debug] 日志级别，支持 debug、info、warn、error |

<a name="Log+timeEnd"></a>

### log.timeEnd(key, message, [...args])
结束计时并显示日志

**Kind**: instance method of [<code>Log</code>](#Log)  

| Param | Type | Description |
| --- | --- | --- |
| key | <code>string</code> | 计时器标识 |
| message | <code>string</code> | 日志内容 |
| [...args] | <code>any</code> | 内容参数 |

