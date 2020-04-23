# Cómo generar un exe desde un script de python

### Script
Generaremos un script de python denominado *index.py* y comprobamos su correcto uso
```python
for x in range(0, 1000):
    print(x)
```

### Instalación
Desde la línea de comandos instalaremos *pyinstaller*, con el cual podremos generar nuestro *.exe*
```bash
pip install pypinstaller
```

### Compilación
Nuevamente desde la línea de comandos ejecutamos lo siguiente:
```bash
pyinstaller -c index.py
```
Nótese que se le agregó la opción *-c*, con la cual generará una consola como salida

