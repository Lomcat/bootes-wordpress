[WordPress 代码参考](../index.md) / [类](../Classes.md) / [WP_Post](../classes/WP_Post.md) / WP_Post::__construct()

## WP_Post::__construct

### 使用

```php
WP_Post::__construct( WP_Post|object $post )
```

### 描述

[WP_Post](../classes/WP_Post.md) 构造方法

### 参数

* $post：

    *`WP_Post | object` （必须）* 帖子对象

### 源码

文件：wp-includes/class-wp-post.php

```php
public function __construct( $post ) {
    foreach ( get_object_vars( $post ) as $key => $value )
        $this->$key = $value;
}
```