# tranquil-cradle

Go · Terraform · Rust

留着备查的示例

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

## 为什么写

现有的工具都太重，就想要个能管道拼接的小东西。

## 安装

```bash
git clone https://github.com/USER/tranquil-cradle.git
cd tranquil-cradle
go build ./...
```

## License

MIT
