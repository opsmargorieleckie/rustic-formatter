# rustic-formatter

Terraform · GraphQL

给自己省点事的小工具

## 用法

```bash
cat data.txt | go run main.go
```

输出：

```
   3  error: timeout
   1  warn: retry
---
2 unique / 4 lines
```

## 安装

```bash
git clone https://github.com/USER/rustic-formatter.git
cd rustic-formatter
go build ./...
```

## 备注

就是给自己省点事，没做太多抽象。

## 为什么写

现有的工具都太重，就想要个能管道拼接的小东西。

## License

MIT
