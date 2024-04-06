# Project Learning GO MVC

### Tips

**Install and Configure CompileDaemon - use for hot reload after save**

**Paste**

```
in nano ~/.bashrc
export PATH=$PATH:$(go env GOPATH)/bin
```

**After install Compile Deamon**

```
go install github.com/githubnemo/CompileDaemon@latest
```

**Run in path base**

```
CompileDaemon --command="./mvcgo"
```
