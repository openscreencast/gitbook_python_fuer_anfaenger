# Einfaches Zeichnen mit turtle

<iframe src="https://player.vimeo.com/video/140204552?title=0&byline=0&portrait=0" width="100%" height="430" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

<!--sec data-title="Links" data-id="links" data-show=true ces-->

* [Python - Turtle](https://docs.python.org/3.6/library/turtle.html)

<!--endsec-->

<!--sec data-title="Python-Programm" data-id="editor" data-show=true data-collapse=true ces-->

{%ace edit=true, lang='python' %}
import turtle

turtle.shape("turtle")
turtle.forward(25)
turtle.exitonclick()
{%endace%}

<!--endsec-->

<!--sec data-title="Quiz" data-id="quiz" data-show=true data-collapse=true ces-->

<quiz name="">
    <question>
        <p>Mit welchem Befehl kann man die Zeichnungen der Schildkröte vom Modul turtle löschen ?</p>
        <answer>turtle.backward()</answer>
        <answer>turtle.shape()</answer>
        <answer>turtle.right()</answer>
        <answer correct>turtle.reset()</answer>
    </question>
</quiz>

<!--endsec-->
