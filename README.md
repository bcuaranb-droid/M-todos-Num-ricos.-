# Markdown

Documento de aprendizaje de los principales comandos y usos de markdown aplicado en archivo de Github

# 📘 Guía Básica de Markdown

Markdown es un lenguaje de marcado ligero que permite dar formato a texto plano de manera sencilla y legible. Es ampliamente utilizado en GitHub para documentar proyectos, escribir README, issues y wikis.

---

## 🧠 ¿Qué es Markdown?

Markdown permite escribir texto con formato usando símbolos simples, sin necesidad de editores visuales complejos.

### Se usa principalmente para:
- Documentación técnica
- README.md en GitHub
- Apuntes
- Blogs y wikis
- Comentarios en plataformas de desarrollo

---

## ✍️ Organización del Texto

### Títulos y subtítulos
Los títulos se crean usando el símbolo `#`.

# Título principal
## Subtítulo
### Subnivel

---

### Párrafos

Se escriben normalmente, dejando una línea en blanco entre ellos.

Este es un párrafo.
para texto que no se renderize usamos   ` (```md ) ` y lo cerramos con (```) 

```md
Este es otro párrafo.
```


## Negrita, cursiva y tachado
`(**Texto en negrita**)` (**Texto en negrita**)
`(*Texto en cursiva*)` (*Texto en cursiva*)  
`(***Negrita y cursiva***)`   (***Negrita y cursiva***)
`(~~Texto tachado~~)`   (~~Texto tachado~~)

---

## 📋 Listas
Lista sin orden
- Elemento 1
- Elemento 2
  - Subelemento
  -subelemento

---

## Lista ordenada
1. Paso uno
2. Paso dos
3. Paso tres

---

🔗 Enlaces e Imágenes
Enlaces
[GitHub](https://github.com)

---

Imágenes
![Imagen seria ]([URL_de_la_imagen]([https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTo44zZa80wIuluo2n593TI1v0EygubQvVfJkEHQfGynQ&s](https://i.pinimg.com/564x/22/7f/c3/227fc3e9bb479ae4ff39cbf0dbf0dc21.jpg)))

---

## 💻 Código en Markdown
Código en línea

Se usa para comandos o palabras clave.
Usa el comando `git status`

Bloques de código

Se usan tres comillas invertidas.
```bash
git add .
git commit -m "mensaje"
git push

Puedes especificar el lenguaje para resaltado:
- `bash`
- `python`
- `javascript`
- `html`
- `sql`

---

## 🧾 Tablas

```md
| Comando     | Función                     |
|-------------|------------------------------|
| git status  | Ver estado del repositorio   |
| git pull    | Actualizar repositorio       |
| git push    | Subir cambios                |

---

## ✅ Checklists (muy usado en GitHub)
- [x] Tarea completada
- [ ] Tarea pendiente

---

## Cita
> Esto es una cita importante, recuerdalo -o-

## ⭐ Ventajas de Markdown frente a otros formatos

### ✅ Frente a Word o Google Docs
- No depende de programas pesados  
- Compatible con control de versiones (Git)  
- Archivos livianos y universales  

### ✅ Frente a HTML
- Más fácil de escribir  
- Más legible  
- Menos código innecesario  

### ✅ Frente a texto plano
- Permite formato  
- Mejor organización  
- Ideal para documentación técnica  

---

## 👤 Autor
Bryan Stiven Cuaran
