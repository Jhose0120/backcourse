# MariaDB

## Comandos ejecutables en consola
Ingreso a bd en consola
```
mariadb -u 'usuario' -p
```
--Crear usuario 

```
CREATE USER 'usuario'@'localhost' IDENTIFIED BY '123';
```
--Borrar usuario 
```
DROP USER 'retamaster'@'localhost'
```
--Documentación relacionada con los privigelios: https://mariadb.com/kb/en/grant/#grant-option
Asignación de todos los privilegios a usuario creado
```
GRANT ALL PRIVILEGES ON *.* TO 'usuario'@'localhost';
FLUSH PRIVILEGES;

mysql mariadb -u 'retamaster' -p <2_tablas.sql

```
--3 alter table

```
-- Agregar foreign key
alter table `trains` add constraint `fk_trains_line_id` foreign key (`line_id`) references `lines`(`id`);

--Borrar columna
ALTER TABLE asignaturas DROP COLUMN hora_de_salida;

--Agregar columna
ALTER TABLE asignaturas ADD COLUMN hora_de_entrega TIMESTAMP NOT NULL;

--Crear tabla
CREATE TABLE estudiantes(
  id INT NOT NULL,
  nombre VARCHAR(255),
  asignatura_id INT,
  PRIMARY KEY (id),
  CONSTRAINT fk_estudiantes_asignatura_id
  FOREIGN KEY (asignatura_id) REFERENCES asignaturas(id)
);
SELECT * FROM asignaturas;
SELECT * FROM estudiantes;

```
--4 INSERTAR LINEAS

```
INSERT INTO 'lines' (name, color) values
('Linea 1', 'rosa'),
('Linea 2', 'rosa'),
('Linea 3', 'rosa'),
('Linea 4', 'rosa'),
('Linea 5', 'rosa'),
('Linea 6', 'rosa'),
('Linea 7', 'rosa'),
('Linea 8', 'rosa'),
('Linea 9', 'rosa'),
('Linea A', 'rosa'),
('Linea B', 'rosa'),
('Linea 12', 'Oro');

```

```
