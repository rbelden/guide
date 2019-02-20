---
title: Use Media Queries to Create Responsive Layouts
---
## Use Media Queries to Create Responsive Layouts

In this challenge, you are required to make the header area occupy the top row completely and the footer area occupy the bottom row completely CSS grid in <code> div class="container"</code>.

<strong>Hint</strong><br>
When the viewport is <code>400px</code> or more, container class should have a grid-template-areas property in which the footer and header areas occupy the top and bottom rows respectively and advert and content occupy the left and right columns of the middle row.

<strong>Solution</strong><br>
Since the challenge requires you to only adjust the header and footer, declare the following in your <code>@media (min-width) .container</code> CSS code block:
  
<p><code>grid-template-areas:<br>“header header”<br>“advert content”<br>“footer footer”;</code></p>
