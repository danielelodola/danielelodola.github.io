---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title2: This is the home page
---
<h2>{{ "Hello World!" | downcase }}</h2>

<h3>Title 3</h3>

{% include text_block.html %}

<!-- Début de widget de badge Calendly -->
<link href="https://assets.calendly.com/assets/external/widget.css" rel="stylesheet">
<script src="https://assets.calendly.com/assets/external/widget.js" type="text/javascript"></script>
<script type="text/javascript">Calendly.initBadgeWidget({url: 'https://calendly.com/lodola/prise-de-contact-15-minutes', text: 'Planifier du temps avec moi', color: '#00a2ff', branding: false});</script>
<!-- Fin de widget de badge Calendly -->