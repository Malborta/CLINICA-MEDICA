### Gestión del Entorno Virtual

Active el entorno virtual ejecutando:

```powershell
.venv\Scripts\Activate.ps1
```

*(Aparecerá el indicador `(.venv)` al inicio de la línea de comandos confirmando la activación exitosa).*

#### Instalar las dependencias del sistema

Actualice el gestor de paquetes e instale el archivo de requerimientos del sistema:

```powershell
python -m pip install --upgrade pip
pip install -r requirements.txt
```

#### Ejecución del Servidor de Desarrollo

Inicie la aplicación ejecutando el script principal:

```powershell
py run.py
```

El servidor se levantará localmente en el puerto **5005**. Abra su navegador web e ingrese a la siguiente dirección:  
[http://127.0.0.1:5005/login](http://127.0.0.1:5005/login)
