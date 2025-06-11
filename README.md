# Calculadora de Funciones con Series de Maclaurin

Este proyecto es una calculadora educativa hecha en Python que permite aproximar funciones matemáticas comunes utilizando **series de Maclaurin**. Fue desarrollado como parte del curso de **Programación Orientada a Objetos** 

📚 Funciones implementadas

- `e^x` — exponencial
- `sin(x)` — seno
- `cos(x)` — coseno
- `arcsen(x)` — arco seno
- `arccos(x)` — arco coseno
- `senh(x)` — seno hiperbólico
- `cosh(x)` — coseno hiperbólico

## 🔧 Tecnologías

- Lenguaje: Python 3
- Arquitectura: Modelo-Vista-Controlador (MVC)
- Interfaz: Terminal

## 🚫 Restricciones

No se utilizaron funciones nativas como `math.exp`, `math.sin`, etc. Todos los cálculos fueron realizados de forma manual utilizando estructuras básicas de control y funciones definidas por el usuario.

## 🧠 Estructura del proyecto

```
taylor_project/
│
├── model/
│   └── taylor_model.py        # Cálculo de series
│
├── view/
│   └── terminal_view.py       # Interfaz de terminal
│
├── controller/
│   └── main_controller.py     # Conexión entre modelo y vista
│
├── docs/
│   └── informe.txt            # Informe del proyecto
│
├── main.py                    # Punto de entrada de la aplicación
└── README.md                  # Este archivo
```

## ▶️ Cómo ejecutar

1. Clona el repositorio o descomprime el `.zip`.
2. Abre una terminal y navega al proyecto.
3. Ejecuta el siguiente comando:

```
python main.py
```

## 🧑‍🎓 Autor

JUAN MANUEL SANABRIA PORTILLO
