# Mi Primera API FastAPI

## ¿Qué hace?

Una API básica creada en el Bootcamp FastAPI Semana 1.

## ¿Cómo ejecutar?

```bash
pip install -r requirements.txt
uvicorn main:app --reload
```

# Mi Primera API FastAPI - Bootcamp

**👤 Desarrollador**: Miguel David Triviño López
**📧 Email**: 200131367+migueltrivino@users.noreply.github.com
**� Privacidad**: Email configurado según mejores prácticas de GitHub
**�📅 Fecha de creación**: 2025-08-14 15:19:20
**📂 Ruta del proyecto**: /c/Users/Aprendiz/desarrollo-personal/miguel-triviño-bootcamp/mi-primera-api-fastapi
**💻 Equipo de trabajo**: BOGDFPCGMP2255

## 🔧 Configuración Local

Este proyecto está configurado para trabajo en equipo compartido:

- **Entorno virtual aislado**: `venv-personal/`
- **Configuración Git local**: Solo para este proyecto
- **Dependencias independientes**: No afecta otras instalaciones

## 🚀 Instalación y Ejecución

```bash
# 1. Activar entorno virtual personal
source venv-personal/bin/activate

# 2. Instalar dependencias (si es necesario)
pip install -r requirements.txt

# 3. Ejecutar servidor de desarrollo
uvicorn main:app --reload --port 8000
```

## 📝 Notas del Desarrollador

- **Configuración Git**: Local únicamente, no afecta configuración global
- **Email de GitHub**: Configurado con email privado para proteger información personal
- **Entorno aislado**: Todas las dependencias en venv-personal/
- **Puerto por defecto**: 8000 (cambiar si hay conflictos)
- **Estado del bootcamp**: Semana 1 - Configuración inicial

## 🛠️ Troubleshooting Personal

- Si el entorno virtual no se activa: `rm -rf venv-personal && python3 -m venv venv-personal`
- Si hay conflictos de puerto: cambiar --port en uvicorn
- Si Git no funciona: verificar `git config user.name` y `git config user.email`
- Si necesitas cambiar el email: usar el email privado de GitHub desde Settings → Emails

## ¿Qué fue lo que mas te sorprende de crear tu primera API?

Lo que más me sorprendió al crear mi primera API fue la cantidad de comandos y pasos necesarios incluso para levantar una API básica en un servidor local. Me impresionó cómo, con solo unas pocas líneas de código y la configuración adecuada, es posible crear un servicio que responda a peticiones en tiempo real.


## ¿Qué aprendí?

Gracias a lo que hice hoy, aprendí conceptos básicos de FastAPI, los comandos necesarios para levantar un servidor local y, sobre todo, cómo crear un entorno virtual y configurar Git para trabajar en un equipo compartido de forma organizada.   

## ¿Los type hints hacen tu código más claro? ¿Por qué?

En mi opinion los type hints si hacen mas claro el codigo ya que brindan a la persona que lee este mismo una mayor claridad de que tipo de dato se espera que reciba y devuelva la función 

## ¿Cómo te ayuda Pydantic a crear APIs más robustas?

Esto me podria ayudar a crear APIs mas robostas porque, tener la posibilidad de validar los datos que llegan a mi API me ayuda en el momento que el usuario digite información incorrecta por ejemplo, que yo pida la edad y el usuario digite letras, lo que hace pydantic es decirte exactamente que esta mal 

## ¿Cómo mejoraron estos conceptos tu API comparada con Semana 1?

Mis conceptos mejoraron ya que en este momento se muchos mas conceptos acerca de fastAPI y reforce conocimientos anteriores, ademas esto se ve reflejado en el resultado final de esta API ya que cuenta con funciones mas utiles e interesantes para el usuario

# Mi API FastAPI - Semana 2

## ¿Qué hace?

API mejorada con validación automática de datos y type hints.

## Nuevos Features (Semana 2)

- Type hints en todas las funciones
- Validación automática con Pydantic
- Endpoint POST para crear datos
- Parámetros de ruta (ejemplo: /products/{id})
- Búsqueda con parámetros query

## ¿Cómo ejecutar?

```bash
pip install fastapi pydantic uvicorn
uvicorn main:app --reload
```

## [Escribe 2-3 oraciones sobre qué fue lo más útil de esta semana]

Lo que fue mas util en esta semana segun mi opinion fue entender, como se crean diccionarios con parametros ya establecidos para crear en el caso del ejercicio, diferentes productos como por ejemplo, name tipo string, price tipo int y tambien como con diferentes funciones podemos buscar el producto por su clave ya sea nombre o precio 