# 🎶 TikTok Trend - Rock That Body (Black Eyed Peas)

Este proyecto reproduce en la **terminal** un efecto visual inspirado en un trend de **TikTok**, utilizando un fragmento de la canción *Rock That Body* de **Black Eyed Peas**.  
El texto aparece con un efecto de tipeo progresivo y cambios de estilo, simulando la sincronización con el ritmo de la música.

## ✨ Características
- Reproduce frases del fragmento de la canción con tiempos sincronizados.  
- Efecto de escritura letra por letra en la terminal.  
- Algunas frases se muestran en **mayúsculas** para dar más impacto (simulando el clímax del trend).  
- Compatible con **Windows**, **Linux** y **Mac**.  

## 📦 Requisitos
- Python **3.7+**  
- Librerías estándar de Python (`os`, `time`) → no requiere instalaciones adicionales.  

## ▶️ Ejecución
1. Descarga o clona este repositorio.  
2. Guarda el archivo como `trend.py` (o el nombre que prefieras).  
3. Abre una terminal en la carpeta del archivo.  
4. Ejecuta:  

```bash
python trend.py
📂 Estructura del Código
lyrics_with_timing → contiene el fragmento de la canción y el tiempo en segundos para cada línea.

clear_terminal() → limpia la pantalla entre frases.

type_line_trend() → imprime cada carácter con efecto de tipeo.

run_trend() → reproduce todo el efecto en orden.

🎵 Personalización
Si quieres usar otro fragmento de canción o frase para otro trend:

Edita la lista lyrics_with_timing.

Cambia el texto y ajusta el tiempo para sincronizarlo con la música:

python
Copiar código
lyrics_with_timing = [
    ("Nueva frase aquí", 3.0),
    ("Otra frase", 2.5),
]