<div align="center">
<table>
    <theader>
        <tr>
            <td><img src="https://github.com/rescobedoq/pw2/blob/main/epis.png?raw=true" alt="EPIS" style="width:50%; height:auto"/></td>
            <th>
                <span style="font-weight:bold;">UNIVERSIDAD NACIONAL DE SAN AGUSTIN</span><br />
                <span style="font-weight:bold;">FACULTAD DE INGENIERÍA DE PRODUCCIÓN Y SERVICIOS</span><br />
                <span style="font-weight:bold;">ESCUELA PROFESIONAL DE INGENIERÍA DE SISTEMAS</span>
            </th>
            <td><img src="https://github.com/rescobedoq/pw2/blob/main/abet.png?raw=true" alt="ABET" style="width:50%; height:auto"/></td>
        </tr>
    </theader>
    <tbody>
        <tr><td colspan="3"><span style="font-weight:bold;">Formato</span>: Guía de Práctica de Laboratorio / Talleres / Centros de Simulación</td></tr>
        <tr><td><span style="font-weight:bold;">Aprobación</span>:  2022/03/01</td><td><span style="font-weight:bold;">Código</span>: GUIA-PRLE-001</td><td><span style="font-weight:bold;">Página</span>: 1</td></tr>
    </tbody>
</table>
</div>

<div align="center">
<span style="font-weight:bold;">INFORME DE LABORATORIO</span><br />

<table>
<theader>
<tr><th colspan="6">INFORMACIÓN BÁSICA</th></tr>
</theader>
<tbody>
<tr><td>ASIGNATURA:</td><td colspan="5">Progamación Web 2</td></tr>
<tr><td>TÍTULO DE LA PRÁCTICA:</td><td colspan="5">Ajax y NodeJS</td></tr>
<tr>
<td>NÚMERO DE PRÁCTICA:</td><td>03</td><td>AÑO LECTIVO:</td><td>2022 A</td><td>NRO. SEMESTRE:</td><td>III</td>
</tr>
<tr>
<td>FECHA DE PRESENTACIÓN:</td><td></td><td>HORA DE PRESENTACIÓN:</td><td colspan="3"></td>
</tr>
<tr><td colspan="3">INTEGRANTE(s):
<ul>
    <li>Azurin Zuñiga Eberth - eazurin@unsa.edu.pe</li>
    <li>Cárdenas Martines Franco - fcardenasm@unsa.edu.pe</li>
    <li>Carrillo Daza Barbara - bcarrillo@unsa.edu.pe</li>
    <li>Hancco Condori Bryan - bhanccoco@unsa.edu.pe</li>
    <li>Velita Aguilar Italo - ivelita@unsa.edu.pe</li>
</ul>
</td>
<td>NOTA:</td><td colspan="2"></td>
</<tr>
<tr><td colspan="6">DOCENTE(s):
<ul>
<li>Richart Smith Escobedo Quispe - rescobedoq@unsa.edu.pe</li>
</ul>
</td>
</<tr>
</tbody>
</table>

<table>
<theader>
<tr><th>Solución y resultados</th></tr>
</theader>
<tbody>
<tr><td>I. SOLUCIÓN DE EJERCICIOS/PROBLEMAS<br><br>
 En grupos de 3 a 5 personas implemente una aplicación web que navegue sobre archivos Markdown y permita:
    <ol>
        <li>Listas los archivos Markdown disponibles</li>
        <li>Ver el contenido de un archivo Markdown traducido a HTML</li>
        <li>Crear nuevos archivos MarkDown y almacenarlos en el servidor</li>
    </ol>
La comunicación entre el cliente y el servidor tiene que ser usando JSON sólamente. <br>
El cliente debe usar AJAX para sus peticiones. <br>
El servidor debe usar NodeJS. <br>
Su aplicación debe ser de página única, es decir que sólo habrá un archivo index.html y nada más. <br>
Si los enlaces proporcionado en esta guía no le son suficientes, puede revisar códigos en Internet que le ayuden con cosas como ejemplos: listar un directorio en NodeJS; pero deberá incluir los enlaces correspondientes en sus archivos como comentarios y sólo podrá usar código de stackoverflow, incluir código de cualquier otra fuente está prohibido y se considerará actitud deshonesta. <br>
 </tr></td>
    <tr><td>ORGANIZACIÓN<br><br>Nos dividimos en dos ramas, backend y frontend, en la rama frontend estuvo organizada puesto que 2 se encargaron de ello.<br>En la rama backend, hicimos reuniones para comprender el contexto del proyecto y tratamos de dividirnos puesto que todo se complementaba decidimos crear soluciones por separado y luego se elegirìa la mejor solución, en las reuniones de meet luego vimos cuàl era la que añadirìamos al main.</td></tr>
  
<tr><td>II. SOLUCIÓN DEL CUESTIONARIO<br><br>
<ul>
    <li>En el Ejemplo "Hola Mundo" con NodeJS. ¿Qué pasó con la línea: "Content type ….."?</li>
        No fue necesario su uso, en este se envio de manera predeterminada con el Content-Type: text/HTML
    <li>En los ejercicios. ¿En qué lugar debería estar el archivo poema.txt?</li>
        En una carpeta denominada priv, que a su vez debería estar en el mismo directorio donde se ubica e
        index.html
    <li>¿Entiende la expresión regular en el código y se da cuenta de para qué es útil?</li>
         Fue ùtil para separar las palabras por espacios en blanco y tambièn para hacer uso de los saltos de lìnea.
    <li>Note que la respuesta del servidor está en formato JSON, ¿Habrá alguna forma de verla directamente?</li>
        Si, lo manera más simple es omitiendo la parte del .setHeader del response, de esa manera la respuesta
        del servidor llegará con el Content-Type: text/HTML de manera predeterminada
</ul>
<tr><td>III. CONCLUSIONES<br><br>
     En el proyecto comprendimos NodeJS, también JSON, los cuales fueron indispensables para el desarrollo del proyecto<br>también usamos JavaScript, la cual ya conocìamos desde el anterior semestre, nos dividimos en Back y Front end.
     <br>Cada integrante trabajó en su rama, según la idea de solución que  consideraba.<br>Hicimos reuniones meet, las cuales nos sirvieron para comprender el código y para organizar nuestras ideas.<br>La bibliografía que nos presentó el ingeniero fue de gran ayuda para lograr el desarrollo del laboratorio presentado.
    </td></tr>
</tbody>
</table>


<table>
<theader>
<tr><th>RETROALIMENTACIÓN GENERAL
    </th></tr>
</theader>
<tbody>
<tr><td>
    <pre>                                                                                          </pre>
    <pre>                                                                                          </pre>
    </td></tr>
</tbody>
</table>
</div>    
<p><b>REFERENCIAS Y BIBLIOGRAFÍA</b></p>
<ul>
    <li>https://www.w3schools.com/nodejs/nodejs_intro.asp</li>
    <li>https://nodejs.org/en/docs/guides/getting-started-guide/</li>
    <li>https://nodejs.dev/learn</li>
    <li>https://www.w3schools.com/js/js_api_fetch.asp</li>
    <li>https://expressjs.com/es/</li>
    <li>https://developer.mozilla.org/es/docs/Web/API/Fetch_API/Using_Fetch</li>
    <li>https://developer.mozilla.org/es/docs/Learn/Server-side/Express_Nodejs/Introduction</li>
</ul>

