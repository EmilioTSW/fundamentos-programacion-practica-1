# 📘 Fundamentos de Programación - Práctica 1

## 👨‍💻 Información del Estudiante

- **Nombre:** [Jorge Emilio Batun Alcocer]
- **Matrícula:** [SW2509055]
- **Grupo:** [B]
- **Cuatrimestre:** Primer Cuatrimestre
- **Carrera:** TSU en Desarrollo e Innovación de Software
- **Profesor:** Jorge Javier Pedrozo Romero

---

## 📋 Descripción del Proyecto

Este repositorio contiene mi solución a la práctica de **Fundamentos de Programación**, donde implemento funciones en JavaScript para resolver problemas de álgebra básica, preparándome para trabajar con operaciones matriciales más complejas.

## 🎯 Objetivos Alcanzados

- ✅ Dominar variables y tipos de datos en JavaScript
- ✅ Implementar estructuras condicionales
- ✅ Utilizar bucles y funciones
- ✅ Manipular arrays unidimensionales
- ✅ Trabajar con arrays bidimensionales (matrices)
- ✅ Aplicar control de versiones con Git y GitHub

---

## 📊 Progreso de Ejercicios

### Sección 1: Variables y Tipos de Datos (10 pts)
- [x] 1.1 Mi Información (2 pts) ✅
- [x] 1.2 Operaciones Básicas (3 pts) ✅
- [x] 1.3 Área de Rectángulo (2 pts) ✅
- [x] 1.4 Conversión Celsius a Fahrenheit (3 pts) ✅

**Puntos obtenidos: 10/10**

### Sección 2: Condicionales (15 pts)
- [x] 2.1 Par o Impar (3 pts) ✅
- [x] 2.2 Evaluar Nota (4 pts) ✅
- [x] 2.3 Mayor de Tres (4 pts) ✅
- [x] 2.4 Clasificar Edad (4 pts) ✅

**Puntos obtenidos: 15/15**

### Sección 3: Funciones y Bucles (20 pts)
- [x] 3.1 Factorial (5 pts) ✅
- [x] 3.2 Suma Hasta N (4 pts) ✅
- [x] 3.3 Tabla de Multiplicar (5 pts) ✅
- [x] 3.4 Números Pares (6 pts) ✅

**Puntos obtenidos: 20/20**

### Sección 4: Arrays (25 pts)
- [x] 4.1 Suma de Array (4 pts) ✅
- [x] 4.2 Promedio de Array (5 pts) ✅
- [x] 4.3 Encontrar Máximo (6 pts) ✅
- [x] 4.4 Filtrar Mayores (5 pts) ✅
- [x] 4.5 Invertir Array (5 pts) ✅

**Puntos obtenidos: 25/25**

### Sección 5: Arrays Bidimensionales - Matrices (30 pts)
- [x] 5.1 Crear Matriz (6 pts) ✅
- [x] 5.2 Suma de Matriz (6 pts) ✅
- [x] 5.3 Obtener Fila (5 pts) ✅
- [x] 5.4 Obtener Columna (7 pts) ✅
- [x] 5.5 Transponer Matriz (6 pts) ✅

**Puntos obtenidos: 30/30**

---

## 📈 Calificación Final

```
┌────────────────────────────────────────┐
│  REPORTE DE CALIFICACIÓN               │
├────────────────────────────────────────┤
│  Puntos obtenidos: 100/100             │
│  Porcentaje: 100%                      │
│  🎓 Calificación: A - Excelente        │
└────────────────────────────────────────┘
```

![Tests](https://github.com/EmilioTSW/fundamentos-programacion-practica-1/actions/workflows/test.yml/badge.svg)

---

## 🚀 Instalación y Uso

### Prerrequisitos
- Node.js (versión 14 o superior)
- Git

### Clonar el repositorio
```bash
git clone https://github.com/TU-USUARIO/fundamentos-programacion-practica-1.git
cd fundamentos-programacion-practica-1
```

### Instalar dependencias
```bash
npm install
```

### Ejecutar tests
```bash
npm test
```

### Ejecutar tests en modo watch
```bash
npm run test:watch
```

### Ver cobertura de código
```bash
npm run test:coverage
```

---

## 📁 Estructura del Proyecto

```
fundamentos-programacion-practica-1/
│
├── ejercicios.js           # ⭐ Archivo principal con mis soluciones
├── ejercicios.test.js      # Tests automatizados (no modificar)
├── package.json            # Configuración del proyecto
├── README.md               # Este archivo
├── GUIA_ESTUDIANTES.md     # Guía de referencia
├── GUIA_INSTRUCTOR.md      # Guía del profesor
│
└── .github/
    └── workflows/
        └── test.yml        # Configuración de GitHub Actions
```

---

## 💡 Aprendizajes Clave

### Lo que más me costó
**Ejercicio 4.2**(Promedio de un Array): Me tomó un poco entender cómo recorrer correctamente el arreglo para sumar todos los valores y luego dividir entre la cantidad de elementos. Al principio olvidé inicializar la variable de suma en 0.

**Ejercicio 2.4** (Clasificación de Edad): Me confundía con las condiciones if y else if, especialmente al definir los rangos de edades. Después logré estructurarlo mejor usando comparaciones encadenadas.

### Lo que más me gustó
- **Ejercicio 3.3**(Tabla de Multiplicar): Me pareció divertido generar la tabla con un bucle for, ya que se ve claramente cómo la programación puede automatizar cálculos repetitivos.

**Ejercicio 5.1** (Crear Matriz): Disfruté mucho al trabajar con arreglos bidimensionales y ver cómo se pueden construir estructuras organizadas como tablas o cuadrículas.

### Técnicas aplicadas
- Uso de `for` loops para iteraciones
- Operador módulo `%` para determinar paridad
- Arrays dinámicos con `.push()`
- Bucles anidados para matrices

---

## 🔧 Ejemplos de Código

### Función Favorita: suma y restas
```javascript
function operacionesBasicas(a, b) {
  
  
  const suma = a + b;
  const resta = a - b;
  const multiplicacion = a * b;
  const division = a / b;
  
  return { suma, resta, multiplicacion, division };
}
```

**Por qué me gusta:** Me gusta por que es una forma basica y sencilla de hacer sumas y restas 

---

## 📚 Recursos Utilizados

- [MDN Web Docs - JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript)
- [JavaScript.info](https://es.javascript.info/)
- [Stack Overflow](https://stackoverflow.com)
- Guía del estudiante incluida en el repositorio

---

## 🎯 Próximos Pasos

Este proyecto me prepara para:
- ✨ Operaciones matriciales avanzadas (multiplicación, determinantes)
- 🖼️ Desarrollo de editores de imágenes
- 🔐 Implementación de algoritmos de encriptación
- 📊 Creación de calculadoras científicas

---

## 📝 Historial de Commits

```bash
# Ver mi historial completo
git log --oneline --graph --decorate
```

**Commits destacados:**
- `feat: Completar Sección 1 - Variables y tipos de datos`
- `feat: Implementar ejercicios de condicionales`
- `feat: Resolver funciones y bucles`
- `feat: Completar manipulación de arrays`
- `feat: Finalizar arrays bidimensionales - matrices`
- `docs: Actualizar README con resultados finales`

---

## 🤝 Agradecimientos

- **Profesor Jorge Javier Pedrozo Romero** por la estructura del curso y la práctica
- **Compañeros del Grupo [A/B/C]** por el apoyo mutuo
- **Tecnológico de Software** por la formación integral

---

## 📧 Contacto

- **Email Institucional:** [jorge.batum@tecdesoftware.edu.mx]
- **GitHub:** [@TU-USUARIO](https://github.com/EmilioTSW)

---

## 📄 Licencia

Este proyecto es parte de las actividades académicas del **Tecnológico de Software** y está bajo la licencia MIT.

---

<div align="center">

**⭐ Si te gustó este proyecto, dale una estrella ⭐**


Hecho con 💙 por [Jorge Emilio Batun Alcocer ] - 2025

</div>
