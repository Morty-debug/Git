
### generar binario como variable de entorno
```batch
go install 
Go_Git.exe
```


### obtener libreria actualizada de git
```batch
go get -d github.com/Morty-debug/librerias
```


### obtener binarios de la libreria actualizada de git y usarla como variable de entorno
```batch
go install github.com/Morty-debug/librerias
librerias.exe
```


### crear el proyecto desde cero
```batch
mkdir Go_Git 
cd Go_Git 
notepad main.go
go mod init github.com/Morty-debug/Go_Git
go mod tidy
```
