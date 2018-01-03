# Schleifen

<iframe src="https://player.vimeo.com/video/249418130?title=0&byline=0&portrait=0" width="100%" height="430" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

<!--sec data-title="Links" data-id="links" data-show=true ces-->

* [Eine informelle Einführung in Python](https://py-tutorial-de.readthedocs.io/de/python-3.3/introduction.html)

<!--endsec-->

<!--sec data-title="Python-Programm" data-id="editor" data-show=true data-collapse=true ces-->

{%ace edit=true, lang='python' %}
import turtle

for name in "Paula", "David", "Rafael":
    print("Hallo " + name)

for i in range(10):
    print(i)

total = 0
for i in 5, 7, 11, 13:
    print(i)
    total = total + i
print(total)

for _ in range(5):
    print("Hallo !")

turtle.shape("turtle")
for i in range(10):
    turtle.forward(15)
    turtle.penup()
    turtle.forward(5)
    turtle.pendown()
turtle.exitonclick()
{%endace%}

<!--endsec-->

<!--sec data-title="Quiz" data-id="quiz" data-show=true data-collapse=true ces-->

<quiz name="">
    <question>
        <p>Mit welcher Python-Anweisung beginnt eine Schleife ?</p>
        <answer correct>for</answer>
        <answer>return</answer>
        <answer>if</answer>
        <answer>LET</answer>
    </question>
    <question>
        <p>Mit welcher turtle-Funktion kann die Schildkröte sich bewegen ohne zu zeichnen ?</p>
        <answer>turtle.pendown()</answer>
        <answer correct>turtle.penup()</answer>
        <answer>turtle.shape()</answer>
        <answer>turtle.forward()</answer>
    </question>
</quiz>

<!--endsec-->
