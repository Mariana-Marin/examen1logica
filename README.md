# 💻 Proyecto Java: Simulación de Liquidación para Programador Freelance

Este proyecto simula el cálculo de la tarifa por hora de un programador, junto con sus pagos por cliente, bonificaciones, descuentos e impuestos. Es parte de una evaluación de lógica de programación 📚.

---

## 🚀 Funcionalidades principales

- Entrada de datos por teclado con `Scanner`.
- Cálculo dinámico de la tarifa por hora.
- Registro de proyectos y bonos por cliente.
- Cálculo de descuentos e impuestos.
- Impresión de un reporte final de liquidación 🧾.

---

## 🐞 Errores corregidos

| Tipo | Descripción | Solución aplicada ✅ |
|------|-------------|----------------------|
| ❌ Sintaxis | `scanner(system)` | Se cambió por `new Scanner(System.in)` |
| ❌ Importación | Faltaban `Scanner` y `LocalDate` | Se añadieron con `import` |
| ❌ Punto y coma | Líneas como `System.out.print(...)` sin `;` | Se corrigió añadiendo punto y coma |
| ❌ Tipos inválidos | `tarifaBase = 50,0,0` | Reemplazado por `50.0` |
| ❌ Variables inexistentes | `scanner.nextLine()`, `leer.nextLine()` | Se reemplazaron por `sc.nextLine()` |
| ❌ Lectura incorrecta | `nex()` no existe | Cambiado a `nextLine()` o `next()` según el caso |
| ❌ Lógica rota | Variables mal nombradas como `bonusCliene1` o `tarifaHoraFnal` | Se renombraron correctamente |
| ❌ Cálculo mal escrito | `subtotal ==== ...` | Cambiado a `subtotal = ...` |
| ❌ Lectura de enteros y strings seguidos | No se limpiaba buffer | Se usó `sc.nextLine()` después de `nextInt()` |

---

# 🧠 Conocimientos Aplicados

Este proyecto fue desarrollado aplicando los siguientes conceptos fundamentales de programación en Java:

- ✅ **Uso de condicionales** (`if`, `else`)
- 🔁 **Uso de ciclos** (`for`, `while`)
- ⌨️ **Entrada y salida de datos** con `Scanner`
- 🧮 **Variables y tipos de datos**
- 🔣 **Lógica booleana**

---

## ✨ Autor

👩‍🎓 **Mariana Marín Vanegas**  
📍 Colombia  
✉️ marianamarinvanegas2014@gmail.com 

---

## 🤖 Ayuda utilizada

- [ChatGPT de OpenAI](https://openai.com/chatgpt) – para generación de documentación y asistencia en corrección de código.
- [Java API Documentation](https://docs.oracle.com/en/java/javase/17/docs/api/index.html)
- Documentación oficial de `Scanner`.

> 💡 *Este proyecto fue creado como parte del curso de Lógica de Programación, integrando teoría y práctica para resolver problemas reales con Java.*

