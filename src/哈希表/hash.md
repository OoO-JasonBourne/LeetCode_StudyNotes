### 1. Map()
Map() 对象是一种键值对的集合，其中每个键唯一且与一个值关联。它类似于传统的对象，但提供更灵活的键类型和更方便的操作方法。键可以是任何数据类型（包括对象、函数、原始类型等），并且保留了插入顺序。可以使用 set(key, value) 方法添加键值对，使用 get(key) 方法获取值，还可以使用 has(key) 方法检查键是否存在。常用于需要快速查找和存储键值对的场景。

### 2. Set()
Set() 对象是一种存储唯一值的集合，其中每个值都是唯一的，不会重复。它类似于数组，但与数组不同的是，它只存储唯一的值。可以使用 add(value) 方法添加值，使用 has(value) 方法检查值是否存在，还可以使用 size 属性获取集合中的值的数量。常用于需要存储唯一值且不需要键值对关系的场景。

### 总结：

Map() 适用于需要存储键值对、需要根据键快速查找值的场景。 set(key, value) 方法添加键值对，使用 get(key) 方法获取值,使用 has(key)检查时候存在 \
Set() 适用于需要存储唯一值且不需要键值对关系的场景。 add(value) 方法添加值，使用 has(value) 方法检查值是否存在，还可以使用 size 属性获取集合中的值的数量。

