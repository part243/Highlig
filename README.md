# Highlig


Agregar antes del </head> lo siguiente:

  <link type="text/css" rel="stylesheet" href="https://rawgit.com/part243/Highlig/master/SyntaxHighlighter.css"></link>
    <script src="https://rawgit.com/part243/Highlig/master/shCore.js"></script>
    <script src="https://rawgit.com/part243/Highlig/master/shBrushCpp.js"></script>
    <script src="https://rawgit.com/part243/Highlig/master/shBrushCSharp.js"></script>
    <script src="https://rawgit.com/part243/Highlig/master/shBrushCss.js"></script>
    <script src="https://rawgit.com/part243/Highlig/master/shBrushDelphi.js"></script>
    <script src="https://rawgit.com/part243/Highlig/master/shBrushJava.js"></script>
    <script src="https://rawgit.com/part243/Highlig/master/shBrushJScript.js"></script>
    <script src="https://rawgit.com/part243/Highlig/master/shBrushPhp.js"></script>
    <script src="https://rawgit.com/part243/Highlig/master/shBrushPython.js"></script>
    <script src="https://rawgit.com/part243/Highlig/master/shBrushRuby.js"></script>
    <script src="https://rawgit.com/part243/Highlig/master/shBrushSql.js"></script>
    <script src="https://rawgit.com/part243/Highlig/master/shBrushVb.js"></script>
      <script src="https://rawgit.com/part243/Highlig/master/shBrushXml.js"></script>

Luego antes del </footer> el siguiente script:
   <script language="javascript">
        dp.SyntaxHighlighter.HighlightAll('code');
    </script>



PARA USAR hacerlo de la siguiente manera dependiendo de la codificación cambiar la clase: en este caso usaremos de java
<pre name="code" class="java">  
Aquí va el código a resaltar
</pre>
