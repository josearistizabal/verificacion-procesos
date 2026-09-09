# Verificador humano de procesos psicológicos (online)

App estática para codificar a ciegas el proceso psicológico de cada publicación
(15 procesos + Ninguno + Indeterminado + Combinar varios), con autoguardado en el
navegador y exportación a CSV. Pensada para validar el consenso multi-LLM.

## Publicar en GitHub Pages (gratis, online)
1. Crea un repositorio nuevo en https://github.com/new (p. ej. `verificacion-procesos`), público.
2. Sube el archivo **index.html** (botón *Add file → Upload files* → arrastra `index.html` → *Commit*).
3. Ve a **Settings → Pages** → en *Branch* elige `main` y carpeta `/ (root)` → *Save*.
4. En ~1 min tu app estará en `https://TU_USUARIO.github.io/verificacion-procesos/`.
   Ábrela desde cualquier navegador y empieza a codificar; se guarda en ese navegador.

## Importante sobre el guardado
- **Autoguarda en el navegador** (localStorage): puedes cerrar y volver en el mismo equipo/navegador.
- Para no depender de un solo equipo, pulsa **Exportar CSV** cada cierto tiempo; con **Importar CSV**
  retomas en otro equipo o navegador.
- El CSV (`verificacion_humana.csv`) es el archivo que se compara con los modelos.

## Comparación con los modelos
Sube `verificacion_humana.csv` a la carpeta de Drive `consenso_procesos/` (junto a
`qca_outputs_crudos.csv`) y ejecuta `Comparacion_Colab.py`, o envíaselo a tu asistente.
