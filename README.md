# Nombre del Proyecto


## Descripción


## Instalación
Sigue estos pasos para ejecutar el proyecto en tu máquina local:

- Clona el repositorio:
    git clone <URL_DEL_REPOSITORIO>

- Ingresa a la carpeta del proyecto:
    cd <NOMBRE_DEL_PROYECTO>

- (Opcional) Crea y activa un entorno virtual:
    python -m venv venv
    venv\Scripts\activate   # En Windows
    source venv/bin/activate # En Linux/Mac

- Ejecuta el programa principal:
    python Menu.py

## Uso
Al ejecutar el programa, se mostrará un menú interactivo en consola donde podrás seleccionar diferentes juegos de azar.

Ejemplo de flujo:

    === MENÚ DE JUEGOS ===
    1. Blackjack
    2. Craps
    3. Bingo
    4. Salir
    Seleccione una opción:

- Ingresa el número correspondiente al juego que deseas.
- Sigue las instrucciones en pantalla para jugar.
- Puedes regresar al menú principal al finalizar cada juego.

Juegos disponibles
- Blackjack: Juego de cartas contra la máquina.
- Craps: Juego de dados basado en probabilidades.
- Bingo: Juego de números aleatorios.

## Autores
- Rosa Isabel Peña Yagüe

## Flujo de trabajo Git
Durante el desarrollo del proyecto se utilizó la estrategia Git Flow para organizar el trabajo en equipo y mantener un flujo ordenado de integración.

    Rama principal
- main: Contiene la versión estable del proyecto lista para producción.
    Rama de desarrollo
- develop: Rama base donde se integraron todas las funcionalidades antes de preparar la versión final.

    Ramas feature
Se crearon ramas específicas para cada funcionalidad:

- feature/juego-blackjack
- feature/juego-craps
- feature/juego-bingo
- feature/documentacion-extra

Estas ramas se fusionaron posteriormente en develop mediante pull requests.

    Rama release
- release/v1.0.0: Se creó para preparar la versión final del proyecto.
Aquí se realizaron ajustes finales en documentación, README y detalles menores antes de pasar a main.

    Rama hotfix
- hotfix/readme-typo: Se utilizó para corregir errores menores en la documentación después de creada la release.

    Versión final
- Se creó el tag:
    git tag v1.0.0

Este tag representa la versión estable del proyecto lista para entrega.

## Evidencias
A continuación se presentan evidencias del desarrollo y flujo de trabajo:

- Historial de commits con uso de ramas:
    - Commits realizados en feature/, develop y release

- Creación del tag final:
    git tag v1.0.0
    git push origin v1.0.0
    
- Capturas del proceso (agregar aquí):
 Creación de ramas feature
 Merge hacia develop
 Creación de release/v1.0.0
 Merge final a main
 Tag v1.0.0 en el repositorio

- Enlace al repositorio:
    <URL_DEL_REPOSITORIO>
