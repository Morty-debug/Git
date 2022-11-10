
### generar binario como variable de entorno
```batch
go install 
Git.exe
```


### obtener libreria actualizada de git
```batch
go get -d github.com/RicardoValladares/Golang/08-librerias
go get github.com/RicardoValladares/Golang/08-librerias@latest
```


### obtener binarios de la libreria en git y usarla como variable de entorno
```batch
go install github.com/RicardoValladares/Golang/08-librerias
go install github.com/RicardoValladares/Golang/08-librerias@latest
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
