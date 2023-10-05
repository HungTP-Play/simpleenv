## simpleenv


**Validate** and **Reflect** Golang Environment

### What I want?

```go
type Env struct {
  ENV_1     string   `env:string`
  ENV_URL   string   `env:url`
  ENV_NAME  string   `env:string,name=OTHER_NAME`
  ENV_NUMBER int     `env:int`
  ENV_BOOLWAN bool   `env:bool`  
}
```

---
## Reference

- https://francoisbest.com/posts/2023/dotenv-is-dead
- https://gist.github.com/sosedoff/b373623a9572cf1a992486d2d87dcd85
