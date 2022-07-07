<div align="center">
<table>
    <theader>
        <tr>            
            <th>
                <span style="font-weight:bold;">Heroku
            </th>            
        </tr>
    </theader>
    
</table>
</div>

<div align="center">
<span style="font-weight:bold;">GUÍA DE LABORATORIO</span><br />
</div>

<table>
    <theader>
        <tr><th colspan="2">INFORMACIÓN BÁSICA</th></tr>
    </theader>
<tbody>

<tr><td>TÍTULO DE LA PRÁCTICA:</td><td>Heroku</td></tr>
<tr><td colspan="2">RECURSOS:
    <ul>
        <li>https://www.heroku.com/</li>
        <li>https://devcenter.heroku.com/articles/heroku-cli</li>
        <li>https://www.geeksforgeeks.org/how-to-deploy-a-basic-static-html-website-to-heroku/</li>
        <li>William S. Vincent - Django for Beginners 3.1-leanpub (2020)</li>
    </ul>
</td>
</<tr>
<tr><td colspan="2">INSTRUCTOR:
    <ul>
        <li>Richart Smith Escobedo Quispe  - richarteq@gmail.com</li>
    </ul>
</td>
</<tr>
</tdbody>
</table>

# Heroku

[![License][license]][license-file]
[![Downloads][downloads]][releases]
[![Last Commit][last-commit]][releases]

[![Debian][Debian]][debian-site]
[![Git][Git]][git-site]
[![GitHub][GitHub]][github-site]
[![Vim][Vim]][vim-site]


#

## OBJETIVOS Y TEMAS

### OBJETIVOS
-   Estudiar un framework MVC.
-   Crear de una WebApp simple.
-   Desplegar la  WebApp en Heroku.

### TEMAS
- 

## CONTENIDO DE LA GUÍA

### MARCO CONCEPTUAL

#### Heroku

-   Heroku es una plataforma (PaaS - Plataforma como servicio) para desplegar aplicaciones que van a estar disponible en la nube.

-   Crear una cuenta gratuita en Heroku
    -   Acceda a https://www.heroku.com/ y registrese.    
    ![SIGNUP-HEROKU](imagenes/heroku-signup.png)
    -   Necesitará confirmar su incripción a través del correo electrónico.

#

#### Instalación - Inicio de sesión

-   Luego, instale en su sistema operativo el cliente de Heroku desde: https://devcenter.heroku.com/articles/heroku-cli

-   Para verificar que ya tiene el cliente de Heroku instalado ejecute desde una terminal:
    ```sh
    heroku --version
    ```
    ```sh
    heroku/7.60.1 linux-x64 node-v14.19.0
    ```

-   Inicie una sesión Heroku desde la consola:
    ```sh
    heroku login
    ```
    ```sh
    heroku: Press any key to open up the browser to login or q to exit:
    ```
    ![LOGIN-CLI-HEROKU](imagenes/heroku-login-cli.png)

    ![LOGIN-HEROKU](imagenes/heroku-login.png)
    ```sh
    Opening browser to https://cli-auth.heroku.com/auth/cli/browser/...
    Logging in... done
    Logged in as rescobedoq@unsa.edu.pe
    ```
    ![LOGGED-HEROKU](imagenes/heroku-logged.png)

#

#### Desplegar una webapp sencilla en Heroku

-   Primero, crearemos un hola mundo en PHP y lo deplegaremos en una aplicación Heroku.

    -   Paso 01: Crear una nueva aplicación en el dashboard de heroku: https://dashboard.heroku.com/apps


## EJERCICIOS PROPUESTOS

1.  En el framework para desarrollo de aplicaciones web que esta estudiando. 
    -   Cree los CRUDS para modelo de su proyecto.  
    -   Personalize sus plantillas.
    -   Y publíque su WebApp en la plataforma Heroku.


## REFERENCIAS
    -   https://www.heroku.com/
    -   https://devcenter.heroku.com/articles/heroku-cli
    -   https://www.geeksforgeeks.org/how-to-deploy-a-basic-static-html-website-to-heroku/
    -   William S. Vincent - Django for Beginners 3.1-leanpub (2020)

#

[license]: https://img.shields.io/github/license/rescobedoulasalle/git_github?label=rescobedoulasalle
[license-file]: https://github.com/rescobedoulasalle/git_github/blob/main/LICENSE

[downloads]: https://img.shields.io/github/downloads/rescobedoulasalle/git_github/total?label=Downloads
[releases]: https://github.com/rescobedoulasalle/git_github/releases/

[last-commit]: https://img.shields.io/github/last-commit/rescobedoulasalle/git_github?label=Last%20Commit

[Debian]: https://img.shields.io/badge/Debian-D70A53?style=for-the-badge&logo=debian&logoColor=white
[debian-site]: https://www.debian.org/index.es.html

[Git]: https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white
[git-site]: https://git-scm.com/

[GitHub]: https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white
[github-site]: https://github.com/

[Vim]: https://img.shields.io/badge/VIM-%2311AB00.svg?style=for-the-badge&logo=vim&logoColor=white
[vim-site]: https://www.vim.org/






[![Debian][Debian]][debian-site]
[![Git][Git]][git-site]
[![GitHub][GitHub]][github-site]
[![Vim][Vim]][vim-site]


[![License][license]][license-file]
[![Downloads][downloads]][releases]
[![Last Commit][last-commit]][releases]