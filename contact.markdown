---
title: Contact
permalink: "/contact/"
layout: page
---

<section class="py-5">
	<div class="container">
		<p class="mb-3">
        <a class="mb-0 text-decoration-none text-dark me-2" href="tel:{{ site.phone }}">
          <span class="fas fa-phone"></span> {{ site.phone }}
        </a><br>
        <a class="mb-0 text-decoration-none text-dark" href="mailto:{{ site.email }}">
          <span class="fas fa-envelope"></span> {{ site.email }}
        </a>
      </p>
	  {% include contact.html %}
	</div>
</section>