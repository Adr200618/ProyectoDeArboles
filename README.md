SISTEMA DE SUCESCION REAL
Un programa en C++ que gestiona y visualiza árboles genealógicos de familias reales, determinando automáticamente la línea de sucesión al trono según reglas específicas.

CARACTERISTICAS
*Gestión de árbol genealógico: Carga y almacena información familiar desde archivos CSV

*Determinación automática de sucesión: Encuentra el sucesor más adecuado al trono basándose en:

 -Primogenitura (hijos mayores primero)
 -Preferencia por varones
 -Edad (entre 15-70 años)
 -Proximidad al rey actual

*Visualización: Muestra el árbol familiar completo con información de estado

*Asignación automática de rey: Detecta cuando el rey actual no es válido y asigna uno nuevo

Estructura de Datos
El programa utiliza una estructura Persona que contiene:
 -Información personal (ID, nombre, apellido, género, edad)
 -Relaciones familiares (ID del padre, punteros a hijos)
 -Estado real (rey actual, ex-rey, fallecido)

EL ARCHIVO CSV CONTIENE LA SIGUIENTE INFORMARCION EN EL MISMO ORDEN:
id,name,last_name,gender,age,id_father,is_dead,was_king,is_king

USOS DEL PROGRAMA
El programa se ejecuta automáticamente y:
1. Crea un archivo CSV de ejemplo si no existe
2. Carga los datos familiares
3. Muestra el árbol genealógico completo
4. Analiza el estado actual del reY
5. Presenta la línea de sucesión
6. Asigna un nuevo rey si es necesario
