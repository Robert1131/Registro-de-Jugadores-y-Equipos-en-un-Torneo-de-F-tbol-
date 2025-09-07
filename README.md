# Registro de Jugadores y Equipos - Torneo de Fútbol

## Descripción
Esta aplicación permite registrar equipos y jugadores para un torneo de fútbol, utilizando **diccionarios (mapas)** y **conjuntos** como estructuras de datos principales.  
Permite realizar reportes, consultas de jugadores y medir el tiempo de ejecución de todas las operaciones.

---

## Funcionalidades
- Agregar equipos al torneo.  
- Agregar jugadores a cada equipo.  
- Visualizar todos los equipos y sus jugadores (**reportería**).  
- Consultar si un jugador pertenece a algún equipo.  
- Medición del tiempo total de ejecución del programa.

---

## Estructura de Datos
- **Diccionario (`dict`)**: Relaciona el nombre del equipo con un conjunto de jugadores.  
- **Conjunto (`set`)**: Asegura que no se registren jugadores duplicados dentro del mismo equipo.

**Ventajas:**
- Búsqueda y registro rápido de jugadores por equipo.  
- Evita duplicados de manera automática.  

**Desventajas:**
- No mantiene un orden específico de equipos o jugadores.  
- No es ideal para búsquedas complejas fuera de equipo/jugador.

---

## Uso de IA
- **Agente utilizado:** ChatGPT (GPT-5 mini)  
- **Porcentaje de código generado con IA:** 40%

---

## Datos de ejemplo incluidos
- **Equipos:** Barcelona, Real Madrid, Manchester United, Bayern Munich  
- **Jugadores:** Lionel Messi, Xavi Hernández, Andrés Iniesta, Karim Benzema, Luka Modric, Sergio Ramos, Cristiano Ronaldo, Paul Pogba, Bruno Fernandes, Robert Lewandowski, Thomas Müller, Manuel Neuer  

---

## Ejecución
1. Clonar o descargar el repositorio.  
2. Ejecutar el archivo `main.py` con Python 3:



