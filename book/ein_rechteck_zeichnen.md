# Ein Rechteck zeichnen

<iframe src="https://player.vimeo.com/video/207923224?title=0&byline=0&portrait=0" width="100%" height="430" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

<!--sec data-title="Links" data-id="links" data-show=true ces-->

* [Python - Turtle](https://docs.python.org/3.6/library/turtle.html)

<!--endsec-->

<!--sec data-title="Python-Programm" data-id="editor" data-show=true data-collapse=true ces-->

{%ace edit=true, lang='python' %}
import turtle

turtle.forward(25)
turtle.left(30)
turtle.reset()
turtle.shape("turtle")
turtle.forward(100)
turtle.left(90)
turtle.forward(100)
turtle.left(90)
turtle.forward(100)
turtle.left(90)
turtle.forward(100)
turtle.left(90)
turtle.color('red')
turtle.forward(100)
turtle.undo()
turtle.exitonclick()
{%endace%}

<!--endsec-->

<!--sec data-title="Quiz" data-id="quiz" data-show=true data-collapse=true ces-->

<quiz name="">
    <question>
        <p>Mit welchem Befehl bekomme ich eine Hilfestellung für die Funktion turtle.width() ?</p>
        <answer>man(turtle.width)</answer>
        <answer correct>help(turtle.width)</answer>
        <answer>turtle.width.help</answer>
        <answer>width.man()</answer>
    </question>
</quiz>

{%fbq%}Gebe den Befehl $$turtle.color('red')## ein um die Schildkröte in eine rote Schildkröte zu verwandeln.{%endfbq%}

<!--endsec-->
