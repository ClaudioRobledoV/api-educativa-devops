# API Educativa DevOps

## Estrategia de ramas

Para este proyecto se decidió utilizar la estrategia **GitFlow**, ya que permite organizar el desarrollo de manera clara, separando el código en distintas etapas como desarrollo, pruebas y producción. Esto facilita el trabajo ordenado y evita errores al momento de integrar cambios.

---

## Ramas principales

- **main**: contiene la versión estable del proyecto, es decir, la que estaría en producción.
- **develop**: es la rama donde se integran los cambios antes de pasar a producción.

---

## Ramas de trabajo

- **feature/<nombre>**: se utilizan para desarrollar nuevas funcionalidades de forma independiente.
- **hotfix/<nombre>**: se usan para corregir errores críticos detectados en producción.

---

## Cambios realizados

Durante el desarrollo del trabajo se realizaron los siguientes cambios:

- **Feature: primer cambio**  
  Se agregó una mejora simulada para probar el uso de ramas feature y el flujo de trabajo.

- **Feature: segundo cambio**  
  Se realizó un segundo cambio para continuar con la simulación de trabajo colaborativo.

- **Hotfix**  
  Se corrigió un error en el archivo README para simular una corrección en producción.

---

## Convención de commits

Para mantener un orden en los cambios realizados, se utilizaron los siguientes prefijos:

- **feat**: cuando se agrega una nueva funcionalidad  
- **fix**: cuando se corrige un error  
- **docs**: cuando se modifica documentación  
- **chore**: tareas de mantenimiento  

**Ejemplos:**
- feat: se agrega primer cambio  
- fix: se corrige error en README  

---

## Naming de ramas

Se utilizaron las siguientes convenciones para nombrar las ramas:

- **main**: rama principal  
- **develop**: rama de desarrollo  
- **feature/<nombre>**: nuevas funcionalidades  
- **hotfix/<nombre>**: correcciones críticas  

---

## Flujo de trabajo

El flujo de trabajo utilizado fue el siguiente:

1. Se crean ramas **feature** a partir de `develop`
2. Se desarrollan los cambios en estas ramas
3. Se integran a `develop` mediante Pull Request
4. Una vez validados, los cambios pueden pasar a `main`
5. En caso de errores, se crean ramas **hotfix** desde `main`
6. Los hotfix se integran tanto en `main` como en `develop`
7. En algunos casos se presentaron conflictos, los cuales se resolvieron manualmente

---

## Estrategia de revisión

Para asegurar la calidad del trabajo se utilizó:

- Uso de **Pull Requests** para cada cambio
- Revisión antes de realizar merge
- Resolución de conflictos cuando fue necesario

---

## Justificación

Se eligió GitFlow porque permite trabajar de manera ordenada y estructurada, especialmente cuando se manejan varias tareas al mismo tiempo. Además, facilita la identificación de errores y su corrección sin afectar el desarrollo principal.