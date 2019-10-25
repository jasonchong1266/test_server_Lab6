<!DOCTYPE html>
<html>
    <head>
        <title>Test Server Lab 6</title>
    </head>
    <body>
        {% block content %}

            {{ content|raw }}

        {% endblock %}
    </body>
</html>
