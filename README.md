📌 GITColaborativoIvan-Alex
📖 Descripción

Este proyecto es una práctica de trabajo en equipo utilizando Git y GitHub, donde aplicamos un flujo de trabajo con ramas, roles y resolución de conflictos para gestionar cambios de manera eficiente.
👥 Integrantes y Roles

    Alejandro Alcaide - Líder de proyecto

    Iván Gómez - Desarrollador de estructura

🔀 Flujo de Trabajo
1️⃣ Creación del repositorio

    Se creó el repositorio en GitHub: GITColaborativoIvan-Alex

    Se configuró la estructura de ramas:

        main → Rama principal con la versión final.

        desarrollo → Rama de integración antes de pasar a main.

        tarea-nombre-de-la-tarea → Ramas individuales para cada funcionalidad.

2️⃣ Proceso de trabajo con ramas

Cada integrante creó una rama basada en desarrollo:

git checkout -b tarea-nombre-de-la-tarea desarrollo

Luego, realizaron cambios en sus respectivas ramas y los subieron al repositorio remoto:

git add .
git commit -m "Descripción del cambio"
git push origin tarea-nombre-de-la-tarea

Finalmente, se creó un Pull Request (PR) para fusionar los cambios en desarrollo, revisado y aprobado por el líder de proyecto.
3️⃣ Fusión de cambios en main

Una vez integradas todas las tareas en desarrollo, se realizó un último PR para fusionar desarrollo en main.
📸 Historial de commits y ramas

Se utilizó el siguiente comando para visualizar el historial de commits y ramas:

git log --oneline --graph --all

📌 Se adjuntan capturas de pantalla con la historia de commits y ramas.
✅ Conclusión

Este ejercicio permitió aplicar buenas prácticas de trabajo en equipo con Git, mejorando la colaboración y organización mediante ramas y pull requests. 🚀
