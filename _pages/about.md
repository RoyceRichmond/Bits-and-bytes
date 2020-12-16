---
layout: defaults/page
permalink: about.html
narrow: true
title: About me
images:
  - https://images.unsplash.com/photo-1421789665209-c9b2a435e3dc?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=5b1016b885e7438c4633109d77368d4d&auto=format&fit=crop&w=1651&q=80
  - https://images.unsplash.com/photo-1476514525535-07fb3b4ae5f1?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=468a8c18f5d811cf03c654b653b5089e&auto=format&fit=crop&w=1650&q=80
  - https://images.unsplash.com/photo-1504626835342-6b01071d182e?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=975855d515c9d56352ee3bfe74287f2b&auto=format&fit=crop&w=1651&q=80
---

## Who am i ?

My name is Royce Richmond pleased to meet you, I studied Bachelor of Engineering in Mechatronics in the ["Unidad Profesional Interdisciplinaria en Ingeniería y Tecnologías Avanzadas"](https://www.upiita.ipn.mx/).
I had the opportunity to serve as chair of the technical chapter RAS (Robotics and Automation Society) of the IEEE UPIITA student branch

Currently I'm pursuing the Master of Science in Computer Engineering in the "Centro de Investigación en Computación" CIC - IPN.

## Hobbies
That that you know me a little bit i can tell you what are my hobbies.
- Reading(i love reading on my kindle tbh).
- Playing electric guitar.
- Programming (python)
- Learning (I enroll on online courses, a lot)
- Youtube (of course, its my main source of entertainment)

And this is a more sophisticated example, using the JS to include a carousel of images:

<div id="carouselExampleControls" class="carousel slide mb-4" data-ride="carousel">
    <div class="carousel-inner">
        {% for img in page.images %}
            <div class="carousel-item {% if forloop.first %}active{% endif %}">
                <img src="{{ img }}" class="d-block w-100" alt="">
            </div>
        {% endfor %}
    </div>
    <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
    </a>
</div>