---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<button onclick="toggleFile('english')">Show/Hide English Resume</button>
<button onclick="toggleFile('portuguese')">Show/Hide Portuguese Resume</button>

<div id="englishPdfContainer" style="display: none;">
    <embed src="{{ site.baseurl }}/files/Resume.pdf" width="600" height="700" type='application/pdf'>
</div>

<div id="portuguesePdfContainer" style="display: none;">
    <embed src="{{ site.baseurl }}/files/Curriculo.pdf" width="600" height="700" type='application/pdf'>
</div>

<script>
function toggleFile(language) {
    var englishContainer = document.getElementById("englishPdfContainer");
    var portugueseContainer = document.getElementById("portuguesePdfContainer");

    if (language === 'english') {
        if (englishContainer.style.display === "none") {
            englishContainer.style.display = "block";
            portugueseContainer.style.display = "none";
        } else {
            englishContainer.style.display = "none";
        }
    } else if (language === 'portuguese') {
        if (portugueseContainer.style.display === "none") {
            portugueseContainer.style.display = "block";
            englishContainer.style.display = "none";
        } else {
            portugueseContainer.style.display = "none";
        }
    }
}
</script>
