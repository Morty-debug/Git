
### crear el proyecto desde cero
```batch
mkdir Go_Git 
cd Go_Git 
notepad main.go
go mod init github.com/Morty-debug/Go_Git
go mod tidy
```


### obtener libreria actualizada
```batch
del /f go.mod
del /f go.sum
go mod init github.com/Morty-debug/Go_Git
go mod tidy
go run main.go
```
