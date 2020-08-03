---
layout: default
title: Home
permalink: /
---

<html>
<head>
    <meta charset="utf-8">
    <title>Roberto Reale</title>
</head>
<body>
<script>
    var lang = navigator.language || navigator.userLanguage;
    if (lang.indexOf('es') == 0)
        window.location = '/es/';
    else if (lang.indexOf('fr') == 0)
        window.location = '/fr/';
    else if (lang.indexOf('it') == 0)
        window.location = '/it/';
    else if (lang.indexOf('pl') == 0)
        window.location = '/pl/';
    else
        window.location = '/en/';
</script>
</body>
</html>
