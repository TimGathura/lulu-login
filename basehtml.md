<!-- The bootstrap base.html -->

<!--{% load static %}
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{% block title %}KIMC STUDIO INVENTORY{% endblock title %}</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous" />
   <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">

    <link rel="stylesheet" href="{% static 'css/output.css' %}" />

    <style>
        body {
            background-image: url('{% static "images/logo 2020 clear-01 (3) (2) (2) (3).png" %}');
            background-repeat: no-repeat;
            background-position: center center;
            background-size: contain;
            backdrop-filter: blur(8px);
            min-height: 100vh;
        }
        </style>
   {% block styles %}
    {% endblock styles %}
</head>

<body>
    {% block navbar %}
    {% include 'library/navbar.html' %}
    {% endblock navbar %}

    {% include "library/messages.html" %}

    <div class="container">
        {% block content %}
        {% endblock content %}
    </div>

    {% block footer %}

    {% endblock footer %}

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" defer></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js" defer></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" defer></script>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js" defer></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" defer></script>

    {% block scripts %} {% endblock scripts %}
</body>

</html>-->