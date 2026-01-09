# 5. Arquitectura Técnica

## 5.1 Diagrama del sistema

```mermaid
graph TB
    subgraph "Frontend"
        A[HTML/CSS] --> B[JavaScript]
        B --> C[React Components]
    end
    
    subgraph "Backend"
        D[Node.js Server] --> E[Express API]
        E --> F[Authentication]
    end
    
    subgraph "Base de Datos"
        G[(SQLite Database)]
    end
    
    subgraph "Infraestructura"
        H[GitHub Pages]
        I[Git Version Control]
    end
    
    C --> E
    E --> G
    F --> C
    H --> A
    I --> D
```

![Diagrama en imagen](https://i.redd.it/nzzpm5jv8l091.jpg)


## 5.2 Explicación técnica

### **Estructura de carpetas:**

```text
taskmaster-pro/
├── src/
│   ├── controllers/   # Lógica de endpoints
│   ├── models/        # Modelos de datos
│   ├── routes/        # Rutas API
│   ├── middleware/    # Middlewares
│   └── utils/         # Utilidades
├── public/            # Archivos estáticos
├── database/          # Configuración BD
└── tests/             # Pruebas unitarias
```

## 5.3 Tecnologías implementadas

### Dependencias principales:
- **express** – Framework backend
- **sqlite3** – Base de datos en desarrollo
- **jsonwebtoken** – Autenticación JWT
- **bcrypt** – Encriptación de contraseñas
- **react** – Librería frontend
- **react-dom** – Renderizado React
- **date-fns** – Gestión de fechas

### Dependencias de desarrollo
- **jest** – Testing
- **nodemon** – Recarga automática
- **eslint** – Linting de código
