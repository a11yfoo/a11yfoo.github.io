---
title: AX_FOCUS_01
gistID: 0c43eb29bcb63d363aea
layout: nots-devtools
tags:
- devtools
---

<h2 aria-describedby="{{ page.gistID }}">Not Begin</h2>
<div class="rendered-not">
<!-- Bad: focusable element has zero area due to floated child element -->
<a href="http://www.google.com">
  <img src="http://www.google.com/images/srpr/logo11w.png"
       style="float: left" width="269" height="95" alt="Google" >
</a>
</div> <!-- rendered-not -->

<h2 aria-describedby="{{ page.gistID }}">Not End</h2>

<h3 aria-describedby="{{ page.gistID }}">Code for this Not</h3>
{% gist page.gistID %}