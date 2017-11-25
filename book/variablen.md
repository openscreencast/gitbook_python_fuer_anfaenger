# Variablen

<iframe src="https://player.vimeo.com/video/243531746?title=0&byline=0&portrait=0" width="100%" height="430" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

<!--sec data-title="Links" data-id="links" data-show=true ces-->

* [Eine informelle Einführung in Python](https://py-tutorial-de.readthedocs.io/de/python-3.3/introduction.html)

<!--endsec-->

<!--sec data-title="editor" data-id="editor" data-show=true data-collapse=true ces-->

{%ace edit=true, lang='python' %}
import turtle
import math

# x sei 5, x*2 = 10

x = 5
y = "Hi turtle !"
print(x)
print(y)

x = 10
timmy = turtle
turtle.shape("turtle")
timmy.forward(x)
timmy.left(90)
timmy.forward(x)
timmy.left(90)
timmy.forward(x)
timmy.left(90)
timmy.forward(x)
timmy.left(90)
turtle.exitonclick()

x = math.sqrt(9)
y = 10**2
print(x)
print(y)
{%endace%}

<!--endsec-->

<!--sec data-title="Quiz" data-id="quiz" data-show=true data-collapse=true ces-->

<quiz name="">
    <question>
        <p>Was ist eine Variable ?</p>
        <answer>ein Modul von Python</answer>
        <answer>eine SQlite-Funktion in Python</answer>
        <answer>eine Bibliothek von Python</answer>
        <answer correct>ein Behälter für einen Wert</answer>
    </question>
    <question>
        <p>Welches Modul muss für die sqrt-Funktion importiert werden ?</p>
        <answer>turtle</answer>
        <answer>sys</answer>
        <answer correct>math</answer>
        <answer>urllib2</answer>
    </question>
</quiz>

<!--endsec-->
