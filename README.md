# 010 — Tu progreso

Aplicación web progresiva (PWA) para registrar nutrición, agua, actividad, peso y medidas.

## Incluye
- Inicio con resumen diario de calorías, agua y actividad.
- Registro manual de calorías por comida; sin macros ni base de datos de alimentos.
- Objetivos calóricos separados para entrenamiento y descanso.
- Calendario semanal configurable y registro de actividad.
- Seguimiento de peso con gráfico y objetivo flexible.
- Medidas corporales personalizables.
- Perfil con estimación metabólica Mifflin-St Jeor.
- Exportación y restauración de copia JSON.
- Almacenamiento local, sin cuenta ni suscripción.
- PWA con caché offline tras la primera carga.

## Publicar gratis en GitHub Pages
1. Descomprime `010-proyecto.zip`.
2. Sube el contenido de la carpeta `010` a la raíz de tu repositorio `PROV-9-10` (debe quedar `index.html` en la raíz).
3. En GitHub, abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Guarda.
5. Cuando termine, la URL será `https://luistorresprov910.github.io/PROV-9-10/` si esos son los nombres actuales de usuario y repositorio.

## Instalar en iPhone
1. Abre la web publicada en Safari.
2. Pulsa Compartir → **Añadir a pantalla de inicio**.
3. Confirma el nombre 010.

## Datos y privacidad
Los registros se guardan en el navegador de este dispositivo. Exporta una copia JSON regularmente; al restaurarla se sustituyen los datos actuales. El recordatorio mensual aparece dentro de la app al abrirla el día 1.

## Límites
- No hay sincronización con Apple Health; introduce la actividad manualmente.
- El recordatorio mensual no es una notificación push.
- El cálculo metabólico es orientativo.
- La primera carga requiere conexión; después se almacenan los recursos principales para uso offline.
