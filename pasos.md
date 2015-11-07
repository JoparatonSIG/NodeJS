Para instalar NVM (Node Version Manager):
==

```
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.29.0/install.sh | bash
```

Reiniciar la terminal porfis!

Listar y seleccionar la version de Node que queremos instalar:
==

```
nvm ls-remote # para listar las versiones disponibles remotamente
```

```
nvm ls # para listar las versiones disponibles localmente
```

Para instalar Node v4.2.2

```
nvm install v4.2.2
```

```
nvm alias default v4.2.2 # para seleccionar esta version por defecto
```

Cosas de Git(hub)
==

Para generar la clave SSH:
```
ssh-keygen # y Enter, enter, enter, hasta el final
```

Para copiar la clave:
```
cat ~/.ssh/*.pub # para copiar la clave al portapapeles
```

Cargar la clave a Github:

https://github.com/settings/ssh

Y ya está :')
