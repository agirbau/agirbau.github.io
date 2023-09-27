---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<style style="text/css">
  	.hoverTable{
		width:85%; 
		border-collapse:collapse; 
		border: 0px;
	}
	.hoverTable td{ 
		padding:7px; 
        border:#4e95f4 0px solid;
        transition: all 0.3s; /* Add a transition for smooth animation */
	}
	/* Define the default color for all the table rows */
	.hoverTable tr{
		background: #ffffff;
	}
	/* Define the hover highlight color for the table row */
    .hoverTable tr:hover {
          background-color: #f7f7f7;
    }
    /* Increase the size of everything in the row on hover */
    .hoverTable tr:hover td {
        padding: 14px; /* Increase padding */
        font-size: 16px; /* Increase font size */
    }
</style>

<table class="hoverTable">
  <col style="width:75%">
  <col style="width:25%">
  {% for post in site.publications reversed %}
    {% include archive-single-pub.html %}
  {% endfor %}
</table>
