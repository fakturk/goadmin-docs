# 列的使用
---

**InfoPanel**内置了很多对于列的操作方法，可以通过这些方法很灵活的操作列数据。

### 设置列宽

```
info.AddField("Name", "name", db.Varchar).FieldWidth(100)
```

### 默认隐藏列

```
info.AddField("Name", "name", db.Varchar).FieldHide()
```

### 设置为可排序

```
info.AddField("Name", "name", db.Varchar).FieldSortable()
```

### 设置为固定

```
info.AddField("Name", "name", db.Varchar).FieldFixed()
```

### 设置为可过滤

```
info.AddField("Name", "name", db.Varchar).FieldFilterable()
```

## 帮助方法

### 字符串操作

限制输出长度

```
info.AddField("Name", "name", db.Varchar).FieldLimit(10)
```

首字母大写

```
info.AddField("Name", "name", db.Varchar).FieldToTitle()
```

去除空格

```
info.AddField("Name", "name", db.Varchar).FieldTrimSpace()
```

字符串截取

```
info.AddField("Name", "name", db.Varchar).FieldSubstr(0, 3)
```

字符串转大写

```
info.AddField("Name", "name", db.Varchar).FieldToUpper()
```

字符串转小写

```
info.AddField("Name", "name", db.Varchar).FieldToLower()
```