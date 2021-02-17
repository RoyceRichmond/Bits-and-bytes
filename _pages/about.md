---
layout: defaults/page
permalink: about.html
narrow: true
title: About me
images:
  - https://lh3.googleusercontent.com/pw/ACtC-3fUzll0Lps4vCyjO9dj-oN5NaqzxjMBTHkdksb33rvzSmGZlOgRaSOyUgxliDJCt9zznw7IixllIe8PJrJGUfe-TawGQ9Lea_PHGdmATif2MGvibpcSoHwUAnndqN6vSodDz3OtN6jFhaUKEsM2SHwuyw=w524-h654-no?authuser=0
  - https://lh3.googleusercontent.com/pw/ACtC-3cS4tm6MfbUIc_jmcoeMgzzlHNEDDSXDhFNY1r_-UrQGenMqyRiXL9LO_o0gSNlI3iwPWhieeEO0A2XJmaryZt21-dk5ygEejt9H6e6fh4n5Gu7nBgFZP1RQO9bESrJFtZET9F-4dJi3ZMrEHmL4aeySg=s600-no?authuser=0
  - https://lh3.googleusercontent.com/pw/ACtC-3fLFyPbs_lO5XILYe8qLWAR9orPegCHX7e_B42YWE8ZAtrsJ_7Dw9q7C0gMme-3HBojNBXmMk29_S_bLBs52hZyTAf0ozOEBsFmM28x1NZbGkMjKBVyn7RXEdYYApGVBtqKPe-d2uvCc5hvJEH4Kgo54Q=s600-no?authuser=0
---

## Who am i ?

My name is Royce Richmond pleased to meet you, I studied B.E in Mechatronics in the ["Unidad Profesional Interdisciplinaria en Ingeniería y Tecnologías Avanzadas"](https://www.upiita.ipn.mx/).
I had the opportunity to serve as chair of the technical chapter RAS (Robotics and Automation Society) of the IEEE UPIITA student branch

Currently I'm pursuing the Master of Science in Computer Engineering in the "Centro de Investigación en Computación" CIC - IPN.

## Hobbies
Let me tell you about my hobbies.
- Reading(i love reading on my kindle tbh).
- Playing electric guitar.
- Programming (python)
- Learning (I enroll on online courses, a lot)
- Youtube (of course, its my main source of entertainment)
- Playin videogames(I love Hollow knight, awesome game wit a lot of content)

Last but not least, here are some of the pictures from places or events i've been, personally i love to take pictures to every place i go, so i have a souvenir that may last forever.

<div id="carouselExampleControls" class="carousel slide mb-4" data-ride="carousel">
    <div class="carousel-inner">
        {% for img in page.images %}
            <div class="carousel-item {% if forloop.first %}active{% endif %}">
                <img src="{{ img }}" class="d-block w-120" alt="">
            </div>
        {% endfor %}
    </div>
    <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="false"></span>
        <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="false"></span>
        <span class="sr-only">Next</span>
    </a>
</div>