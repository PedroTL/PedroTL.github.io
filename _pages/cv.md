---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<button onclick="toggleFile()">Show/Hide Resume</button>

<div id="pdfContainer" style="display: none;">
  <embed id="pdfEmbed" src="{{ site.baseurl }}/files/Resume.pdf" width="600" height="700" type='application/pdf'>
</div>

<script>
function toggleFile() {
  var file = document.getElementById("pdfContainer");
  if (file.style.display === "none") {
    file.style.display = "block";
  } else {
    file.style.display = "none";
  }
}
</script>
