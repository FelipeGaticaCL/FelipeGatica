# Portfolio — Coming Soon

Landing temporal para felipegatica.design mientras se termina el portfolio.

## Deploy en GitHub Pages

### 1. Crear el repo
- Nuevo repo público en GitHub llamado `felipegatica.design` (o el que prefieras — el nombre no afecta el dominio custom).
- Subir `index.html` y `CNAME` a la raíz.

### 2. Activar GitHub Pages
- Repo → **Settings** → **Pages**
- Source: **Deploy from a branch**
- Branch: `main` / root
- Guardar.

### 3. Configurar el dominio en tu registrar
En el panel DNS de donde compraste el dominio, agregá:

**Para el dominio raíz (felipegatica.design):**
Cuatro registros A apuntando a las IPs de GitHub Pages:
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

**Para www (opcional pero recomendado):**
Un registro CNAME:
```
www → TU-USUARIO.github.io
```

### 4. Verificar en GitHub
- Volver a Settings → Pages
- Custom domain: `felipegatica.design` → Save
- Esperar a que verifique el DNS (puede tardar hasta 24h, normalmente 10-30 min)
- Marcar **Enforce HTTPS** cuando aparezca disponible

### Listo
El sitio estará live en https://felipegatica.design con HTTPS.

## Reemplazar por el portfolio real
Cuando esté listo el portfolio, simplemente reemplazá `index.html` (y agregá los assets que necesites). El CNAME y la config de DNS ya están hechos.
