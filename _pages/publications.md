---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<style style="text/css">
    .hoverTable {
        width: 85%;
        border-collapse: collapse;
        border: 0px;
        position: relative;
    }

    .hoverTable td {
        padding: 7px;
        border: #4e95f4 0px solid;
        transition: all 0.3s; /* Add a transition for smooth animation */
    }

    /* Define the default color for all the table rows */
    .hoverTable tr {
        background: #ffffff;
        transition: background-color 0.3s; /* Add a transition for smooth background color change */
    }

    /* Define the hover highlight color for the table row */
    .hoverTable tr:hover {
        background-color: #f7f7f7;
    }

    /* Increase the size of everything on the right side of the row on hover using zoom */
    .hoverTable tr:hover td {
        transform-origin: right center;
        transform: scale(1.2); /* Increase the size by 20% (adjust as needed) */
    }
</style>


<table class="hoverTable">
  <col style="width:75%">
  <col style="width:25%">
  {% for post in site.publications reversed %}
    {% include archive-single-pub.html %}
  {% endfor %}
</table>
