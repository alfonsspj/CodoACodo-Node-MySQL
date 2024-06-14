## Sentencias en MySQL


1. crear una base de datos "usuarios_bd"
```sql
CREATE DATABASE usuarios_bd;   
```

2. crear bd si no existe - forma de asegurarse que no estamos pisando una bd creada 
```sql
CREATE DATABASE IF NOT EXISTS usuarios_db;   
```

3. Indicar que bd vamos a usar
```sql
USE usuarios_bd;   
```

4. Borrar una bd
```sql
DROP DATABASE pruebaborrar;   
```

5. Agregar entidades - tabla
```sql
CREATE TABLE IF NOT EXISTS usuarios (
	id INT AUTO_INCREMENT PRIMARY KEY,
    nombre VARCHAR(100) NOT NULL,
    apellido VARCHAR(100) NOT NULL,
    mail VARCHAR(100) NOT NULL
);
```

6. Insertar datos en la bd
```sql
   INSERT INTO usuarios (nombre,apellido,mail) VALUES
   ('Juan','Perez','juan@gmail.com'),
   ('Pedro','Paredes','pedro@gmail.com'),
   ('Rocio','Caceres','rocio@gmail.com'),
   ('Daniela','Aramayo','daniela@gmail.com');
```

7. Mostrar tabla
```sql
   SELECT * FROM usuarios;
```



```sql
   
```