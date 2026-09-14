# Guia para trabajar en el proyecto Planify_day

## 1. Clonar el repositorio

```bash
git clone https://github.com/veronicap3412-lang/Planify_day.git
cd Planify_day
```

## 2. Cambiar a tu rama

Cada integrante debe trabajar unicamente en su rama:

| Integrante      | Rama              |
|-----------------|-------------------|
| Juan Manuel     | `juan_manuel`     |
| Santiago        | `santiago_Popayan`|
| Veronica        | `veronica_p`      |
| Yuliana         | `yuliana_perez`   |

Ejemplo:
```bash
git checkout veronica_p
```

## 3. Trabajar en tus archivos

Solo modifica o crea archivos dentro de tu carpeta o con tu nombre. No edites archivos de otros compañeros.

## 4. Guardar cambios (commit)

```bash
git add .
git commit -m "descripcion de lo que hiciste"
```

## 5. Subir cambios a tu rama (push)

```bash
git push -u origin veronica_p
```
*(Reemplaza `veronica_p` con el nombre de tu rama)*

## 6. Actualizar tu rama con los cambios de main

Antes de trabajar, siempre actualiza tu rama:

```bash
git checkout main
git pull origin main
git checkout veronica_p   # vuelve a tu rama
git merge main            # trae los cambios de main
```

## 7. Reglas importantes

- **NO** hacer commit ni push directamente a `main`
- **NO** editar archivos de otros compañeros
- **SIEMPRE** pull de main antes de empezar a trabajar
- **SIEMPRE** trabajar en tu propia rama
- Los archivos deben llevar el nombre del autor (ej: `veronica_archivo.html`, `juan_archivo.html`)
