# Facultad de Ingeniería en Sistemas

**Asignatura:** Paradigmas de la Programación
**Docente:** Ingeniero Ricardo Toro
**Laboratorio:** Introducción a la Programación Orientada a Objetos en Smalltalk

---

## Contexto de la Asignación

Has sido contratado como **desarrollador Junior** en una empresa bancaria llamada **Banco NovaTech**, la cual desea modernizar parte de sus sistemas internos utilizando programación orientada a objetos.

Tu jefe inmediato, el líder del equipo de desarrollo, te ha asignado la siguiente tarea inicial como parte de tu proceso de capacitación dentro de la empresa:

> *"Necesitamos una pequeña prueba funcional para validar que comprendes los principios básicos de la Programación Orientada a Objetos. Para ello, deberás desarrollar una clase llamada **Cliente**, que represente a un cliente de nuestro sistema bancario.*
>
> *La clase deberá permitir realizar operaciones básicas sobre una cuenta bancaria, tales como depósitos, retiros y consultas de saldo.*
>
> *El objetivo no es construir un sistema completo, sino demostrar buenas bases en el diseño de clases, atributos y métodos utilizando Smalltalk en el entorno Pharo."*

---

## Objetivo del Laboratorio

Aplicar los fundamentos de la **Programación Orientada a Objetos** mediante el desarrollo de una clase básica en el lenguaje **Smalltalk** utilizando el IDE **Pharo**.

Con este laboratorio se busca reforzar los siguientes conceptos:

- Creación de clases
- Definición de atributos
- Creación de métodos
- Envío de mensajes
- Manipulación de objetos
- Encapsulamiento básico

---

## Requerimientos del Laboratorio

### 1. Crear la clase `Cliente`

La clase debe representar un cliente bancario y contener al menos los siguientes atributos:

| Atributo       | Descripción                        |
|----------------|------------------------------------|
| `nombre`       | Nombre del cliente                 |
| `numeroCuenta` | Número de cuenta bancaria          |
| `saldo`        | Saldo disponible en la cuenta      |

---

### 2. Implementar los siguientes métodos

#### Método `depositar`

Debe permitir agregar dinero al saldo del cliente.

**Ejemplo esperado:**

| Estado         | Valor  |
|----------------|--------|
| Saldo inicial  | 1000   |
| Depósito       | 500    |
| Nuevo saldo    | 1500   |

---

#### Método `retirar`

Debe permitir retirar dinero de la cuenta.

**Condiciones:**
- No debe permitir retirar más dinero del saldo disponible
- Debe mostrar un mensaje si los fondos son insuficientes

**Ejemplo esperado:**

| Estado         | Valor  |
|----------------|--------|
| Saldo inicial  | 1000   |
| Retiro         | 300    |
| Nuevo saldo    | 700    |

---

#### Método `consultarSaldo`

Debe mostrar o retornar el saldo actual del cliente.

---

## Requisitos Técnicos

El laboratorio debe desarrollarse utilizando:

- **Lenguaje:** Smalltalk
- **IDE / Entorno:** Pharo

---

## Actividades Esperadas

El estudiante deberá:

1. Crear correctamente la clase `Cliente`
2. Definir sus atributos
3. Implementar los métodos solicitados
4. Crear uno o más objetos de prueba
5. Ejecutar ejemplos de:
   - Depósitos
   - Retiros
   - Consultas de saldo
6. Mostrar evidencias de funcionamiento

---

## Documento PDF de Entrega

Cada estudiante deberá entregar un **documento PDF** explicando el trabajo realizado.

El documento debe incluir:

### Portada
- Nombre de la universidad
- Nombre de la asignatura
- Nombre del estudiante
- Fecha de entrega
- Nombre del laboratorio

### Introducción
Breve explicación sobre la Programación Orientada a Objetos y el propósito del ejercicio.

### Desarrollo

**Clase creada**
- Nombre de la clase
- Propósito de la clase

**Atributos**
Descripción de cada atributo utilizado.

**Métodos**
Explicación del funcionamiento de cada método:
- `depositar`
- `retirar`
- `consultarSaldo`

### Capturas de Pantalla
Incluir evidencias del funcionamiento del programa dentro de Pharo.

### Resultados Finales
Mostrar ejemplos de ejecución y resultados obtenidos.

---

## Criterios de Evaluación

| Criterio                              | Puntaje |
|---------------------------------------|---------|
| Creación correcta de la clase         | 25%     |
| Uso adecuado de atributos y métodos   | 25%     |
| Funcionamiento de depósitos y retiros | 25%     |
| Explicación en el PDF                 | 25%     |

---

## Recomendaciones

- Utilizar **nombres claros** para atributos y métodos
- Mantener **buena organización** del código
- Probar **distintos escenarios** de uso
- **Documentar correctamente** cada parte del laboratorio

---

## Bibliografía de Apoyo Sugerida

- **Sitio oficial de descarga Pharo:** [https://pharo.org](https://pharo.org)
- **Manual de Pharo** *(Ejemplo guiado paso a paso, Capítulo 5):* [Pharo by Example 9](https://books.pharo.org/pharo-by-example9/pdf/2022-03-26-index.pdf)
- **Curso MOOC Oficial:** [rmod-pharo-mooc.lille.inria.fr](https://rmod-pharo-mooc.lille.inria.fr/MOOC/2018-PreSequelOOP-ENG/)
- **Tutorial de YouTube:** [Introducción a Pharo](https://www.youtube.com/watch?v=_SXbdwEX6N0&list=PLjAkTa6GqXRdYkY2cWXTRWTYy7A0gms13)

---

## Entrega

- **Formato:** Documento PDF explicativo con capturas de pantalla del trabajo realizado
- **Fecha de entrega:** Establecida en clase
