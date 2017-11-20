## get_adjacent_post()

### 描述

检索相邻的文章，可以是上一篇或下一篇。

### 使用

```php
get_adjacent_post( bool $in_same_term = false, array|string $excluded_terms = '', bool $previous = true, string $taxonomy = 'category' )
```

### 参数

* $in_same_term

    *`bool` （可选）* 检索的文章是否应在同一分类中。默认值：`false`

* $excluded_terms

    *`array|string` （可选）* 排除的分类ID，数组或以逗号分隔的字符串。默认值：`''`

* $previous

    *`bool` （可选）* 是否检索上一篇文章。默认值：`true`

* $taxonomy

    *`string` （可选）* 当 `$in_same_term` 为 `true` 时，指定分类名称。默认值：`'category'`

### 返回值

