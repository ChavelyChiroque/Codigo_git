# Primer día con Git y Github
Lista de comandos de GIT

* Para poder ver la versión de GIT ejecutamos en la terminal:

```bash
git --version
git -v
```
* Para configurar Comandos de GIT (correo y nombre) solo la primera vez en la MÁQUINA
```bash
git config --global user.email "micorreo@gmail.com"
git config --global user.name "Mi nombre"
```

* Para ver la configuración del GIT
```bash
git config --list
```

* Para inicializar repositorio en git:
```bash
git init
```

* Para ver el estado de nuestros cambios
```bash
git status
```

* Para preparar nuestros archivos para stage (para commit)
```bash
git add .
git add nombreDelArchivo.xy
```

* Para crear registro de los cambios realizados:
```bash
git commit -m "comentario corto y conciso".
```

* Para ver una lnea de tiempo de los commits que hemos realizado
```bash
git log
```
