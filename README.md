
### generar binario como variable de entorno
```batch
go install 
Git.exe
```


### obtener libreria actualizada de git
```batch
go get -d github.com/Morty-debug/librerias
```


### obtener binarios de la libreria en git y usarla como variable de entorno
```batch
go install github.com/Morty-debug/librerias
librerias.exe
```


### crear el proyecto desde cero
```batch
mkdir Git 
cd Git 
notepad main.go
go mod init github.com/Morty-debug/Git
go mod tidy
```
