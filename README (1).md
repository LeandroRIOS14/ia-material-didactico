# IA: Entretejiendo Imaginación y Algoritmos

## Resumen
Proyecto para generar material didáctico en ciencias naturales usando IA: texto→texto (explicaciones adaptadas) y texto→imagen (esquemas/ilustraciones). Ideal para apoyar a docentes de nivel secundario y ahorrar tiempo en la preparación de recursos.

---

## Contenido del repositorio
- `README.md` — explicación y guía rápida.  
- `trabajo_ia.ipynb` — Notebook con celdas de prompts, ejemplos y resultados.  
- `images/` — Imágenes generadas de ejemplo.  
- `docs/` — Documento final opcional: metodología y conclusiones.

---

## Objetivo
Crear un flujo reproducible que:
1. Genere explicaciones claras y adaptadas a estudiantes (13–15 años).  
2. Produzca imágenes didácticas que acompañen las explicaciones.  
3. Documente prompts, decisiones y resultados en un notebook.

---

## Herramientas sugeridas
- Python 3.10+ y Jupyter Notebook.  
- OpenAI / ChatGPT (para texto) o interfaz web según disponibilidad.  
- Stable Diffusion / NightCafe / otra API de texto→imagen.  
- Librerías Python: `requests`, `openai`, `Pillow`, `jupyter`.

---

## Instalación rápida (local)
```bash
# crear entorno
python -m venv venv
source venv/bin/activate   # o venv\Scripts\activate en Windows

# instalar dependencias mínimas
pip install openai requests pillow jupyter
```
> Configurá tus claves de API como variables de entorno (`OPENAI_API_KEY`, etc.) antes de ejecutar el notebook.

---

## Prompts de ejemplo

### Prompt de texto (explicación)
```text
Explica la fotosíntesis en 100 palabras, usando un lenguaje para estudiantes de 14 años. 
Organiza la explicación en 3 frases claras y añade un ejemplo cotidiano corto.
```

### Prompt de imagen (esquema)
```text
Generar un esquema educativo de la fotosíntesis: planta con hojas, flechas indicando 'luz', 'agua', 'dióxido de carbono' entrando y 'azúcares' y 'oxígeno' saliendo. 
Estilo: infografía escolar, colores claros, etiquetas en español, fondo blanco.
```

---

## Resultados esperados
- Un conjunto de explicaciones (texto) listas para imprimir o poner en una presentación.  
- Varias imágenes/esquemas que acompañen las explicaciones.  
- Un notebook documentado con prompts, outputs y observaciones.

---

## Conclusiones
La IA facilita la generación de material didáctico rápido y personalizable. Es una herramienta de apoyo: los resultados suelen necesitar revisión humana para asegurar precisión y adecuación pedagógica.

---

## Referencias
- Documentación de OpenAI / ChatGPT.  
- Stable Diffusion / NightCafe (texto→imagen).  
- Material del curso: Coderhouse — Diplomatura Científico de Datos.
