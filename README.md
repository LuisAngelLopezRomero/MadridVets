# Madrid Vets · Guía veterinaria

PWA personal para consulta rápida de protocolos de medicación y cálculo de dosis en pequeños animales.

> **Uso profesional.** Verifica siempre ficha técnica/prospecto vigente, presentación exacta, especie, peso, contraindicaciones, interacciones y situación clínica.

## Portada

**MR**  
**Madrid Vets**  
*Guía para sobrevivir a la consulta… o al menos parecer que lo tienes todo controlado y acabar el turno con el pelo en su sitio.*

## Publicar en GitHub Pages

1. Crea un repositorio nuevo, por ejemplo `madrid-rio-vet-guide`.
2. Sube **todos** los archivos de esta carpeta a la raíz del repositorio.
3. En GitHub entra en **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`.
6. Guarda y espera a que GitHub te muestre la URL publicada.
7. En iPhone: abre esa URL en Safari → **Compartir → Añadir a pantalla de inicio**.

## Acceso

La versión entregada lleva una pantalla de acceso activada.

**Clave de acceso:** `Sobreviviendo`

El acceso se recuerda durante 30 días en ese dispositivo.

### Importante sobre seguridad

GitHub Pages sirve archivos estáticos. Esta pantalla evita el acceso casual, pero **no es autenticación real**: una persona técnica puede inspeccionar el código publicado o evitar la pantalla. No subas datos de clientes, historiales, credenciales, documentos internos ni otra información confidencial.

## Cambiar la clave

En `index.html`, busca `const ACCESS =` y sustituye el valor `hash` por el SHA-256 de la nueva contraseña. Puedes obtenerlo en tu equipo, por ejemplo con Python:

```python
import hashlib
print(hashlib.sha256("TU_NUEVA_CLAVE".encode()).hexdigest())
```

## Independencia

Herramienta personal e independiente. No afiliada ni respaldada por ninguna clínica, empresa o laboratorio.
