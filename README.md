### crear proyecto
```batch
mkdir invocar-go_ejemplo
cd invocar-go_ejemplo
notepad main.go
```

### inicializar proyecto
```batch
go mod init github.com/Morty-debug/invocar-go_ejemplo
go mod tidy
```

### actualizar proyecot
```batch
del /f go.mod
del /f go.sum
go mod init github.com/Morty-debug/invocar-go_ejemplo
go mod tidy
```

### interpretar codigo
```batch
go run main.go
```

### compilar codigo
```batch
go build main.go
```
