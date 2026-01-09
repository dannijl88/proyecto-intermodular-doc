# 4. Uso de la Aplicación

## 4.1 Capturas

### **Pantalla principal:**
![Dashboard TaskMaster](https://store-wp.mui.com/wp-content/uploads/2019/08/tabler-react.com_-min-e1565617941333.png)

*Interfaz principal con:*
1. **Lista de tareas** pendientes
2. **Filtros** por materia y prioridad
3. **Calendario** de entregas
4. **Contador** de tareas completadas

## 4.2 Casos de uso

### **Caso 1: Estudiante universitario**

**Usuario:** *Ana, 20 años, estudiante de Ingeniería*

```javascript
// Tareas típicas de Ana
const tareasAna = [
  {
    id: 1,
    titulo: "Proyecto Base de Datos",
    materia: "Bases de Datos II",
    prioridad: "alta",
    fecha: "2024-01-25",
    estado: "pendiente"
  },
  {
    id: 2, 
    titulo: "Estudiar para parcial",
    materia: "Cálculo",
    prioridad: "media",
    fecha: "2024-01-22",
    estado: "en-progreso"
  }
];
```
### **Caso 2: Grupo de trabajo

**Situación: 3 estudiantes trabajando en proyecto final

| Integrante | Tareas asignadas | Estado | Fecha límite |
|:-----------|:-----------------|:-------|:-------------|
| Carlos | Diseño BD | ✅ Completado | 2024-01-18 |
| María | Documentación | 🟡 En progreso | 2024-01-20 |
| Luis | Implementación | 🔴 Pendiente | 2024-01-22 |

## 4.3 Usuarios tipo
Tabla de tipos de usuarios:
| Tipo          | Características                               | Funcionalidades principales                          |
|---------------|-----------------------------------------------|------------------------------------------------------|
| Estudiante    | Usuario principal, necesita organización básica | Crear tareas, ver calendario, recibir recordatorios  |
| Profesor      | Crea tareas para grupos completos              | Compartir tareas, establecer fechas grupales         |
| Administrador | Gestiona usuarios y sistema                   | Borrar usuarios, ver estadísticas, backups           |
