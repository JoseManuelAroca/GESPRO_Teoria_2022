<a name="readme-top"></a>

# GESPRO_Teoria_2022
### Aplicación de apuestas deportivas

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Vea</summary>
  <ol>
    <li>
      <ul>
         <li><a href="#enunciado-de-la-práctica">Enunciado de la práctica</a></li>
         <li><a href="#participantes-del-proyecto">Participantes del proyecto</a></li>
      </ul>
    </li>
    <li><a href="#descripción">Descripción</a></li>
    <li><a href="#requisitos">Requisitos</a></li>
    <li><a href="#instalación">Instalación</a></li>
    <li><a href="#usabilidad">Usabilidad</a>
        <ul>
        <li><a href="#gestión-de-usuarios">Gestión de usuarios</a></li>
        <li><a href="#apartado-deportivo">Apartado deportivo</a></li>
        <li><a href="#gestión-del-dinero">Gestión del dinero</a></li>
      </ul>
    </li>
    <li><a href="#licencia-de-la-aplicación">Licencia de la aplicación</a>
        <ul>
            <li><a href="#licencias-generales">Licencias generales</a></li>
            <li><a href="#requisitos-de-licencia-de-juego">Requisitos de licencia de juego</a>
                <ul>
                    <li><a href="#requisitos-jurídicos">A.Requisitos jurídicos</a></li>
                    <li><a href="#requisitos-económicos">B.Requisitos económicos</a></li>
                    <li><a href="#requisitos-técnicos">C.Requisitos técnicos</a></li>
                </ul>
            </li>
        </ul>
    </li>
    <li><a href="#contacto">Contacto</a></li>
  </ol>
</details>

### Enuciado de la práctica
Repositorio a emplear por los alumnos de la asignatura de Gestión de Proyectos (3º de G. en Ing. Informática) en el curso académico 2022/23. Universidad de Burgos.

Para completar el trabajo de estudio en grupo en las sesiones de teoría, se iniciará el repositorio de cada grupo (en el que se completará el resto de la práctica) por medio de un fork a este repositiorio.


JMA modifica

### Participantes del proyecto

* Alberto Santos Martínez
* Miguel Ubierna Gutiérrez
* Mario Sanz Perez

A continuación se detallará información acerca de nuestra apliación de apuestas

<!-- Descripción -->
## Descripción
Nuestra aplicación se centra en las apuestas deportivas de varios deportes, por ejemplo fútbol, baloncesto, tenis o formula uno. Cada usuario deberá crearse una cuenta nueva e iniciar sesión cada vez que entre en nuestra aplicación pero tambien podrá recordar su usuario o contraseña para no tener que pasar por este proceso cada vez que la inicia. Cada apartado de deporte aparecerá en una lista con varios botones que representarán tanto el nombre como un pequeño dibujo del deporte que le caracteriza. Por ejemplo, en el caso de futbol, aparecerá un icono con el nombre de `Fútbol` seguido de una imagen como esta:

<img height = "100" width = "100" src="soccer-ball_39433.png" align="left"/>

<br>
<br>
<br>
<br>
<br>

Una vez entrado en un apartado de un deporte, podrá ver una lista de los proximos partidos en orden descendente desde el próximo hasta el de dentro de una semana. Si el usuario selecciona un partido, entrará en una interfaz nueva en la que podrá elegir el ganador del partido o en caso de probabilidad de empate, tambien podrá elegir empate (en formula uno no hay empate). Al igual que elegir quien es el ganador del partido, podrá seleccionar cual será el posible resultado del partido, si van a acabar 1-2 o 4-0, por ejemplo. Una vez elegido el resultado, dirá cuanta cantidad de dinero quiere invertir en dicha apuesta y le aparecerá el balance de cuanto ganará en caso de acierto. Para meter el dinero en la cuenta lo podrá hacer de varias formas entre las cuales están Paypal y transferencia del banco, se dirá cuanto dinero quieren introducir y se pasará en dinero a la cuenta en un periodo máximo de 3 días laborales.

<p align="right">(<a href="#readme-top">volver arriba</a>)</p>

<!-- Requisitos -> +18, dispositivo movil/PC -->
## Requisitos
Para poder usar esta aplicación se tendrán que cumplir unos requisitos, los cuales serán:
<br>
* Nuestra aplicación al ser de apuestas tendrá como principal requisito de que el usuario sea mayor de edad, siendo esta la edad de mayoría de edad para poder empezar a ser responsable de los actos de uno mismo.
* Tener un ordenador o un teléfono móvil compatible con la aplicación
* Documento de identidad del usuario en la que se vea que nuestro usuario tiene la mayoría de edad
* Una foto del usuario para compararla con la del documento de identidad

<p align="right">(<a href="#readme-top">volver arriba</a>)</p>

<!-- Instalación -->
## Instalación
Para poder instalar esta apliación, el usuario tendrá que:
* Podrá descargarla en su dispositivo a través de la Play Store en android o la App Store en apple. 
* En un ordenador, se podrá acceder perfectamente a través de nuestra página web: https://aplicacionDeApuestas.example.com

<p align="right">(<a href="#readme-top">volver arriba</a>)</p>


<!-- Funcionalidad de la aplicación -->
## Usabilidad
Una vez instalada la aplicación, el usuario se encontrará con varias **funciones** que puede realizar:

### Gestión de Usuarios 
1. El usuario puede registrarse usando la interfaz del login.
2. Acceso a un perfil de usuario donde puede modificar informacion personal: *DNI*,*cuenta bancaria*,etc.
3. Posibilidad de ver perfiles de "amigos".
4. El usuario debe aceptar la politica de provacidad y los terminos y condiciones de uso de la información.

### Apartado deportivo
1. Elegir el deporte por el que se desea apostar.
2. Ver resultados a tiempo real.
3. Notificaciones de interes para el usuario.
4. Introducir importe para la apuesta.
5. Posibilidad de combinar varias apuestas.

### Gestión del dinero
1. EL usuario puede ingresar y sacar dinero mediante el metodo de pago a su elección.
2. Resumen estadistico de ganancias/perdidas.
3. Retirada del dinero al final o en medio de un evento deportivo.

<p align=“right”>(<a href="#readme-top">volver arriba</a>)</p>

<!-- Preguntas frecuentes-->
## FAQ
* **¿Es posible entrar a la aplicación siendo menor de edad?**
Para acceder a la aplicación se debe introducir el DNI real para comprobar la edad y para controlar el acceso a ciertas personas.
* **¿Puedo retirar mi dinero en cualquier momento?**
Sí, todo el dinero pertenece al usuario y puede retirarlo cundo quiera.
* **¿Mi información esta bien protegida?**
Toda la información se guarda en una base de datos protegida de cualquier acceso no deseado.
* **¿La aplicación informa de los ultimos resultados y de otra informacion de los equipos?**
A la hora de apostar en cualquier deporte la aplicación nos indica las últimas noticias/resultados para que se pueda apostar basandonos en algo fundamentado.

<p align=“right”>(<a href="#readme-top">volver arriba</a>)</p>

<!-- Licencia de la aplicación-->
## Licencia de la aplicación 

### Licencias generales

Habilitan a su titular para el ejercicio de las modalidades de juego de apuestas, concursos y otros juegos. El otorgamiento de dichas licencias se realiza por la DGOJ previa la oportuna convocatoria de un procedimiento administrativo guiado por los principios de publicidad, concurrencia, igualdad, transparencia, objetividad y no discriminación, recogidos en el pliego de bases que regirán la convocatoria y que se publicará en el «Boletín Oficial del Estado». Asimismo, también cabe la apertura del procedimiento a instancia del interesado (los interesados pueden solicitar la convocatoria de un nuevo procedimiento de otorgamiento de licencias generales para la explotación y comercialización de determinados juegos, transcurridos al menos 18 meses contados desde la fecha de la anterior convocatoria en relación con la misma modalidad de juego). En este caso, la DGOJ dispone de un plazo de 6 meses para iniciar dicho procedimiento salvo que se estimara, en base a razones de interés general, no proceder a la convocatoria del mismo.
Su duración es de 10 años prorrogables por un periodo de idéntica duración.


### Requisitos de licencia de juego
En este apartado se determinarán los requisitos para obtener la licencia de juego


#### A.Requisitos jurídicos

* Forma de sociedad anónima o forma societaria análoga, con domicilio social en un Estado perteneciente al Espacio Económico Europeo.
* Presentar como objeto social único la organización, comercialización y explotación de juegos.
* Estar en posesión de un capital social mínimo, total y desembolsado, de 100.000 euros para la solicitud de licencia general de la modalidad de juego “Apuestas” y “Otros juegos” o de 60.000 euros cuando únicamente se solicite una licencia general para el desarrollo de la modalidad de juego “Concursos”.
* Inscripción en el Registro Mercantil o, en el supuesto de sociedades extranjeras, en un registro equivalente siempre que la legislación del Estado en el que la sociedad tenga su sede legal requiera la inscripción.
* Inscripción en la Sección Especial de Concurrentes del Registro General de Licencias de Juego.
* No concurrir en ninguna de las circunstancias previstas en el artículo 13.2 de la Ley 13/2011, de 27 de mayo, de regulación del juego.


#### B.Requisitos económicos

* Declaraciones apropiadas de entidades financieras sobre la solvencia de la sociedad.
* Cuentas anuales presentadas en el Registro Mercantil o en el Registro oficial que corresponda.
* Declaración sobre el volumen global de negocios en los tres últimos ejercicios.
* Descripción y origen de los recursos financieros propios y ajenos
* Sin perjuicio de que la DGOJ, por razones justificadas, pueda autorizar al solicitante la acreditación de su solvencia económica y financiera por medio de cualquier otro documento que considerara apropiado.


#### C.Requisitos ténicos

* Declaración indicando la estructura de personal técnico.
* Experiencia profesional de los directivos de la entidad responsable del desarrollo de las actividades de juego objeto de la licencia.
* Declaración sobre la plantilla media anual de la entidad durante los tres últimos años.
* Declaración indicando los sistemas técnicos de los que dispondrá para el desarrollo de las actividades de juego objeto de la licencia.
* Descripción de las instalaciones o unidades técnicas, de las medidas empleadas para garantizar la calidad y la seguridad y, en su caso, de los medios de estudio e investigación de la empresa.
 
<p align=“right”>(<a href="#readme-top">volver arriba</a>)</p>

<!-- Contacto-->
## Contacto 

Your Name - [@scrumApuestas](https://twitter.com/scrumApuestas) - scumApuestas@gmail.com

Project Link: [https://github.com/MarioSanzP/GESPRO_Teoria_2022](https://github.com/MarioSanzP/GESPRO_Teoria_2022)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
