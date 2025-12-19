# Landing QR - Fundación Cuenta Conmigo (Planes)

Landing page estática para que una sola impresión de **QR** lleve a una página donde el usuario elige su **aporte mensual** y luego continúa el proceso en **VirtualPOS**.

## Qué incluye
- Página única (`index.html`) con 7 planes y botones que redirigen a VirtualPOS
- Estilos (`styles.css`) inspirados en la identidad visual del sitio oficial
- Logo oficial descargado desde `fundacioncuentaconmigo.cl` en `assets/`

## Editar planes (URLs)
Los links están definidos en `index.html` dentro de la sección **Elige tu aporte mensual**. Si cambian las URLs de VirtualPOS, reemplázalas ahí.

## Deploy gratis con GitHub Pages (Project Pages)
1. Crea un repo en GitHub (por ejemplo: `landing-qr-fcc`).
2. Sube estos archivos a la rama `main` (en la raíz del repo):
   - `index.html`
   - `styles.css`
   - `assets/` (con `logo.png`, `logo-128.png`, `logo-32.png`)
3. En GitHub: **Settings → Pages**
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` + `/ (root)`
4. Espera 1–2 minutos. Tu URL quedará como:
   - `https://<usuario>.github.io/<repo>/`

## Generar el QR (para la calle)
- Genera un QR apuntando a la URL de GitHub Pages (ej: `https://<usuario>.github.io/<repo>/`).
- Recomendación: imprime también un texto corto debajo del QR (ej: “Escanea para hacerte socio/a”).

## Notas
- Esta landing **no procesa pagos**. Solo redirige al flujo oficial de suscripción en VirtualPOS.
- El diseño usa la fuente `Poppins` cargada desde Google Fonts.


