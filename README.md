### crear proyecto
```batch
mkdir libreria-go
cd libreria-go
notepad main.go
```

### inicializar proyecto
```batch
go mod init github.com/Morty-debug/libreria-go
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

### actualizar libreria que esta en internet
```batch
del /f go.mod
del /f go.sum
go mod init github.com/Morty-debug/libreria-go
go mod tidy
go build main.go
```
