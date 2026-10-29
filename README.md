# Fakemail · Comunicado NovaTech

Vista web del comunicado para clientes de NovaTech, presentada dentro de la interfaz de correo Fakemail.

## Flujo

1. El usuario escribe su nombre.
2. Accede a la bandeja de Fakemail.
3. A los cinco segundos llega un correo de NovaTech con aviso sonoro y visual.
4. Los correos de la bandeja pueden abrirse en una vista de lectura completa.

## Desarrollo local

Abre `index.html` directamente o inicia un servidor estático:

```bash
python3 -m http.server 8000
```

La página estará disponible en `http://localhost:8000`.

## Publicación

El sitio se publica con GitHub Pages desde la rama `main`.
