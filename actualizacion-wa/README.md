# Campaña "Actualización WhatsApp: @username + PIN"

## Entregables
- `noticia-craftdigit.md`: nota estilo newsroom lista para publicar.
- `index.html`: landing responsiva (Azul Plomo + Verde Neón) con bloque de botones "Me Gusta" y footer fijo dividido en comunidad + GitHub Stars.
- `social-whatsapp.txt`: mensaje corto para enviar por WhatsApp con foco en impacto de privacidad.

## Pendientes para el equipo
1. **Imagen hero**: reemplazar `assets/actualizacion-wa.jpg` con la imagen aprobada (la adjunta en la consigna). Mantener mismo nombre o actualizar `src` en `index.html`.
2. **URL reales**:
   - En la CTA "Sumate a la comunidad" poner el enlace definitivo al grupo/flow de WhatsApp.
   - En los enlaces a GitHub, ajustar al repositorio exacto.
   - Completar `{{URL_GITHUB_PAGES}}` en `social-whatsapp.txt` una vez publicada la landing.
3. **Deploy**:
   - Publicar `index.html` en GitHub Pages (branch `main` / carpeta raíz o `docs/`).
   - Confirmar que el sitio queda accesible en `https://macdevbot.github.io/actualizacion-wa/` (o URL que corresponda) para compartirlo.
4. **Push**: subir la carpeta `actualizacion-wa` al repositorio remoto y correr el flujo de CI/CD si aplica.

## Cómo probar localmente
```bash
cd macdevbot-coder/actualizacion-wa
python3 -m http.server 8080
# Abrir http://localhost:8080
```

Cualquier ajuste adicional (copy, métricas, automatizaciones) puede documentarse en este README para mantener el traspaso ordenado.
