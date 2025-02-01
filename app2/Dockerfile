# Dockerfile para app1 y app2

# Usamos una imagen base de Python
FROM python:3.9

# Establecemos el directorio de trabajo dentro del contenedor
WORKDIR /app

# Copiamos los archivos de la aplicación
COPY requirements.txt requirements.txt
COPY . .

# Instalamos las dependencias
RUN pip install --no-cache-dir -r requirements.txt

# Exponemos el puerto 5000
EXPOSE 5000

# Comando para ejecutar la aplicación
CMD ["python", "app.py"]