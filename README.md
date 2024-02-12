
# Auditar proyectos de ISPP-2024 con Bluejay.

## 1. Crear y configurar el repositorio.

**1.1. Crear un repositorio en GitHub.**

**1.2. En la rama main añadir un archivo `info.yml`.**

info.yml:
```yaml
project:
  name: 'ISPP-2024-LX-XX'
  owner: 'LX'
  teamId: 'XX'
  identities: {}
  notifications:
    email: 'XXXXXXXXXXX'
  members:
    member1:
      name: 'Manuel'
      surname: 'Otero' 
      githubUsername: 'motero2k'
    member2:
      name: 'Javi'
      surname: 'Fernandez' 
      githubUsername: 'JaviFdez7'
    member3:
      name: 'XXXXXXXXXXX'
      surname: 'XXXXXXXXXXX' 
      githubUsername: 'XXXXXXXXXXX'
    member4:
      name: 'XXXXXXXXXXX'
      surname: 'XXXXXXXXXXX' 
      githubUsername: 'XXXXXXXXXXX'
```

- Rellenar las X.
    > Por ejemplo, el grupo 54 del Laboratorio 2:
    > name = ISPP-2024-L2-54
- Borrar los members que no se usen.
- Añadir los members que se necesiten.

**1.3. Confirmar que la cuenta de governifyauditor tiene acceso al repositorio.**
- Si el repositorio es **propiedad de una organización de la US**, governifyauditor tendrá acceso.
- Si el repositrio es **privado** debe **invitar a governifyauditor como miembro del proyecto.**

## 2. Crear el GitHub Project
- Crear un tablero de GitHub
- Asignar el tablero al repositorio
- Las columnas del cambo Status deben ser **OBLIGATORIAMENTE:** `Todo, In Progress, In Review, Done` (case sensitive).
- El tablero debe ser público o tener a la cuenta de governifyauditor como miembro.
## 3. Unir el proyecto a la asignatura auditada por bluejay

- Accede a [join.bluejay.governify.io](https://join.bluejay.governify.io).
- Añade la **URL del repositorio** de GitHub.
- Click en **CHECK**. Si ha dado error revisa la [sintaxis](https://www.yamllint.com/) del info.yml.
- **Selecciona la clase** a la que te quieres unir (ISPP-2024).
- Click en **JOIN**.
- No pierdas el **enlace al dashboard**.


